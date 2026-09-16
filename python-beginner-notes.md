# 🐍 Python Beginner Notes

A complete beginner-friendly guide to learning Python with explanations, examples, cheat sheets, and practice projects.

---

## 📚 Table of Contents

1. [What is Python?](#1-what-is-python)
2. [Installing Python](#2-installing-python)
3. [Hello World](#3-hello-world)
4. [Comments](#4-comments)
5. [Variables](#5-variables)
6. [Data Types](#6-data-types)
7. [Type Conversion](#7-type-conversion)
8. [Strings](#8-strings)
9. [String Methods](#9-string-methods)
10. [Operators](#10-operators)
11. [Input and Output](#11-input-and-output)
12. [Conditional Statements](#12-conditional-statements)
13. [Loops](#13-loops)
14. [Lists](#14-lists)
15. [Tuples](#15-tuples)
16. [Sets](#16-sets)
17. [Dictionaries](#17-dictionaries)
18. [List Comprehension](#18-list-comprehension)
19. [Functions](#19-functions)
20. [Lambda Functions](#20-lambda-functions)
21. [Modules](#21-modules)
22. [Exception Handling](#22-exception-handling)
23. [File Handling](#23-file-handling)
24. [Object-Oriented Programming](#24-object-oriented-programming)
25. [Inheritance](#25-inheritance)
26. [Iterators](#26-iterators)
27. [Generators](#27-generators)
28. [Decorators](#28-decorators)
29. [JSON](#29-json)
30. [Virtual Environment](#30-virtual-environment)
31. [Useful Built-in Functions](#31-useful-built-in-functions)
32. [Practice Projects](#32-practice-projects)
33. [Python Cheat Sheet](#33-python-cheat-sheet)
34. [Learning Roadmap](#34-learning-roadmap)

---

# 1. What is Python?

Python is a high-level, interpreted, general-purpose programming language.

Python is popular because:

* It has simple and readable syntax.
* It is beginner-friendly.
* It is open source.
* It has a large community.
* It has many libraries and frameworks.
* It is used in Web Development, Data Science, AI/ML, Automation, Cybersecurity, and more.

### Example

```python
print("Hello, World!")
```

Output:

```text
Hello, World!
```

---

# 2. Installing Python

Download Python from:

https://www.python.org/

Check Python version:

```bash
python --version
```

or:

```bash
python3 --version
```

---

# 3. Hello World

The `print()` function is used to display output.

```python
print("Hello, World!")
print("Welcome to Python")
```

Output:

```text
Hello, World!
Welcome to Python
```

---

# 4. Comments

Comments are used to explain code.

Python ignores comments while executing the program.

### Single-line comment

```python
# This is a comment

print("Hello")
```

### Multi-line documentation

```python
"""
This is a multi-line
documentation string.
"""
```

---

# 5. Variables

Variables are used to store data.

```python
name = "John"
age = 25
salary = 25000.50
```

Print variables:

```python
print(name)
print(age)
print(salary)
```

### Variable Naming Rules

Valid:

```python
name = "John"
age1 = 20
student_name = "Alex"
```

Invalid:

```python
# 1name = "John"
# student-name = "Alex"
```

Python is case-sensitive:

```python
name = "John"
Name = "Alex"
```

`name` and `Name` are different variables.

---

# 6. Data Types

Python has several built-in data types.

| Type       | Example            |
| ---------- | ------------------ |
| `int`      | `10`               |
| `float`    | `10.5`             |
| `complex`  | `2 + 3j`           |
| `str`      | `"Hello"`          |
| `bool`     | `True`             |
| `list`     | `[1, 2, 3]`        |
| `tuple`    | `(1, 2, 3)`        |
| `set`      | `{1, 2, 3}`        |
| `dict`     | `{"name": "John"}` |
| `NoneType` | `None`             |

Check data type:

```python
x = 10

print(type(x))
```

Output:

```text
<class 'int'>
```

---

# 7. Type Conversion

Type conversion means changing one data type into another.

### String to Integer

```python
age = "25"

age = int(age)

print(age)
```

### Integer to String

```python
age = 25

age = str(age)

print(age)
```

### Float

```python
price = "99.99"

price = float(price)

print(price)
```

Common conversion functions:

```python
int()
float()
str()
bool()
list()
tuple()
set()
```

---

# 8. Strings

A string is a sequence of characters.

```python
name = "Python"
```

Single quotes:

```python
name = 'Python'
```

Double quotes:

```python
name = "Python"
```

### String Indexing

```python
word = "Python"

print(word[0])
print(word[1])
```

Output:

```text
P
y
```

Python indexing starts from `0`.

### Negative Indexing

```python
word = "Python"

print(word[-1])
```

Output:

```text
n
```

### String Slicing

```python
word = "Python"

print(word[0:3])
```

Output:

```text
Pyt
```

More examples:

```python
print(word[:3])
print(word[2:])
print(word[::-1])
```

---

# 9. String Methods

```python
text = "hello python"
```

### Uppercase

```python
print(text.upper())
```

### Lowercase

```python
print(text.lower())
```

### Capitalize

```python
print(text.capitalize())
```

### Replace

```python
print(text.replace("python", "world"))
```

### Split

```python
text = "apple,banana,mango"

print(text.split(","))
```

### Remove Extra Spaces

```python
text = "   hello   "

print(text.strip())
```

### Length

```python
text = "Python"

print(len(text))
```

---

# 10. Operators

## Arithmetic Operators

```python
a = 10
b = 3
```

| Operator | Meaning        | Example  |
| -------- | -------------- | -------- |
| `+`      | Addition       | `a + b`  |
| `-`      | Subtraction    | `a - b`  |
| `*`      | Multiplication | `a * b`  |
| `/`      | Division       | `a / b`  |
| `//`     | Floor Division | `a // b` |
| `%`      | Modulus        | `a % b`  |
| `**`     | Power          | `a ** b` |

Example:

```python
print(10 + 3)
print(10 - 3)
print(10 * 3)
print(10 / 3)
print(10 // 3)
print(10 % 3)
print(10 ** 3)
```

## Comparison Operators

```python
a = 10
b = 20

print(a == b)
print(a != b)
print(a > b)
print(a < b)
print(a >= b)
print(a <= b)
```

Comparison operators return:

```text
True
False
```

## Logical Operators

### and

```python
age = 25

print(age > 18 and age < 60)
```

### or

```python
age = 15

print(age < 18 or age > 60)
```

### not

```python
is_student = True

print(not is_student)
```

## Assignment Operators

```python
x = 10

x += 5
x -= 2
x *= 3
x /= 2
```

---

# 11. Input and Output

Use `input()` to take input from the user.

```python
name = input("Enter your name: ")

print("Hello", name)
```

Using f-string:

```python
name = input("Enter your name: ")

print(f"Hello, {name}!")
```

### Taking Integer Input

```python
age = int(input("Enter your age: "))

print(age)
```

### Taking Float Input

```python
price = float(input("Enter price: "))

print(price)
```

---

# 12. Conditional Statements

Conditional statements are used to make decisions.

## if

```python
age = 20

if age >= 18:
    print("Adult")
```

## if-else

```python
age = 16

if age >= 18:
    print("Adult")
else:
    print("Minor")
```

## if-elif-else

```python
marks = 75

if marks >= 90:
    print("A")

elif marks >= 75:
    print("B")

elif marks >= 60:
    print("C")

else:
    print("Fail")
```

---

# 13. Loops

Loops are used to repeat code.

## For Loop

```python
for i in range(5):
    print(i)
```

Output:

```text
0
1
2
3
4
```

### Loop through a list

```python
names = ["John", "Alex", "Sam"]

for name in names:
    print(name)
```

## While Loop

```python
count = 1

while count <= 5:
    print(count)
    count += 1
```

## Break

`break` stops the loop.

```python
for i in range(10):

    if i == 5:
        break

    print(i)
```

## Continue

`continue` skips the current iteration.

```python
for i in range(5):

    if i == 2:
        continue

    print(i)
```

## Pass

`pass` is used as a placeholder.

```python
def my_function():
    pass
```

---

# 14. Lists

A list stores multiple values.

```python
fruits = ["apple", "banana", "mango"]
```

Lists are:

* Ordered
* Mutable
* Allow duplicate values

Access elements:

```python
print(fruits[0])
```

Change an element:

```python
fruits[0] = "orange"
```

### List Methods

Add:

```python
fruits.append("grapes")
```

Insert:

```python
fruits.insert(1, "orange")
```

Remove:

```python
fruits.remove("orange")
```

Remove last item:

```python
fruits.pop()
```

Sort:

```python
fruits.sort()
```

Reverse:

```python
fruits.reverse()
```

Length:

```python
print(len(fruits))
```

---

# 15. Tuples

A tuple is ordered and immutable.

```python
numbers = (10, 20, 30)
```

Access:

```python
print(numbers[0])
```

Tuples cannot normally be changed after creation.

```python
# numbers[0] = 100
```

---

# 16. Sets

A set stores unique values.

```python
numbers = {1, 2, 3, 3, 4}

print(numbers)
```

Duplicate values are removed.

Add:

```python
numbers.add(5)
```

Remove:

```python
numbers.remove(2)
```

---

# 17. Dictionaries

A dictionary stores data as key-value pairs.

```python
student = {
    "name": "John",
    "age": 20,
    "course": "Python"
}
```

Access a value:

```python
print(student["name"])
```

Update:

```python
student["age"] = 21
```

Add:

```python
student["city"] = "Chennai"
```

Get:

```python
print(student.get("name"))
```

Keys:

```python
print(student.keys())
```

Values:

```python
print(student.values())
```

Items:

```python
print(student.items())
```

Loop through dictionary:

```python
for key, value in student.items():
    print(key, value)
```

---

# 18. List Comprehension

List comprehension provides a short way to create lists.

Normal approach:

```python
numbers = []

for i in range(5):
    numbers.append(i * 2)
```

List comprehension:

```python
numbers = [i * 2 for i in range(5)]
```

### With condition

```python
even_numbers = [
    i for i in range(10)
    if i % 2 == 0
]

print(even_numbers)
```

---

# 19. Functions

Functions are reusable blocks of code.

```python
def greet():
    print("Hello!")
```

Call the function:

```python
greet()
```

## Function Parameters

```python
def greet(name):
    print(f"Hello, {name}!")

greet("John")
```

## Multiple Parameters

```python
def add(a, b):
    print(a + b)

add(10, 20)
```

## Return

```python
def add(a, b):
    return a + b

result = add(10, 20)

print(result)
```

## Default Arguments

```python
def greet(name="Guest"):
    print(f"Hello, {name}")

greet()
greet("John")
```

## `*args`

```python
def add(*numbers):
    return sum(numbers)

print(add(1, 2, 3, 4))
```

## `**kwargs`

```python
def display(**details):
    print(details)

display(name="John", age=25)
```

---

# 20. Lambda Functions

A lambda is a small anonymous function.

```python
square = lambda x: x * x

print(square(5))
```

Output:

```text
25
```

Another example:

```python
add = lambda a, b: a + b

print(add(10, 20))
```

---

# 21. Modules

A module is a Python file containing reusable code.

Example:

```python
import math

print(math.sqrt(25))
```

Import a specific function:

```python
from math import sqrt

print(sqrt(25))
```

---

# 22. Exception Handling

Exceptions are errors that occur during program execution.

Use `try` and `except` to handle them.

```python
try:
    number = int(input("Enter a number: "))
    print(number)

except ValueError:
    print("Please enter a valid number.")
```

## finally

```python
try:
    print("Hello")

except Exception:
    print("Error")

finally:
    print("Program finished")
```

## Raising an Exception

```python
age = -1

if age < 0:
    raise ValueError("Age cannot be negative")
```

---

# 23. File Handling

## Reading a File

```python
with open("data.txt", "r") as file:
    content = file.read()

print(content)
```

## Writing a File

```python
with open("data.txt", "w") as file:
    file.write("Hello Python!")
```

## Appending

```python
with open("data.txt", "a") as file:
    file.write("\nNew line")
```

### File Modes

| Mode | Meaning |
| ---- | ------- |
| `r`  | Read    |
| `w`  | Write   |
| `a`  | Append  |
| `x`  | Create  |
| `b`  | Binary  |

---

# 24. Object-Oriented Programming

Python supports Object-Oriented Programming (OOP).

Important concepts:

* Class
* Object
* Constructor
* Attributes
* Methods
* Inheritance
* Encapsulation
* Polymorphism

## Class and Object

```python
class Student:

    def __init__(self, name, age):
        self.name = name
        self.age = age


student1 = Student("John", 20)

print(student1.name)
print(student1.age)
```

`Student` is a class.

`student1` is an object.

---

# 25. Methods

Methods are functions defined inside a class.

```python
class Student:

    def __init__(self, name):
        self.name = name

    def greet(self):
        print(f"Hello, I am {self.name}")


student = Student("John")

student.greet()
```

---

# 26. Inheritance

Inheritance allows a class to reuse functionality from another class.

```python
class Animal:

    def speak(self):
        print("Animal makes a sound")


class Dog(Animal):
    pass


dog = Dog()

dog.speak()
```

---

# 27. Polymorphism

Different classes can have the same method name with different behavior.

```python
class Dog:

    def sound(self):
        print("Bark")


class Cat:

    def sound(self):
        print("Meow")


animals = [Dog(), Cat()]

for animal in animals:
    animal.sound()
```

---

# 28. Encapsulation

Python uses naming conventions to indicate internal attributes.

```python
class Student:

    def __init__(self):
        self.__name = "John"
```

The double underscore triggers name mangling.

---

# 29. Iterators

An iterator allows values to be accessed one at a time.

```python
numbers = [1, 2, 3]

iterator = iter(numbers)

print(next(iterator))
print(next(iterator))
print(next(iterator))
```

Output:

```text
1
2
3
```

---

# 30. Generators

Generators use `yield` to produce values one at a time.

```python
def numbers():

    yield 1
    yield 2
    yield 3


for number in numbers():
    print(number)
```

Generators are useful when working with large amounts of data because values can be produced lazily.

---

# 31. Decorators

A decorator modifies or extends the behavior of a function.

```python
def decorator(func):

    def wrapper():
        print("Before function")

        func()

        print("After function")

    return wrapper


@decorator
def hello():
    print("Hello")


hello()
```

---

# 32. JSON

Python provides a built-in `json` module.

Convert Python object to JSON:

```python
import json

data = {
    "name": "John",
    "age": 25
}

json_data = json.dumps(data)

print(json_data)
```

Convert JSON to Python:

```python
data = json.loads(json_data)

print(data["name"])
```

---

# 33. Virtual Environment

Virtual environments isolate project dependencies.

Create a virtual environment:

```bash
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

### Linux/macOS

```bash
source venv/bin/activate
```

Install a package:

```bash
pip install requests
```

Save dependencies:

```bash
pip freeze > requirements.txt
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# 34. Useful Built-in Functions

Important Python built-in functions:

```python
print()
input()
len()
type()
range()
sum()
min()
max()
sorted()
abs()
round()
```

Example:

```python
numbers = [10, 20, 5, 40]

print(len(numbers))
print(sum(numbers))
print(min(numbers))
print(max(numbers))
print(sorted(numbers))
```

---

# 35. `enumerate()`

`enumerate()` gives both the index and value.

```python
names = ["John", "Alex", "Sam"]

for index, name in enumerate(names):
    print(index, name)
```

Output:

```text
0 John
1 Alex
2 Sam
```

---

# 36. `zip()`

`zip()` combines multiple iterables.

```python
names = ["John", "Alex", "Sam"]
ages = [20, 25, 22]

for name, age in zip(names, ages):
    print(name, age)
```

---

# 37. `map()`

`map()` applies a function to every item.

```python
numbers = [1, 2, 3, 4]

squares = list(
    map(lambda x: x * x, numbers)
)

print(squares)
```

---

# 38. `filter()`

`filter()` selects values based on a condition.

```python
numbers = [1, 2, 3, 4, 5, 6]

even_numbers = list(
    filter(lambda x: x % 2 == 0, numbers)
)

print(even_numbers)
```

---

# 39. `any()` and `all()`

## any()

Returns `True` if at least one value is true.

```python
values = [False, False, True]

print(any(values))
```

## all()

Returns `True` if all values are true.

```python
values = [True, True, True]

print(all(values))
```

---

# 40. `__name__ == "__main__"`

A common Python pattern:

```python
def main():
    print("Program started")


if __name__ == "__main__":
    main()
```

This is commonly used to make code run only when the file is executed directly.

---

# 41. Basic Testing

Python provides the `unittest` module.

```python
import unittest


def add(a, b):
    return a + b


class TestAdd(unittest.TestCase):

    def test_add(self):
        self.assertEqual(add(2, 3), 5)


if __name__ == "__main__":
    unittest.main()
```

---

# 42. Simple Calculator Project

```python
num1 = float(input("Enter first number: "))

operator = input(
    "Enter operator (+, -, *, /): "
)

num2 = float(input("Enter second number: "))


if operator == "+":
    result = num1 + num2

elif operator == "-":
    result = num1 - num2

elif operator == "*":
    result = num1 * num2

elif operator == "/":

    if num2 == 0:
        result = "Cannot divide by zero"
    else:
        result = num1 / num2

else:
    result = "Invalid operator"


print("Result:", result)
```

---

# 43. Number Guessing Game

```python
import random

number = random.randint(1, 100)

while True:

    guess = int(input("Guess the number: "))

    if guess < number:
        print("Too low")

    elif guess > number:
        print("Too high")

    else:
        print("Correct!")
        break
```

---

# 44. Beginner Practice Questions

Try solving these without looking at the solution.

### Easy

1. Print `"Hello World"`.
2. Add two numbers.
3. Find the largest of two numbers.
4. Find the largest of three numbers.
5. Check whether a number is even or odd.
6. Check whether a number is positive or negative.
7. Find the square of a number.
8. Calculate the area of a circle.
9. Convert Celsius to Fahrenheit.
10. Calculate simple interest.

### Loops

11. Print numbers from 1 to 100.
12. Print even numbers from 1 to 100.
13. Print odd numbers from 1 to 100.
14. Print a multiplication table.
15. Find the sum of numbers from 1 to N.
16. Find the factorial of a number.
17. Reverse a number.
18. Check whether a number is prime.
19. Print Fibonacci numbers.
20. Check whether a number is a palindrome.

### Strings

21. Reverse a string.
22. Count characters in a string.
23. Count vowels.
24. Check whether a string is a palindrome.
25. Count words in a sentence.

### Lists

26. Find the largest element in a list.
27. Find the smallest element.
28. Find the sum of list elements.
29. Remove duplicates.
30. Sort a list.
31. Find common elements between two lists.

---

# 45. Beginner Projects

Build projects after learning the basics.

## Project 1: Calculator

Topics:

* Variables
* Input
* Conditions
* Operators
* Functions

## Project 2: Number Guessing Game

Topics:

* Loops
* Conditions
* Random module
* User input

## Project 3: To-Do List

Topics:

* Lists
* Functions
* Loops
* File handling

## Project 4: Quiz Application

Topics:

* Dictionaries
* Lists
* Conditions
* Loops

## Project 5: Expense Tracker

Topics:

* Functions
* Lists
* Dictionaries
* File handling

## Project 6: Contact Book

Topics:

* Dictionaries
* Functions
* File handling

## Project 7: Student Management System

Topics:

* OOP
* Lists
* Dictionaries
* Functions
* File handling

---

# 46. Common Beginner Mistakes

## Mistake 1: Wrong indentation

Correct:

```python
if age >= 18:
    print("Adult")
```

Incorrect:

```python
if age >= 18:
print("Adult")
```

---

## Mistake 2: Confusing `=` and `==`

Assignment:

```python
x = 10
```

Comparison:

```python
x == 10
```

---

## Mistake 3: Forgetting that input returns a string

This:

```python
age = input("Enter age: ")
```

returns a string.

Use:

```python
age = int(input("Enter age: "))
```

when an integer is required.

---

## Mistake 4: Index out of range

```python
numbers = [1, 2, 3]

# numbers[5]  # IndexError
```

Valid indexes are:

```text
0
1
2
```

---

# 47. Python Learning Roadmap

Follow this order:

```text
Python Basics
      ↓
Variables
      ↓
Data Types
      ↓
Operators
      ↓
Strings
      ↓
Input / Output
      ↓
if / elif / else
      ↓
for / while loops
      ↓
Lists
      ↓
Tuples
      ↓
Sets
      ↓
Dictionaries
      ↓
Functions
      ↓
Lambda
      ↓
Modules
      ↓
Exception Handling
      ↓
File Handling
      ↓
OOP
      ↓
Iterators
      ↓
Generators
      ↓
Decorators
      ↓
JSON
      ↓
Virtual Environments
      ↓
Testing
      ↓
Projects
```

---

# 48. Python Quick Cheat Sheet

```python
# Print
print("Hello")

# Variable
name = "John"

# Integer
age = 25

# Float
price = 99.99

# Boolean
is_active = True

# Input
name = input("Enter name: ")

# Integer input
age = int(input("Enter age: "))

# If
if age >= 18:
    print("Adult")

# If else
if age >= 18:
    print("Adult")
else:
    print("Minor")

# For loop
for i in range(5):
    print(i)

# While loop
while condition:
    pass

# List
numbers = [1, 2, 3]

# Tuple
numbers = (1, 2, 3)

# Set
numbers = {1, 2, 3}

# Dictionary
person = {
    "name": "John",
    "age": 25
}

# Function
def add(a, b):
    return a + b

# Lambda
square = lambda x: x * x

# Exception handling
try:
    pass
except Exception:
    pass

# File handling
with open("file.txt", "r") as file:
    data = file.read()

# Import
import math

# Class
class Person:

    def __init__(self, name):
        self.name = name
```

---

# 🎯 Final Advice for Beginners

Don't try to memorize everything.

Focus on:

1. Understanding the syntax.
2. Writing code every day.
3. Practicing small problems.
4. Debugging your own errors.
5. Building small projects.
6. Reading other people's code.
7. Gradually learning libraries and frameworks.

The best way to learn Python is:

```text
LEARN
  ↓
PRACTICE
  ↓
MAKE MISTAKES
  ↓
DEBUG
  ↓
BUILD PROJECTS
  ↓
REPEAT
```

---

## ⭐ Useful Resources

* Python Official Website: https://www.python.org/
* Python Documentation: https://docs.python.org/3/
* Python Package Index: https://pypi.org/

---

## 🤝 Contributing

If you find an error or want to improve these notes, feel free to open an issue or submit a pull request.

---

## ⭐ Support

If these notes helped you learn Python, consider giving this repository a ⭐ on GitHub.

Happy Coding! 🐍💻

---

## 📜 License

This project is intended for educational purposes.
