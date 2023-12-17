# Introduction to Python Programming

Python is a high-level, interpreted programming language known for its readability and simplicity. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming. Python is widely used for automation testing, web development, data analysis, artificial intelligence, and more.

Kindly enable `Add PIP to PATH`

## Datatypes in Python

1. Numbers

   - a. Integers:
     It can be +ve / -ve whole numbers.
     Eg: 10, 203, -102

   - b. Floats:
     +ve / -ve irrational numbers / which has decimal points.
     Eg: -10.23, 0.23

   - c. Complex Numbers:
     real part + imaginary part
     -10.23 + 10j

2. Strings
   'a', "abc", "1234"

3. Collections / Sequences:

   - List
   - Tuple
   - Sets
   - Dictionary

4. Boolean
   True and False

## Print Function

The `print()` function is used to display output in Python.

```python
print("Hello, Python!")
```

### `sep` and `end` parameters

The `sep` parameter specifies the separator between the arguments in the `print()` function, and the `end` parameter specifies what to print at the end.

```python
print("apple", "orange", "banana", sep=", ", end=".\n")
```

## Variables

Variables are used to store and manage data in a program. Python is dynamically typed, meaning you don't need to declare the variable type explicitly.

```python
x = 5
y = "Hello, Python!"

print(x)
print(y)
```

### Home Work : Naming Conventions and Rules for Variables

## Type Conversion

Python provides functions for converting between different data types.

### `int()`

Floats -> Int - They would remove the decimal values

Strings -> Int - Every character in the string must be within 0-9 / base 10 value.

```python
num_str = "123"
num_int = int(num_str)
print(num_int)
```

### `float()`

```python
num_float = float(num_int)
print(num_float)
```

### `str()`

```python
str_num = str(num_float)
print(str_num)
```

## Input Function

The `input(prompt)` function allows you to take user input.

```python
name = input("Enter your name: ")
print("Hello, " + name + "!")
```
