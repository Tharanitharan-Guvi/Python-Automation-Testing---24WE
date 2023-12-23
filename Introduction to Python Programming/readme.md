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

## Operators

Operators are special symbols or keywords that perform operations on variables and values. Python supports various types of operators, including arithmetic, comparison, logical, assignment, bitwise, membership, and identity operators. Let's go through each type with examples:

### 1. Arithmetic Operators

```
+ - Addition
- - Subtraction
* - Multiplication
/ - Division
// - Floor Division
% - Modulo
** - exponent
```

```python
a = 10
b = 5

# Addition
sum_result = a + b  # 15

# Subtraction
diff_result = a - b  # 5

# Multiplication
prod_result = a * b  # 50

# Division
div_result = a / b  # 2.0 (result is a float)

# Floor Division
floor_div_result = a // b  # 2 (returns the quotient as an integer)

# Modulus (remainder)
mod_result = a % b  # 0

# Exponentiation
exp_result = a ** b  # 100000
```

### 2. Comparison Operators

Comparison operators are used to compare values and return a boolean result.

```
== - Equal to
!= - Not equat to
>
<
<=
>=
```

```python
x = 10
y = 20

# Equal to
print(x == y)  # False

# Not equal to
print(x != y)  # True

# Greater than
print(x > y)  # False

# Less than
print(x < y)  # True

# Greater than or equal to
print(x >= y)  # False

# Less than or equal to
print(x <= y)  # True
```

### 3. Logical Operators

Logical operators are used to combine conditional statements.

```
and

T T  T
T F  F
F T  F
F F  F

or

T T  T
T F  T
F T  T
F F  F


not

T   F
F   T
```

```python

p = True
q = False

# Logical AND
print(p and q)  # False

# Logical OR
print(p or q)  # True

# Logical NOT
print(not p)  # False
```

### 4. Assignment Operator

Assignment operators are used to assign values to variables.

```python
a = 10
b = 20
```

### 5. Membership Operator

Membership operators test whether a value is a member of a sequence.

```python

my_list = [1, 2, 3, 4, 5]

# In
print(3 in my_list)  # True

# Not in
print(6 not in my_list)  # True
```

### 6. Identity Operators

Identity operators compare the memory addresses of two objects.

```python
a = [1, 2, 3]
b = a
c = [1, 2, 3]

# is
print(a is b)  # True (a and b reference the same object)

# is not
print(a is not c)  # True (a and c reference different objects)
```
