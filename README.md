- [Classes](#classes)
- [Scope](#scope)
	- [Local Scope](#local-scope)
		- [Function inside Function](#function-inside-function)
	- [Global Scope](#global-scope)
		- [Naming variables](#naming-variables)
		- [global keyword](#global-keyword)
	- [nonlocal variable](#nonlocal-variable)
- [String Formatting](#string-formatting)
	- [f-string](#f-string)
		- [fixed point number](#fixed-point-number)
		- [More variables](#more-variables)
		- [Percentage](#percentage)
		- [HEX](#hex)
		- [Big number](#big-number)
		- [Positive number](#positive-number)
		- [Aligning](#aligning)
	- [format()](#format)
		- [fixed point number](#fixed-point-number-1)
		- [More variables](#more-variables-1)
- [Modules](#modules)
	- [Changing name](#changing-name)
	- [built-in modules](#built-in-modules)
	- [Methods of a module](#methods-of-a-module)
	- [Importing part of a module](#importing-part-of-a-module)
- [Context Manager](#context-manager)
	- [write on file](#write-on-file)
	- [Custom Context Manager](#custom-context-manager)
	- [delete file](#delete-file)
- [Debugger](#debugger)
	- [Importing Python Debugger](#importing-python-debugger)
	- [Add break point](#add-break-point)
	- [Commands](#commands)
- [Handling Errors](#handling-errors)
	- [Try except](#try-except)
		- [Common exceptions](#common-exceptions)
	- [else](#else)
	- [finally](#finally)
	- [Custom exception](#custom-exception)
	- [Representing exception](#representing-exception)
- [Magic Methods(Dunder Methods)](#magic-methodsdunder-methods)
	- [__init__()](#init)
	- [__repr__()](#repr)
	- [__add__()](#add)
	- [__len__()](#len)
	- [__eq__()](#eq)
	- [__getitem__()](#getitem)
	- [__setitem__()](#setitem)
	- [__delitem__()](#delitem)
	- [__reversed__()](#reversed)
	- [__call__()](#call)
	- [Other dunder methods](#other-dunder-methods)
- [Iterators and Generators](#iterators-and-generators)
	- [Iterator](#iterator)
		- [Custom iterator](#custom-iterator)
	- [Generator](#generator)
- [Decorators](#decorators)
	- [Error Handler Decorator](#error-handler-decorator)
	- [Run Time Decorator](#run-time-decorator)
- [Metaclasses](#metaclasses)
	- [Create metaclass](#create-metaclass)
- [Map, Filter and Reduce](#map-filter-and-reduce)
	- [map()](#map)
		- [Zip function with Map](#zip-function-with-map)
	- [filter()](#filter)
	- [reduce()](#reduce)
- [Asynchronous and Parallel Programming](#asynchronous-and-parallel-programming)
	- [Parallelism(CPU bound)](#parallelismcpu-bound)
	- [Concurrency(I/O bound)](#concurrencyio-bound)
	- [AsyncIO(I/O bound)](#asyncioio-bound)
		- [asyncio.gather](#asynciogather)
		- [asyncio.create_task](#asynciocreate_task)
- [Pytest](#pytest)
	- [Installation](#installation)
	- [Usage](#usage)
# Classes

# Scope
## Local Scope
```python
def my_func():
	a = 10
	print(a)

my_func()
```
### Function inside Function
```python
def my_func():
	a = 10
	def my_inner_func():
		print(a)
	my_inner_func()

my_func()
```
## Global Scope
```python
a = 10
def my_func():
	print(a)

myfunc()
```
### Naming variables
```python
a = 10

def my_func():
	a = 20
	print(a)

my_func()
```
### global keyword
```python
def my_func():
	global a
	a = 10
	
my_func()
print(a)
```
To use the global value inside a function, first the function needs to be called! You can also change the global variable inside a function:
```python
a = 10

def my_func():
	global a
	a = 20

my_func()
print(a)
```
## nonlocal variable
```python
a = 0
def outer_func():
	a = 10
	def inner_func():
		nonlocal a
		a = 20
		print(a)
	inner_func()
	print(a)

outer_func()
print(a)
```
# String Formatting
## f-string
**f-string is only available in python 3.6 above.**
```python
num = 23
print(f'This is your number: {num}')
```
### fixed point number
```python
num = 3.3333333
print(f'This is your number: {num:.2f}')
```
### More variables
```python
numOne = 3
numTwo = 4
numThree = 5
print(f'number one: {numOne}\nnumber two: {numTwo}\nnumber three: {numThree}')
```
### Percentage
```python
num = 0.25 # It's 25 percent.
print(f'Your score is {num:.0%}')
```
### HEX
```python
num = 255
print(f'Hex of {num} is {num:x}') # X used for upper-case and x used for lower-case
```
### Big number
```python
num = 3000000
print(f'Your number is {num:,}') # 3,000,000
```
### Positive number
```python
num = 3
print(f'number: {num:+}')
```
### Aligning
```python
num = 34
print(f'The number {num:^4} is your number!') # 4 is the number for spaces
print(f'The number {num:>4} is your number!')
print(f'The number {num:<4} is your number!')
```
## format()
```python
num = 23
print('This is your number: '.format(num))
```
### fixed point number
```python
num = 3.3333333
print('This is your number: {:.2f}'.format(num))
```
### More variables
```python
numOne = 3
numTwo = 4
numThree = 5
print('number one: {}\nnumber two: {}\nnumber three: {}'.format(numOne, numTwo, numThree))
```
You can use index to make custom order:
```python
numOne = 3
numTwo = 4
numThree = 5
print('number one: {0}\nnumber two: {1}\nnumber three: {2}'.format(numOne, numTwo, numThree))
```
Another way:
```python
numOne = 3
numTwo = 4
numThree = 5
print('number one: {first}\nnumber two: {second}\nnumber three: {third}'.format(first = numOne, second = numTwo, third = numThree))
```
# Modules
Create mymodule.py file:
```python
def adder(a, b):
	return a + b
```
Now create another .py file to use the module:
```python
import mymodule

c = mymodule.adder(3, 5)
print(c)
```
## Changing name
```python
import matplotlib.pyplot as plt
```
## built-in modules
[Python Module Index — Python 3.10.0 documentation](https://docs.python.org/3/py-modindex.html)
## Methods of a module
```python
import datetime

print(dir(datetime))
```
## Importing part of a module
```python
from datetime import datetime as time

print(time.now())
```
# Context Manager
```python
with open('test.txt', 'r') as f:
	data = f.read()
```
| key | operation |
| --- |:---------:|
|  r  |    read   |
|  a  |   append  |
|  w  |   write   |
|  x  |   create  |
To open file as binary, use b beside the key(t for text mode):
```python
with open('test.txt', 'rt') as f:
    print(f.read(5))
    print(f.readline())
```
## write on file
```python
oldData = ''

with open('test.txt', 'r') as f:
    oldData = f.read()

newData = oldData.replace('\n', '\t')

with open('test.txt', 'w') as f:
    f.write(newData)
```
## Custom Context Manager
```python
from pymongo import MongoClient
  
class MongoDBConnectionManager():
    def __init__(self, hostname, port):
        self.hostname = hostname
        self.port = port
        self.connection = None
  
    def __enter__(self):
        self.connection = MongoClient(self.hostname, self.port)
        return self
  
    def __exit__(self, exc_type, exc_value, exc_traceback):
        self.connection.close()
  
# connecting with a localhost
with MongoDBConnectionManager('localhost', '27017') as mongo:
    collection = mongo.connection.SampleDb.test
    data = collection.find({'_id': 1})
    print(data.get('name'))
```
## delete file
```python
import os

if os.path.exists('test.txt'):
    os.remove('test.txt')
```
# Debugger
## Importing Python Debugger
```python
import pdb
```
## Add break point
```python
pdb.set_trace()
```
## Commands
| Key | Command |
| --- | :---: |
|n(ext)|Continue execution until the next line in the current function is reached or it returns.|
|c(ont(inue))|Continue execution, only stop when a breakpoint is encountered.|
|l(ist)|List source code for the current file.|
|s(tep)|xecute the current line, stop at the first possible occasion.|
|b(reak)|With a _lineno_ argument, set a break there in the current file. With a _function_ argument, set a break at the first executable statement within that function.|
|cl(ear)|With a _filename:lineno_ argument, clear all the breakpoints at this line. With a space separated list of breakpoint numbers, clear those breakpoints. Without argument, clear all breaks|
|p|Evaluate the _expression_ in the current context and print its value.|
More commands on: [pdb — The Python Debugger — Python 3.10.0 documentation](https://docs.python.org/3/library/pdb.html)
# Handling Errors
## Try except
```python
try:
	print(10/0)
except:
	print('An exception occured!')
```
We can use specific except:
```python
try:
	print(10/0)
except ZeroDivisionError:
	print('Zero Division Error')
except:
	print('An exception occured!')
```
### Common exceptions
|Exception | Cause of Error|
| --- | :---: |
|`AssertionError`|Raised when an `assert` statement fails.|
|`AttributeError`|Raised when attribute assignment or reference fails.|
|`EOFError`|Raised when the `input()` function hits end-of-file condition.|
|`FloatingPointError`|Raised when a floating point operation fails.|
|`GeneratorExit`|Raise when a generator's `close()` method is called.|
|`ImportError`|Raised when the imported module is not found.|
|`IndexError`|Raised when the index of a sequence is out of range.|
|`KeyError`|Raised when a key is not found in a dictionary.|
|`KeyboardInterrupt`|Raised when the user hits the interrupt key (`Ctrl+C` or `Delete`).|
|`MemoryError`|Raised when an operation runs out of memory.|
|`NameError`|Raised when a variable is not found in local or global scope.|
|`NotImplementedError`|Raised by abstract methods.|
|`OSError`|Raised when system operation causes system related error.|
|`OverflowError`|Raised when the result of an arithmetic operation is too large to be represented.|
|`ReferenceError`|Raised when a weak reference proxy is used to access a garbage collected referent.|
|`RuntimeError`|Raised when an error does not fall under any other category.|
|`StopIteration`|Raised by `next()` function to indicate that there is no further item to be returned by iterator.|
|`SyntaxError`|Raised by parser when syntax error is encountered.|
|`IndentationError`|Raised when there is incorrect indentation.|
|`TabError`|Raised when indentation consists of inconsistent tabs and spaces.|
|`SystemError`|Raised when interpreter detects internal error.|
|`SystemExit`|Raised by `sys.exit()` function.|
|`TypeError`|Raised when a function or operation is applied to an object of incorrect type.|
|`UnboundLocalError`|Raised when a reference is made to a local variable in a function or method, but no value has been bound to that variable.|
|`UnicodeError`|Raised when a Unicode-related encoding or decoding error occurs.|
|`UnicodeEncodeError`|Raised when a Unicode-related error occurs during encoding.|
|`UnicodeDecodeError`|Raised when a Unicode-related error occurs during decoding.|
|`UnicodeTranslateError`|Raised when a Unicode-related error occurs during translating.|
|`ValueError`|Raised when a function gets an argument of correct type but improper value.|
|`ZeroDivisionError`|Raised when the second operand of division or modulo operation is zero.|
## else
else will be executed if no errors occured:
```python
try:
	print(10/0)
except:
	print('An exception occured!')
else:
	print('Successfully completed!')
```
## finally
finally will be always executed. You can use it to close objects or something:
```python
try:
	f = open("test.txt")
	f.write("Testing...")
except:
	print("Something went wrong when writing to the file!")
finally:
	f.close()
```
## Custom exception
We want to get a number to calculate the factorial of it:
```python
import math

num = input('Please enter your number: ')

if num.isdigit()==False:
	raise TypeError('Only positive numbers are allowed!')
digit = int(num)
print(math.factorial(digit))
```
## Representing exception
```python
try:
	print(a)
except Exception as e:
	print(e)
```
# Magic Methods(Dunder Methods)
## __init__()
```python
class String:
	def __init__(self, string):
		self.string = string
	
newString = String('Hello')
print(newString)
```
The print function above gives us the memory location of the object. To get the string itself we need another dunder method called representation...
## __repr__()
```python
class String:
    def __init__(self, string):
        self.string = string
    def __repr__(self):
        return f'{self.string}'

newString = String('Hello')
print(newString)
```
Now, how we can combine this string with another one?!(since the str object can't combine with another class!)
## __add__()
```python
class String:
    def __init__(self, string):
        self.string = string
    def __repr__(self):
        return f'{self.string}'
    def __add__(self, anotherString):
        return self.string + str(anotherString)

newString = String('Hello')
print(newString + ' world!')
```
## __len__()
For getting the length of an object:
```python
class String:
	def __init__(self, string):
		self.string = string
	def __repr__(self):
		return f'{self.string}'
	def __add__(self, anotherString):
		return self.string + str(anotherString)
	def __len__(self):
		return len(self.string)
		
newString = String('Hello')
print(len(newString))
```
## __eq__()
For checking equality of two things:
```python
class String:
	def __init__(self, string):
		self.string = string
	def __repr__(self):
		return f'{self.string}'
	def __add__(self, anotherString):
		return self.string + str(anotherString)
	def __len__(self):
		return len(self.string)
	def __eq__(self, anotherString):
		return self.string==anotherString
		
newString = String('Hello')
print(newString=='Hello')
```
## __getitem__()
To get an item with the index:
```python
class String:
	def __init__(self, string):
		self.string = string
	def __repr__(self):
		return f'{self.string}'
	def __add__(self, anotherString):
		return self.string + str(anotherString)
	def __len__(self):
		return len(self.string)
	def __eq__(self, anotherString):
		return self.string==anotherString
	def __getitem__(self, index:int):
		return self.string[index]
		
newString = String('Hello')
print(newString[0])
```
## __setitem__()
As you know, str object does not support item assignment. But we are making custom str object. So to set an item with the index:
```python
class String:
	def __init__(self, string):
		self.string = string
	def __repr__(self):
		return f'{self.string}'
	def __add__(self, anotherString):
		return self.string + str(anotherString)
	def __len__(self):
		return len(self.string)
	def __eq__(self, anotherString):
		return self.string==anotherString
	def __getitem__(self, index:int):
		return self.string[index]
	def __setitem__(self, index:int):
		newString == ''
		for i in range(len(self.string)):
			if i == index:
				newString += newValue
			else:
				newString += self.string[i]
		self.string = newString
		
newString = String('Hello')
newString[0] = 'h'
print(newString)
```
## __delitem__()
Because str objects are immutable, like the previous one, we should write the function manually:
```python
class String:
	def __init__(self, string):
		self.string = string
	def __repr__(self):
		return f'{self.string}'
	def __add__(self, anotherString):
		return self.string + str(anotherString)
	def __len__(self):
		return len(self.string)
	def __eq__(self, anotherString):
		return self.string==anotherString
	def __getitem__(self, index:int):
		return self.string[index]
	def __setitem__(self, index:int):
		newString == ''
		for i in range(len(self.string)):
			if i == index:
				newString += newValue
			else:
				newString += self.string[i]
		self.string = newString
	def __delitem__(self, index:int):
		newString = ''
		for i in range(len(self.string)):
			if i != index:
				newString += self.string[i]
		self.string = newString
		
newString = String('Hello')
del newString[0]
print(newString)
```
## __reversed__()
Reverse the string:
```python
class String:
	def __init__(self, string):
		self.string = string
	def __repr__(self):
		return f'{self.string}'
	def __add__(self, anotherString):
		return self.string + str(anotherString)
	def __len__(self):
		return len(self.string)
	def __eq__(self, anotherString):
		return self.string==anotherString
	def __getitem__(self, index:int):
		return self.string[index]
	def __setitem__(self, index:int):
		newString == ''
		for i in range(len(self.string)):
			if i == index:
				newString += newValue
			else:
				newString += self.string[i]
		self.string = newString
	def __delitem__(self, index:int):
		newString = ''
		for i in range(len(self.string)):
			if i != index:
				newString += self.string[i]
		self.string = newString
	def __reversed__(self):
		return self.string[::-1]
		
newString = String('Hello')
print(reversed(newString))
```
## __call__()
use the object instance to call a function:
```python
class String:
	def __init__(self, string):
		self.string = string
	def __repr__(self):
		return f'{self.string}'
	def __add__(self, anotherString):
		return self.string + str(anotherString)
	def __len__(self):
		return len(self.string)
	def __eq__(self, anotherString):
		return self.string==anotherString
	def __getitem__(self, index:int):
		return self.string[index]
	def __setitem__(self, index:int):
		newString == ''
		for i in range(len(self.string)):
			if i == index:
				newString += newValue
			else:
				newString += self.string[i]
		self.string = newString
	def __delitem__(self, index:int):
		newString = ''
		for i in range(len(self.string)):
			if i != index:
				newString += self.string[i]
		self.string = newString
	def __reversed__(self):
		return self.string[::-1]
	def __call__(self, value):
		print(value)
		
newString = String('Hello')
newString('test')
```
## Other dunder methods
To see the full list visit [3. Data model — Python 3.10.0 documentation](https://docs.python.org/3/reference/datamodel.html#basic-customization)
# Iterators and Generators
## Iterator
```python
li = ['apple', 'orange', 'banana']

myIter = iter(li)
print(next(myIter))
print(next(myIter))
print(next(myIter))
```
### Custom iterator
```python
class EvenNumbers:
	def __iter__(self):
		self.a = 0
		return self
	def __next__(self):
		if self.a <= 10:
			b = self.a
			self.a += 2
			return b

evenClass = EvenNumbers()
myIter = iter(evenClass)
print(next(myIter))
print(next(myIter))
print(next(myIter))
print(next(myIter))
# for x in myIter:
# 	print(x)
```
## Generator
It's like iterator, but with simpler code!(function instead of class)
```python
def even_numbers():
	a = 0
	while a <= 10:
		yield a # yield doesn't stop the the round
		a += 2

myGen = even_numbers()
print(next(myGen))
print(next(myGen))
print(next(myGen))
print(next(myGen))
# for x in myGen:
# 	print(x)
```
# Decorators
## Error Handler Decorator
```python
def error_handler(func):
    try:
        func()
    except Exception as e:
        print(e)

@error_handler
def division_by_zero():
    print(10/0)
```
## Run Time Decorator
```python
import time

def time_comparison(round_num):
	def decorator(func):
		def wrapper(*args, **kwargs):
			result = 0
			for i in range(round_num):
				start = time.time()*1000
				func(*args, **kwargs)
				result += time.time()*1000 - start # end - start
			result /= round_num
			print(f'Average time in {round_num} rounds: {result:.2f}')
		return wrapper
	return decorator
	
@time_comparison(round_num = 10)
def factorial(n):
    result = 1
    for i in range(n, 1, -1):
        result *= i 

factorial(10000)
```
For more info visit: [Decorators with parameters in Python - GeeksforGeeks](https://www.geeksforgeeks.org/decorators-with-parameters-in-python/)
# Metaclasses
create simple class with `type()`:
```python
class AnotherClass:
	def another_test(self):
		print('Testing...')
		
Test = type('Test', (AnotherClass,), {'a': 20}) # arguments: class name, parent, attributes
test = Test()
test.another_test()
print(test.a)
```
## Create metaclass
```python
class Meta(type):
	def __new__(self, class_name, bases, attrs):
		return type(class_name, bases, attrs)

class test(metaclass=Meta):
	pass
```
**Tip:** `__new__()` will be called even before `__init__()` method.
**Example:** We want to make a metaclass that have `all()` function and it will return all attributes of the class:
```python
class Collection(type):
	def __new__(self, class_name, bases, attrs):
		def all(self):
			return [name for name, values in attrs.items() if not name.startswith('__') and not callable(value)]
	attrs['all'] = all
	return type(class_name, bases, attrs)
	
class Data:
	score = 100
	is_admin = False
	name = 'rick'

d = Data()
print(d.all())
```
# Map, Filter and Reduce
## map()
```python
# map(func, *iterables)
li = ['1', '2', '3', '4', '5']
newLi = list(map(int, li))
print(neLi)
```
If your function takes more than one argument, you can pass it like this:
```python
def sum(a:int, b:int):
	return a + b
	
liOne = [1, 2, 3]
liTwo = [4, 5, 6]
result = list(map(sum, liOne, liTwo))
print(result)
[5, 7, 9]
```
### Zip function with Map
```python
li1 = ['a', 'b', 'c', 'd', 'e']
li2 = [1, 2, 3, 4, 5]

result = list(zip(li1, li2))
print(result)
```
->
```python
li1 = ['a', 'b', 'c', 'd', 'e']
li2 = [1, 2, 3, 4, 5]

result = list(map(lambda x, y: (x, y), li1, li2))
print(result)
```
And the result will be the same:
```
[('a', 1), ('b', 2), ('c', 3), ('d', 4), ('e', 5)]
```
## filter()
```python
li = [1, -1, 2, -2, 3, -3]
newLi = list(filter(lambda x: x >= 0, li))
print(newLi)
```
## reduce()
```python
# reduce(func, iterable[, initial])
from functools import reduce

numbers = [1, 2, 3, 4, 5]

result = reduce(lambda x, y: x+y, numbers)
print(result)
```
# Asynchronous and Parallel Programming
## Parallelism(CPU bound)
```python
import time
from multiprocessing import Pool

def increment(input):
    for i in range(1000000):
        input = input + 1

if __name__ == "__main__":
    inputs = [1] * 100
    pool = Pool(8)
    started = time.time()
    pool.map(increment, inputs)
    elapsed = time.time()
    print('Time taken:', elapsed - started)
    pool.close()
# Time taken MultiProcess : 1.6436049938201904
```
## Concurrency(I/O bound)
```python
from alpha_vantage.timeseries import TimeSeries 
import time 
import concurrent.futures

companies = ['MSFT', 'IBM', 'SHOP.TRT', 'GOOGL', 'GPV.TRV']

def get_stock_data(stock_name):
    ts = TimeSeries(key='###', output_format='pandas')
    data, meta_data = ts.get_daily(stock_name, outputsize='full')

started = time.time()
size = 5
with concurrent.futures.ThreadPoolExecutor(size) as thp:
    thp.map(get_stock_data, companies)
elapsed = time.time()

print('Time taken: :', elapsed-started)
# Time taken: : 0.8325850963592529
```
## AsyncIO(I/O bound)
```python
import random, time, asyncio

async def sleeper():
    sleepDuration = random.random()
    await asyncio.sleep(sleepDuration)
    print(sleepDuration)

async def test():
    start = time.time()
    await sleeper()
    await sleeper()
    await sleeper()
    end = time.time()
    print(f'Time: {end-start}')

asyncio.run(test())
```
### asyncio.gather
```python
import random, time, asyncio

async def sleeper():
    sleepDuration = random.random()
    await asyncio.sleep(sleepDuration)
    print(sleepDuration)

async def test():
    start = time.time()
    await asyncio.gather(
        sleeper(), 
        sleeper(), 
        sleeper(),
    )
    end = time.time()
    print(f'Time: {end-start}')

asyncio.run(test())
```
### asyncio.create_task
```python
import random, time, asyncio

async def sleeper():
    sleepDuration = random.random()
    await asyncio.sleep(sleepDuration)
    print(sleepDuration)

async def test():
    start = time.time()
    taskOne = asyncio.create_task(sleeper())
    taskTwo = asyncio.create_task(sleeper())
    taskThree = asyncio.create_task(sleeper())
    await taskOne
    await taskTwo
    await taskThree
    end = time.time()
    print(f'Time: {end-start}')

asyncio.run(test())
```
# Pytest
## Installation
```shell
pip install pytest
```
## Usage
Make files with the name test_\*.py(\* is your desired name) in your project folder and write your test using `assert`:
```python
def factorial(n: int):
    result = 1
    for i in range(1, n):
        result *= i
    return result
```
Run `python -m pytest` in terminal to see the result of all tests.
