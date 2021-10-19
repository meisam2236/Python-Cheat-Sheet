- [Data](#data)
	- [Arithmatic Operators](#arithmatic-operators)
	- [type](#type)
	- [int](#int)
	- [float](#float)
	- [complex](#complex)
	- [Casting](#casting)
	- [string](#string)
		- [multiple-line string](#multiple-line-string)
		- [string as array](#string-as-array)
		- [string slicing](#string-slicing)
		- [len()](#len)
		- [in-not in](#in-not-in)
		- [Concatenate](#concatenate)
		- [backslash](#backslash)
		- [Other commands](#other-commands)
	- [list](#list)
		- [Accessing items in list](#accessing-items-in-list)
		- [insert()](#insert)
		- [append()](#append)
		- [len()](#len-1)
		- [extend()](#extend)
		- [remove()](#remove)
		- [pop()](#pop)
		- [clear()](#clear)
		- [del](#del)
		- [constructor](#constructor)
		- [sort()](#sort)
		- [reverse()](#reverse)
		- [List copying](#list-copying)
	- [tuple](#tuple)
		- [del](#del-1)
		- [constructor](#constructor-1)
		- [unpack tuples](#unpack-tuples)
		- [tuple concat](#tuple-concat)
		- [tuple multiplication](#tuple-multiplication)
		- [count()](#count)
		- [index()](#index)
	- [range](#range)
	- [set](#set)
		- [len()](#len-2)
		- [constructor](#constructor-2)
		- [in](#in)
		- [add()](#add)
		- [remove()](#remove-1)
		- [update()](#update)
		- [discard()](#discard)
		- [pop()](#pop-1)
		- [clear()](#clear-1)
		- [del](#del-2)
		- [union()](#union)
		- [intersection_update()](#intersection_update)
		- [symmetric_difference()](#symmetric_difference)
	- [frozenset](#frozenset)
	- [dictionary](#dictionary)
		- [changing values](#changing-values)
		- [get item](#get-item)
		- [len()](#len-3)
		- [keys()](#keys)
		- [values()](#values)
		- [items()](#items)
		- [in](#in-1)
		- [update()](#update-1)
		- [Adding item](#adding-item)
		- [pop()](#pop-2)
		- [popitem()](#popitem)
		- [clear()](#clear-2)
		- [del](#del-3)
		- [Dictionary copying](#dictionary-copying)
		- [nested dictionaries](#nested-dictionaries)
		- [fromkeys](#fromkeys)
		- [setdefault](#setdefault)
	- [bool](#bool)
		- [Comparison Operators](#comparison-operators)
	- [Other types](#other-types)
- [Comments](#comments)
	- [One-line comment](#one-line-comment)
	- [Multiple-line comment](#multiple-line-comment)
- [If Statements](#if-statements)
	- [if](#if)
	- [elif(else if)](#elifelse-if)
	- [else](#else)
	- [shortened if statement](#shortened-if-statement)
	- [and](#and)
	- [or](#or)
	- [nested if](#nested-if)
	- [pass](#pass)
- [match-case](#match-case)
- [Loops](#loops)
	- [while loops](#while-loops)
		- [break](#break)
		- [continue](#continue)
		- [else](#else-1)
		- [while loop on sequential data](#while-loop-on-sequential-data)
	- [for loops](#for-loops)
		- [for loop on string](#for-loop-on-string)
		- [break](#break-1)
		- [continue](#continue-1)
		- [else](#else-2)
		- [range()](#range-1)
		- [nested loops](#nested-loops)
		- [pass](#pass-1)
		- [List comprehension](#list-comprehension)
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
- [Functions](#functions)
	- [Arguments](#arguments)
	- [Desired Arguments](#desired-arguments)
	- [Keyword Arguments](#keyword-arguments)
		- [Desired Keyword Arguments](#desired-keyword-arguments)
	- [Default Arguments](#default-arguments)
	- [return](#return)
	- [pass](#pass-2)
	- [lambda](#lambda)
	- [Recursive functions](#recursive-functions)
- [Classes](#classes)
	- [Constructor](#constructor-3)
	- [Changing object attrs](#changing-object-attrs)
	- [pass](#pass-3)
- [Object-Oriented Programming(OOP)](#object-oriented-programmingoop)
	- [Encapsulation](#encapsulation)
	- [Inheritance](#inheritance)
		- [Execute parent's init method](#execute-parents-init-method)
		- [Child's function](#childs-function)
	- [Composition](#composition)
	- [Abstraction](#abstraction)
	- [Polymorphism](#polymorphism)
- [Scope](#scope)
	- [Local Scope](#local-scope)
		- [Function inside Function](#function-inside-function)
	- [Global Scope](#global-scope)
		- [Naming variables](#naming-variables)
		- [global keyword](#global-keyword)
	- [nonlocal variable](#nonlocal-variable)
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
	- [else](#else-3)
	- [finally](#finally)
	- [Custom exception](#custom-exception)
	- [Representing exception](#representing-exception)
- [Magic Methods(Dunder Methods)](#magic-methodsdunder-methods)
	- [__init__()](#init)
	- [__repr__()](#repr)
	- [__add__()](#add-1)
	- [__len__()](#len-4)
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
# Data
```python
a = 20
b = 30 
print(a+b)
```
## Arithmatic Operators
|Operator|Name|
|---|:---:|
|+|Addition|
|-|Subtraction|
|\*|Multiplication|
|/|Division|
|%|Modulus|
|\*\*|Exponentiation|
|//|Floor division|
## type
```python
a = 45
print(type(a))
```
## int
```python
a = 32 
b = 123456789 
c = -43
```
## float
```python
a = 1.25 
b = 3.0 
c = -23.14567
```
## complex
```python
a = 2 + 3j 
b = 6j 
c = -2j
```
## Casting
```python
a = 32 
b = 12.25 
c = 3j  
x = float(a) 
y = int(b) 
z = complex(a)  
print(x) 
print(y) 
print(z)
```
## string
**Tip:** string is immutable.
```python
a = 'hello world!' 
b = "hello world!" 
print(a) 
print(b)
```
### multiple-line string
```python
a = '''Lorem ipsum dolor sit amet, 
consectetur adipiscing elit, 
sed do eiusmod tempor incididunt 
ut labore et dolore magna aliqua.''' 
b = """Lorem ipsum dolor sit amet, 
consectetur adipiscing elit, 
sed do eiusmod tempor incididunt 
ut labore et dolore magna aliqua.""" 
print(a) 
print(b)
```
### string as array
```python
a = 'hello' 
print(a[1])
```
### string slicing
```python
a = 'hello my friend!' 
print(a[0:5])
```
**Another example:**
```python
a = 'hello my friend!' 
b = a[:5] 
c = a[6:] 
d = a[:] 
e = a[-7:-1] 
print(a) 
print(b) 
print(c) 
print(d) 
print(e)
```
### len()
```python
a = 'test'
print(len(a))
```
### in-not in
```python
text = "This is a test text!." 
print('test' in text) 
print('not' not in text)
```
### Concatenate
```python
a = 'Hello' 
b = 'World!' 
c = a + ' ' + b 
print(c)
```
**Another example:**
```python
age = 25 
txt = "My name is Meisam and I'm {}" 
print(txt.format(age))
```
**Another example:**
```python
age = 25 
txt = f"My name is Meisam and I'm {age}" 
print(txt)
```
### backslash
```python
a = 'I\'m Meisam' 
print(a)
```
|character|function|
|---|:--:|
|\\|\|
|\n|new line|
|\t|tab|
|\b|backspace|
### Other commands
|Command|Action|
|---|:---:|
|`strip()`|remove white spaces before and after string|
|`replace()`|replace with another string|
|`lower()`|turn entire string to lowercase(Purely ASCII Text)|
|`upper()`|turn entire string to uppercase|
|`split()`|turn string to list with given character|
|`capitalize()`|Capitalize the string|
|`casefold()`|turn entire string to lowercase(Unicode text/user input)|
View full list commands: [3.6.1 String Methods (python.org)](https://docs.python.org/2.5/lib/string-methods.html)
## list
```python
myList = ['Ali', 'Hasan', 'Asqar'] 
print(myList)
```
Lists can handle multiple type variables:
```python
myList = ['Apple', 12, 3.5, True] 
print(myList)
```
### Accessing items in list
```python
li = ['apple', 'banana', 'cherry'] 
print(li[1])
```
**Another examples:**
```python
li = ['apple', 'orange', 'banana', 'grapes', 'kiwi', 'lemon'] 
print(li[2:4]) 
print('watermelon' in li) 
li[1] = 'watermelon' 
print(li) 
print('apple' in li)
```
### insert()
```python
li = ['apple', 'orange', 'banana', 'grapes', 'kiwi', 'lemon'] 
li.insert(2, 'watermelon') 
print(li)
```
### append()
```python
myList = ['apple', 'lemon', 'kiwi'] 
myList.append('watermelon') 
print(myList)
```
### len()
```python
myList = [1, 4, 65, 34, 23] 
print(len(myList))
```
### extend()
```python
li = ['mango', 'apple', 'cherry'] 
myList = ['watermelon', 'pineapple', 'lemon'] 
li.extend(myList) 
print(li)
```
### remove()
```python
myList = ['watermelon', 'pineapple', 'lemon'] 
myList.remove('lemon') 
print(myList) 
```
### pop()
```python
myList = ['watermelon', 'pineapple', 'lemon'] 
myList.pop(0) 
print(myList)
```
### clear()
```python
myList = ['watermelon', 'pineapple', 'lemon'] 
myList.clear() 
print(myList)
```
### del
```python
myList = ['watermelon', 'pineapple', 'lemon'] 
del myList
```
### constructor
```python
li = list()
myList = list((3, 5, 7))
print(li)
print(myList)
```
### sort()
```python
myList = ['brown', 'purple', 'green', 'yellow', 'blue'] 
myList.sort() 
print(myList) 
li = [ 43, 32, 191, 8, 26, 365] 
print(li.sort())
```
for descending sort, give argument `reverse=True`:
```python
myList = ['brown', 'purple', 'green', 'yellow', 'blue'] 
myList.sort(reverse = True) 
print(myList)
```
`sort()` is case sensetive. To cope that:
```python
li = ['Brown', 'purple', 'Yellow', 'pink', 'blue'] 
li.sort(key = str.lower) 
print(li)
```
### reverse()
```python 
myList = ['brown', 'purple', 'green', 'yellow', 'blue'] 
myList.reverse() 
print(myList)
```
### List copying
```python
li = [1, 2, 3, 4, 5] 
li2 = li
```
By doing the code above, li2 use li as a reference. A better way to copy is using `copy()`:
```python
li = [1, 2, 3, 4, 5]
li2 = li.copy()
```
Another approach will be:
```python
li = [1, 2, 3, 4, 5]
li2 = list(li)
```
## tuple
**Tip:** tuple is immutable.
```python
myTuple = ('apple', 'banana', 'orange') 
print(myTuple) 
tu = (1, 2, 3, 4) 
print(tu[0]) 
print(tu[0:2]) 
print(tu[-1]) 
tuple1 = ('Ali', 23, 1.78, True) 
print(len(tuple1))
```
Make sure to use , at the end of tuple or python interpreter recognize it as a string:
```python
tu = ('test',) 
print(type(tu)) 
tu = ('test') 
print(type(tu))
```
### del 
```python
thisTuple = (1, 3, 5, 7)
del thisTuple
```
### constructor
```python
myTuple = tuple(('apple', 'banana', 'lemon')) 
print(myTuple)
```
### unpack tuples
```python
colors = ('red', 'green', 'blue')
(love, nature, ocean) = colors
print(love)
print(nature)
print(ocean)
```
You can even have list in tuple and unpack it:
```python
tu = ([1, 2, 3], [4, 5, 6])
(li1, li2) = tu
print(li1)
```
You can use astrix(\*) to get all items:
```python
tu = ('red', 'green', 'blue', 'black', 'purple', 'yellow') 
(love, *colors, sun) = tu
print(love) 
print(colors) 
print(sun)
```
### tuple concat
```python
tu1 = ('apple', 'banana', 'orange') 
tu2 = ('kiwi', 'lemon', 'grapes') 
tu3 = tu1 + tu2 
print(tu3)
```
### tuple multiplication
```python
tu1 = ('apple', 'banana', 'orange') 
tu2 = tu1 * 2 
print(tu2)
```
### count()
```python
tu1 = ('apple', 'banana', 'orange', 'apple') 
print(tu1.count('apple'))
```
### index()
```python
tu1 = ('apple', 'banana', 'orange', 'apple') 
print(tu1.index('banana')) 
```
## range
```python
x = range(1, 20, 2) # arguments: start, stop, step
print(x)
```
## set
Items in set doesn't have order; Thus it doesn't need index and items are unique! We use for loop to access items in set.
```python
mySet = {'apple', 'banana', 'orange'} 
print(mySet)
```
### len()
```python
mySet = {'apple', 'banana', 'orange'} 
print(len(mySet))
```
### constructor
```python
mySet = set(('apple', 'orange', 'banana')) 
print(mySet)
```
### in
```python
mySet = {'apple', 'orange', 'banana'} 
print('orange' in mySet)
```
### add()
```python
mySet = {'apple', 'orange', 'banana'} 
mySet.add('lemon') 
print(mySet) 
```
### remove()
```python
mySet = {'apple', 'orange', 'banana'} 
mySet.remove('apple') 
print(mySet)
```
### update()
We can combine set with another set or list using `update()`:
```python
set1 = {'apple', 'orange', 'banana'} 
set2 = ['kiwi', 'watermelon', 'lemon']
set1.update(set2) 
print(set1)
```
### discard()
`discard()` is a safe `remove()` method(If item doesn't exist, it will not encounter error):
```python
mySet = {'apple', 'orange', 'banana'} 
mySet.discard('lemon') 
print(mySet)
```
### pop()
```python
mySet = {'apple', 'orange', 'banana'} 
mySet.pop() 
print(mySet)
```
### clear()
```python
mySet = {'apple', 'orange', 'banana'} 
clear(mySet)
print(mySet)
```
### del
```python
mySet = {'apple', 'orange', 'banana'} 
del mySet
```
### union()
create another set containing two sets:
```python
set1 = {'apple', 'orange', 'banana'} 
set2 = {'kiwi', 'watermelon', 'lemon'} 
set3 = set1.union(set2)
print(set3)
```
### intersection_update()
```python
set1 = {'apple', 'orange', 'banana'} 
set2 = {'apple', 'watermelon', 'lemon'} 
set3 = set1.intersection_update(set2) 
print(set3)
```
### symmetric_difference()
```python
set1 = {'apple', 'orange', 'banana'} 
set2 = {'apple', 'watermelon', 'lemon'} 
set3 = set1.symmetric_difference(set2) 
print(set3)
```
## frozenset
immutable set!
```python
myList = ['apple', 'banana', 'orange'] 
fset = frozenset(myList)
```
## dictionary
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
print(myDict)
```
### changing values
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
myDict['name'] = 'Hasan' 
print(myDict)
```
### get item
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
print(myDict['age']) 
name = myDict.get('name') 
print(name)
```
### len()
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
print(len(myDict))
```
### keys()
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
keys = myDict.keys() 
print(keys)
```
`keys()` uses the dictionary itself as a reference. So if anything changes in the dictionary, `keys()` will be updated too:
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
keys = myDict.keys() 
print(keys) 
myDict['weight'] = 70 
print(keys)
```
### values()
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
values = myDict.values() 
print(values)
```
Same as `keys()`, `values()` uses the dictionary as a reference.
### items()
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
items = myDict.items() 
print(items)
```
### in
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
print('weight' in myDict)
```
### update()
If the key doesn't exist in the dictionary, it will create one:
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
myDict.update({'weight': 73}) 
print(myDict)
```
### Adding item
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
myDict['weight'] = 80 
print(myDict) 
```
### pop()
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
myDict.pop('age') 
print(myDict)
```
### popitem()
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
myDict.popitem() 
print(myDict)
```
### clear()
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
myDict.clear() 
print(myDict)
```
### del
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
del myDict
```
In dictionary, with `del` you can also delete an item:
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
del myDict['age'] 
print(myDict)
```
### Dictionary copying
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
myDict2 = myDict
```
By doing the code above, myDict2 use myDict as a reference. A better way to copy is using `copy()`:
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
myDict2 = myDict.copy()
```
Another approach will be:
```python
myDict = {'name': 'Ali', 'age': 25, 'height': 1.73} 
myDict2 = dict(myDict)
```
### nested dictionaries
```python
myDict = {
	'child1':{
		'name': 'Ali',
		'age': 25,
		'height': 1.73
	},
	'child2':{
		'name': 'Hasan',
		'age': 32,
		'height': 1.80
	}
}
```
### fromkeys
Returns a dictionary with the specified keys and the specified value.
```python
keys = ('key1', 'key2', 'key3')
value = 0
myDict = dict.fromkeys(keys, value)
print(myDict)
```
### setdefault
If the key exist, it has no effect. But if the key does not exist, the value given will become the key's value:
```python
car = {  
 "brand": "Ford",  
 "model": "Mustang",  
 "year": 1964  
}  
  
x = car.setdefault("color", "white")  
  
print(x)
print(car)
```
## bool
```python
print(10 < 12) 
print(10 >= 10) 
a = 20 < 12 
print(a)
```
You can also check variables with bool:
```python
print(bool('Hello')) 
print(bool(0))
```
### Comparison Operators
|Operator|Name|
|---|:---:|
|\==|Equal|
|!=|Not equal|
|>|Greater than|
|<|Less than|
|>=|Greater than or equal to|
|<=|Less than or equal to|
## Other types
- byte array
- bytes
- memoryview
- arrays
# Comments
## One-line comment
```python
# This is a comment
print('hello')
# This is another comment
```
## Multiple-line comment
```python
'''This is a comment
This is another comment'''
print('hello')
```
# If Statements
## if
```python
a = 200
b = 100
if a > b:
	print(f'{a} is greater than {b}')
```
## elif(else if)
```python
a = 100 b = 200
if a > b:
	print('a is greater than b')
elif a < b:
	print('b is greater than a')
```
## else
```python
a = 100 b = 200
if a > b:
	print('a is greater than b')
elif a==b:
	print('a is equal to b')
else:
	print('b is greater than a')
```
## shortened if statement
```python
a = 200
b = 100
if a > b: print('a is greater than b')
```
**Another example:**
```python
a = 100
b = 200
print('a is greater than b') if a > b else print('a is equal to b') if a == b else print('b is greater than a')
```
## and
```python
a = 200
b = 100
c = 50

if a > b and b > c:
	print('a is greater than c')
```
## or
```python
a = 100
b = 200
c = 50

if a > c or b > c:
	print('a or b is greater than c')
```
## nested if
```python
x = 20
if x > 10:
	print('x is above 10')
	if x > 20:
		print('x is above 20')
		if x > 30:
			print('x is above 30')
		else:
			print('x is equal or below 30')
	else:
		print('x is equal or below 20')
else:
	print('x is equal or below 10')
```
## pass
```python
if 20 > 10:
	pass
```
# match-case
In python v3.10, you can do match-case instead of if, else thing:
```python
def converted_day_of_week(dayOfWeek: str):
	match dayOfWeek.lower():
		case 'saturday':
			return 'شنبه'
		case 'sunday':
			return 'یکشنبه'
		case 'monday':
			return 'دوشنبه'
		case 'tuesday':
			return 'سه شنبه'
		case 'wednesday':
			return 'چهار شنبه'
		case 'thursday':
			return 'پنج شنبه'
		case 'friday':
			return 'جمعه'
		case _:
			return 'not found!'

print(converted_day_of_week('Sunday'))
```
# Loops
## while loops
```python
x = 1
while x < 10:
	print(x)
	x += 1
```
### break
```python
i = 1
while i < 10:
	print(i)
	if i == 5:
		break
	i += 1
# output: 1 2 3 4 5
```
### continue
```python
i = 0
while i < 10:
	if i == 5:
		continue
	print(i)
	i += 1
# output: 0 1 2 3 4 6 7 8 9
```
### else
```python
i = 1
while i < 10:
	print(i)
	i += 1
else:
	print('Loop ended!')
```
### while loop on sequential data
```python
li = [1, 2, 3, 4, 5]
i = 0

while i < len(li):
	print(li[i])
	i += 1
```
## for loops
```python
fruits = ['apple', 'orange', 'banana']
for x in fruits:
	print(x)
```
### for loop on string
```python
for x in 'apple':
	print(x)
```
### break
```python
for i in 'test':
	print(i)
	if i == 'e':
		break
# output: t e
```
### continue
```python
for i in 'test':
	if i == s:
		continue
	print(i)
# output: t e t
```
### else
```python
for i in 'test':
	print(i)
else:
	print('Loop ended!')
```
### range()
```python
for x in range(0, 6, 2): # arguments: start, stop, step
	print(x)
# output: 0, 2, 4
```
### nested loops
```python
li = [[1, 2, 3], [4, 5, 6], [7, 8, 9]] 
for i in range(len(li)): 
    for j in range(len(li[i])): 
        print(li[i][j])
```
### pass
```python
for x in [1, 2, 3]:
	pass
```
### List comprehension
```python
li = [for x in range(10)]
print(li)
```
**Another example:**
```python
fruits = ['apple', 'banana', 'orange', 'kiwi', 'lemon'] 
li = [x for x in fruits if 'a' in x] 
print(li)
```
**Another example:**
```python
fruits = ['apple', 'banana', 'orange', 'kiwi', 'lemon'] 
li = [x for x in fruits if 'a' in x] 
print(li)
```
**Another example:**
```python
fruits = ['apple', 'banana', 'lemon'] 
li = [x if x != 'banana' else 'orange' for x in fruits] 
print(li)
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
# Functions
```python
def my_func():
	print('hello world!')
	
my_func()
my_func()
```
## Arguments
```python
def multiply(num1:int, num2:int):
	print(num1 * num2)


multiply(7, 9)
multiply(3, 2)
multiply('a', 'b')
```
## Desired Arguments
```python
def classmates_names(*names):
	length = len(names)
	if length>0:
		for i in range(length):
			print(names[i])
	else:
		print('Undefined!')

classmates_names('Ali', 'Sadra', 'Mohsen')
```
## Keyword Arguments
```python
def my_func(name1, name2):
    print(f'Names: {name1} - {name2}')
my_func(name2 = 'Reza', name1 = 'Asqar')
```
### Desired Keyword Arguments
```python
def classmates_names(**names):
    print(names['name1'])
    print(names['name2'])
    print(names['name3'])

classmates_names(name1 = 'Ali', name2 = 'Sadra', name3 = 'Mohsen')
```
## Default Arguments
```python
def my_func(num1=1, num2=1):
    print(f'num1 + num2 = {num1+num2}')

my_func()
```
## return
```python
def my_func(num1, num2):
    return num1 + num2

print(my_func(3, 5))
x = my_func(10, 12)
print(x)
```
## pass
```python
def my_func():
    pass

my_func()
```
## lambda
```python
my_func = lambda a, b : a + b
print(my_func(3, 4))
```
**Another example:**
```python
def my_func(n):
    return lambda a : a + n

my_adder = my_func(2)
print(my_adder(10))
```
## Recursive functions
```python
def is_prime(n, div = None):
    if div is None:
        div = n - 1
    while div >= 2:
        if n % div == 0:
            print(f"{n} is not prime!")
            break
        else:
            return is_prime(n, div-1)
    else:
        print(f"{n} is prime!")

is_prime(4)
is_prime(3)
```
# Classes
```python
class MyClass:
	a = 10

objOne = MyClass()
print(objOne.a)
```
## Constructor
```python
class Person:
	def __init__(self, name: str, age: int): # constructor
		self.name = name
		self.age = age
	def call(self):
		print(f"My name is {self.name} and I'm {self.age}")

objOne = Person('Ali', 23)
objOne.call()
```
## Changing object attrs
```python
class Person:
	def __init__(self):
		self.name = 'Ali'
		self.age = 23
	def call(self):
		print(f"My name is {self.name} and I'm {self.age}")

objOne = Person()
objOne.name = 'Mohsen'
objOne.call()
del objOne.age
```
## pass
```python
class Test():
	pass
```
# Object-Oriented Programming(OOP)
## Encapsulation
```python
class MyClass:
	def __init__(self):
		self.__a = 2 # private variable
	def __test(self): # private function
		return self.__a *2
	def output(self): # public function
		print(self.__test())
		
objOne = MyClass()
objOne.output()
```
## Inheritance
```python
class Person:
	def __init__(self, name: str, age: int):
		self.name = name
		self.age = age
	def print(self):
		print(f'My name is {self.name} and I am {self.age}')
	
class MyClass(Person):
	pass

objOne = MyClass('Ali', 23)
objOne.print()
```
### Execute parent's init method
If you have `__init__()` inside child's class, the `__init__()` in parent class won't be executed. But there is a way to execute it:
```python
class Person:
	def __init__(self, name: str, age: int):
		self.name = name
		self.age = age
	def print(self):
		print(f'My name is {self.name} and I am {self.age}')
	
class MyClass(Person):
	def __init__(self, name, age):
		Person.__init__(self, name, age)

objOne = MyClass('Ali', 23)
objOne.print()
```
You can also use `super()` to inherite all methods of the parent. same result:
```python
class Person:
	def __init__(self, name: str, age: int):
		self.name = name
		self.age = age
	def print(self):
		print(f'My name is {self.name} and I am {self.age}')
	
class MyClass(Person):
	def __init__(self, name, age):
		super().__init__(name, age)

objOne = MyClass('Ali', 23)
objOne.print()
```
### Child's function
```python
class Person:
	def __init__(self, name: str, age: int):
		self.name = name
		self.age = age
	def print(self):
		print(f'My name is {self.name} and I am {self.age}')
	
class MyClass(Person):
	def __init__(self, name, age, height: int):
		super().__init__(name, age)
		self.height = height
	def new_print(self):
		print('My height is {self.height}')

objOne = MyClass('Ali', 23, 180)
objOne.print()
objOne.new_print()
```
## Composition
Composition is like inheriance but has some major differences. We use it when we don't want to change the parent class(since class encapsulate things...). 
```python
class Component:
	def __init__(self):
		print('Component class object is created...')
	def component_test(self):
		print('Component class component_test method executed...')

class Coposite:
	def __init__(self):
		self.objOne = Component()
	def composite_test(self):
		print('Composite class composite_test method executed...')
		self.objOne.component_test()
		
objTwo = Composite()
objTwo.composite_test()
```
## Abstraction
```python
from abc import ABC, abstractmethod

class MyClass(ABC): # abstract class
	def return_val(self, x):
		print(f'Value is {x}')
	@abstractmethod
	def test(self): # abstract function
		pass
	
class TestClass(MyClass):
	def test(self):
		print('Tets string from TestClass!')

class AnotherTestClass(MyClass):
	def test(self):
		print('Another test string from AnotherTestClass!')
	
objOne = TestClass()
objOne.test()
objOne.return_val(20)
objTwo = AnotherTestClass()
objTwo.test()
```
## Polymorphism
`len()` is a good polymorphism example. Another example is the function that has default values:
```python
def multiply(a:int=0, b:int=0):
	return a*b
print(multiply(3))
print(multiply())
print(multiply(2, 3))
```
Another example:
```python
class India(): 
    def capital(self): 
        print("New Delhi is the capital of India.") 
  
    def language(self): 
        print("Hindi is the most widely spoken language of India.") 
  
    def type(self): 
        print("India is a developing country.") 
  
class USA(): 
    def capital(self): 
        print("Washington, D.C. is the capital of USA.") 
  
    def language(self): 
        print("English is the primary language of USA.") 
  
    def type(self): 
        print("USA is a developed country.") 
  
obj_ind = India() 
obj_usa = USA() 
for country in (obj_ind, obj_usa): 
    country.capital() 
    country.language() 
    country.type() 
```
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
