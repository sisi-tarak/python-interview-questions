# Python Interview Questions & Answers

> Click ⭐ if you like the project. Follow me [@sisi_tarakk](https://www.instagram.com/sisi_tarakk) on Instagram and [@sisitarak](https://www.linkedin.com/in/sisitarak) on LinkedIn for more.

> Pull Requests are highly recommended and appreciated. 🙌

---

### Table of Contents

<details open>
<summary>
Hide/Show table of contents
</summary>

#### 🟢 Basic Level — Python Fundamentals

| No. | Questions |
| --- | --------- |
| 1 | [What is Python? What are its key features?](#1-what-is-python-what-are-its-key-features) |
| 2 | [What are the key differences between Python 2 and Python 3?](#2-what-are-the-key-differences-between-python-2-and-python-3) |
| 3 | [What are Python's built-in data types?](#3-what-are-pythons-built-in-data-types) |
| 4 | [What is the difference between mutable and immutable types?](#4-what-is-the-difference-between-mutable-and-immutable-types) |
| 5 | [What is the difference between a list, tuple, set, and dictionary?](#5-what-is-the-difference-between-a-list-tuple-set-and-dictionary) |
| 6 | [What is the difference between == and is operators?](#6-what-is-the-difference-between--and-is-operators) |
| 7 | [What are *args and **kwargs in Python?](#7-what-are-args-and-kwargs-in-python) |
| 8 | [What is the difference between a shallow copy and a deep copy?](#8-what-is-the-difference-between-a-shallow-copy-and-a-deep-copy) |
| 9 | [What are list comprehensions? How do they work?](#9-what-are-list-comprehensions-how-do-they-work) |
| 10 | [What is the difference between range() and xrange()?](#10-what-is-the-difference-between-range-and-xrange) |
| 11 | [What are Python's scope rules? What is LEGB?](#11-what-are-pythons-scope-rules-what-is-legb) |
| 12 | [What is the difference between break, continue, and pass?](#12-what-is-the-difference-between-break-continue-and-pass) |
| 13 | [How does Python handle memory management?](#13-how-does-python-handle-memory-management) |
| 14 | [What is a lambda function in Python?](#14-what-is-a-lambda-function-in-python) |
| 15 | [What are map(), filter(), and reduce() functions?](#15-what-are-map-filter-and-reduce-functions) |
| 16 | [What is the difference between append() and extend() in a list?](#16-what-is-the-difference-between-append-and-extend-in-a-list) |
| 17 | [What is string formatting in Python? What are the methods?](#17-what-is-string-formatting-in-python-what-are-the-methods) |
| 18 | [What is exception handling in Python?](#18-what-is-exception-handling-in-python) |
| 19 | [What is the purpose of the finally block?](#19-what-is-the-purpose-of-the-finally-block) |
| 20 | [What are Python modules and packages?](#20-what-are-python-modules-and-packages) |
| 21 | [What is the difference between import module and from module import?](#21-what-is-the-difference-between-import-module-and-from-module-import) |
| 22 | [What is PEP 8?](#22-what-is-pep-8) |
| 23 | [What are docstrings in Python?](#23-what-are-docstrings-in-python) |
| 24 | [What is the difference between del, remove(), and pop()?](#24-what-is-the-difference-between-del-remove-and-pop) |
| 25 | [What is type casting in Python?](#25-what-is-type-casting-in-python) |

#### 🟡 Medium Level — OOP in Python

| No. | Questions |
| --- | --------- |
| 26 | [What are the four pillars of OOP in Python?](#26-what-are-the-four-pillars-of-oop-in-python) |
| 27 | [What is the difference between a class and an object?](#27-what-is-the-difference-between-a-class-and-an-object) |
| 28 | [What is __init__? Is it a constructor?](#28-what-is-__init__-is-it-a-constructor) |
| 29 | [What is the difference between __str__ and __repr__?](#29-what-is-the-difference-between-__str__-and-__repr__) |
| 30 | [What is the difference between instance, class, and static methods?](#30-what-is-the-difference-between-instance-class-and-static-methods) |
| 31 | [What is inheritance in Python? What are its types?](#31-what-is-inheritance-in-python-what-are-its-types) |
| 32 | [What is MRO (Method Resolution Order)?](#32-what-is-mro-method-resolution-order) |
| 33 | [What is polymorphism in Python?](#33-what-is-polymorphism-in-python) |
| 34 | [What is encapsulation in Python?](#34-what-is-encapsulation-in-python) |
| 35 | [What are dunder (magic) methods in Python?](#35-what-are-dunder-magic-methods-in-python) |
| 36 | [What is the difference between __new__ and __init__?](#36-what-is-the-difference-between-__new__-and-__init__) |
| 37 | [What is duck typing in Python?](#37-what-is-duck-typing-in-python) |
| 38 | [What are abstract classes and interfaces in Python?](#38-what-are-abstract-classes-and-interfaces-in-python) |
| 39 | [What is the super() function?](#39-what-is-the-super-function) |
| 40 | [What are dataclasses in Python?](#40-what-are-dataclasses-in-python) |

#### 🟡 Medium Level — Functions, Decorators & Generators

| No. | Questions |
| --- | --------- |
| 41 | [What are closures in Python?](#41-what-are-closures-in-python) |
| 42 | [What are decorators in Python? How do they work?](#42-what-are-decorators-in-python-how-do-they-work) |
| 43 | [How do you write a decorator with arguments?](#43-how-do-you-write-a-decorator-with-arguments) |
| 44 | [What are generators in Python?](#44-what-are-generators-in-python) |
| 45 | [What is the difference between yield and return?](#45-what-is-the-difference-between-yield-and-return) |
| 46 | [What is a generator expression?](#46-what-is-a-generator-expression) |
| 47 | [What is the difference between an iterator and an iterable?](#47-what-is-the-difference-between-an-iterator-and-an-iterable) |
| 48 | [What are context managers? How does the with statement work?](#48-what-are-context-managers-how-does-the-with-statement-work) |
| 49 | [What is functools.wraps and why is it important?](#49-what-is-functoolswraps-and-why-is-it-important) |
| 50 | [What is memoization? How do you implement it in Python?](#50-what-is-memoization-how-do-you-implement-it-in-python) |

#### 🟡 Medium Level — File Handling & Exceptions

| No. | Questions |
| --- | --------- |
| 51 | [How do you read and write files in Python?](#51-how-do-you-read-and-write-files-in-python) |
| 52 | [How do you handle CSV and JSON files in Python?](#52-how-do-you-handle-csv-and-json-files-in-python) |
| 53 | [What are custom exceptions in Python?](#53-what-are-custom-exceptions-in-python) |
| 54 | [What is the difference between raise and raise from in Python?](#54-what-is-the-difference-between-raise-and-raise-from-in-python) |
| 55 | [How do you use regular expressions in Python?](#55-how-do-you-use-regular-expressions-in-python) |

#### 🟡 Medium Level — Data Structures & Built-in Tools

| No. | Questions |
| --- | --------- |
| 56 | [What is the collections module? Name its key classes](#56-what-is-the-collections-module-name-its-key-classes) |
| 57 | [What is the difference between a list and a deque?](#57-what-is-the-difference-between-a-list-and-a-deque) |
| 58 | [What is enumerate() and zip() in Python?](#58-what-is-enumerate-and-zip-in-python) |
| 59 | [What is the difference between sorted() and list.sort()?](#59-what-is-the-difference-between-sorted-and-listsort) |
| 60 | [What are *unpacking and **unpacking in Python?](#60-what-are-unpacking-and-unpacking-in-python) |
| 61 | [What is the difference between dict.get() and dict[key]?](#61-what-is-the-difference-between-dictget-and-dictkey) |
| 62 | [What are frozensets in Python?](#62-what-are-frozensets-in-python) |
| 63 | [What are named tuples?](#63-what-are-named-tuples) |
| 64 | [What is the difference between any() and all()?](#64-what-is-the-difference-between-any-and-all) |
| 65 | [What is __slots__ in Python?](#65-what-is-__slots__-in-python) |

#### 🔴 Advanced Level — Concurrency & Performance

| No. | Questions |
| --- | --------- |
| 66 | [What is the GIL (Global Interpreter Lock)?](#66-what-is-the-gil-global-interpreter-lock) |
| 67 | [What is the difference between threading and multiprocessing?](#67-what-is-the-difference-between-threading-and-multiprocessing) |
| 68 | [What is asyncio? How does it work?](#68-what-is-asyncio-how-does-it-work) |
| 69 | [What is the difference between concurrency and parallelism?](#69-what-is-the-difference-between-concurrency-and-parallelism) |
| 70 | [How do you share data between processes in Python?](#70-how-do-you-share-data-between-processes-in-python) |
| 71 | [What is a thread lock? How do you prevent race conditions?](#71-what-is-a-thread-lock-how-do-you-prevent-race-conditions) |
| 72 | [What is the difference between async/await and threading?](#72-what-is-the-difference-between-asyncawait-and-threading) |

#### 🔴 Advanced Level — Memory, Internals & Metaclasses

| No. | Questions |
| --- | --------- |
| 73 | [How does Python's garbage collector work?](#73-how-does-pythons-garbage-collector-work) |
| 74 | [What are metaclasses in Python?](#74-what-are-metaclasses-in-python) |
| 75 | [What are descriptors in Python?](#75-what-are-descriptors-in-python) |
| 76 | [What is monkey patching in Python?](#76-what-is-monkey-patching-in-python) |
| 77 | [What is the difference between __getattr__ and __getattribute__?](#77-what-is-the-difference-between-__getattr__-and-__getattribute__) |
| 78 | [What is pickling and unpickling in Python?](#78-what-is-pickling-and-unpickling-in-python) |
| 79 | [What are weak references in Python?](#79-what-are-weak-references-in-python) |
| 80 | [What is the difference between @staticmethod, @classmethod, and @property?](#80-what-is-the-difference-between-staticmethod-classmethod-and-property) |

#### 🔴 Advanced Level — Libraries & Frameworks

| No. | Questions |
| --- | --------- |
| 81 | [What is NumPy? How is it different from a Python list?](#81-what-is-numpy-how-is-it-different-from-a-python-list) |
| 82 | [What is Pandas? Explain Series and DataFrame](#82-what-is-pandas-explain-series-and-dataframe) |
| 83 | [What is the difference between loc and iloc in Pandas?](#83-what-is-the-difference-between-loc-and-iloc-in-pandas) |
| 84 | [What is Django? What are its key components?](#84-what-is-django-what-are-its-key-components) |
| 85 | [What is Flask? How does it differ from Django?](#85-what-is-flask-how-does-it-differ-from-django) |
| 86 | [What is FastAPI and why is it gaining popularity?](#86-what-is-fastapi-and-why-is-it-gaining-popularity) |
| 87 | [What is SQLAlchemy?](#87-what-is-sqlalchemy) |

#### 🎯 Scenario & Conceptual Questions (MNC Favourites)

| No. | Questions |
| --- | --------- |
| 88 | [How is Python interpreted? What is bytecode?](#88-how-is-python-interpreted-what-is-bytecode) |
| 89 | [What is the difference between is None and == None?](#89-what-is-the-difference-between-is-none-and--none) |
| 90 | [What happens when you pass a list to a function and modify it inside?](#90-what-happens-when-you-pass-a-list-to-a-function-and-modify-it-inside) |
| 91 | [What is the output of this code and why? (tricky questions)](#91-what-is-the-output-of-this-code-and-why-tricky-questions) |
| 92 | [How would you find duplicates in a list in Python?](#92-how-would-you-find-duplicates-in-a-list-in-python) |
| 93 | [How do you reverse a string in Python?](#93-how-do-you-reverse-a-string-in-python) |
| 94 | [How do you merge two dictionaries in Python?](#94-how-do-you-merge-two-dictionaries-in-python) |
| 95 | [What is the Singleton design pattern in Python?](#95-what-is-the-singleton-design-pattern-in-python) |
| 96 | [How do you profile and optimize Python code?](#96-how-do-you-profile-and-optimize-python-code) |
| 97 | [What are Python type hints? Why are they used?](#97-what-are-python-type-hints-why-are-they-used) |
| 98 | [How do you write unit tests in Python?](#98-how-do-you-write-unit-tests-in-python) |
| 99 | [What is virtual environment in Python and why is it important?](#99-what-is-virtual-environment-in-python-and-why-is-it-important) |
| 100 | [What are the latest features in Python 3.10, 3.11, 3.12, and 3.13?](#100-what-are-the-latest-features-in-python-310-311-312-and-313) |

</details>

---

<br>

## 🟢 Basic Level — Python Fundamentals

<br>

### 1. What is Python? What are its key features?

Python is a **high-level, interpreted, general-purpose programming language** created by **Guido van Rossum** and first released in **1991**. It emphasizes code readability and simplicity, making it one of the most popular languages in the world.

**Key features:**

| Feature | Description |
| ------- | ----------- |
| **Interpreted** | Executed line-by-line — no separate compilation step |
| **Dynamically typed** | Variable types determined at runtime |
| **Object-oriented** | Supports classes, inheritance, polymorphism |
| **High-level** | Abstracts hardware details |
| **Extensive standard library** | "Batteries included" — datetime, os, re, json, etc. |
| **Cross-platform** | Runs on Windows, Linux, macOS, etc. |
| **Open source** | Free to use and distribute |
| **Large ecosystem** | NumPy, Pandas, Django, Flask, TensorFlow, PyTorch |

```python
# Python philosophy: readable and concise
# "Hello World" in Python
print("Hello, World!")

# Compare Java (verbose) vs Python (clean)
# Java: System.out.println("Hello, World!");
# Python: print("Hello, World!")
```

**Use cases:** Web development, Data Science, AI/ML, Automation, Scripting, DevOps, Cybersecurity.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 2. What are the key differences between Python 2 and Python 3?

| Feature | Python 2 | Python 3 |
| ------- | -------- | -------- |
| `print` | Statement: `print "hello"` | Function: `print("hello")` |
| Division | `5/2 = 2` (integer) | `5/2 = 2.5` (float) |
| String default | ASCII (bytes) | Unicode (str) |
| `range()` | Returns a list | Returns an iterator (memory efficient) |
| `xrange()` | Exists | Removed — `range()` does its job |
| `input()` | Evaluates expression | Returns string |
| `__future__` | Used for forward compatibility | Not needed |
| Support status | ❌ EOL since Jan 1, 2020 | ✅ Actively maintained |
| `super()` | `super(ClassName, self)` | `super()` (no args needed) |

```python
# Python 2 (old)
print "Hello"          # Statement
5 / 2                  # Returns 2 (integer division)

# Python 3 (current)
print("Hello")         # Function
5 / 2                  # Returns 2.5 (float division)
5 // 2                 # Returns 2 (floor division)
```

> **Always use Python 3.** Python 2 is officially dead.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 3. What are Python's built-in data types?

| Category | Types |
| -------- | ----- |
| **Numeric** | `int`, `float`, `complex` |
| **Sequence** | `str`, `list`, `tuple`, `range` |
| **Mapping** | `dict` |
| **Set** | `set`, `frozenset` |
| **Boolean** | `bool` |
| **Binary** | `bytes`, `bytearray`, `memoryview` |
| **None** | `NoneType` |

```python
# Examples
x = 42           # int
y = 3.14         # float
z = 2 + 3j       # complex

name = "Sisi"    # str
nums = [1, 2, 3] # list (mutable)
point = (10, 20) # tuple (immutable)
r = range(5)     # range

profile = {"name": "Sisi", "age": 20}  # dict

unique = {1, 2, 3}        # set (no duplicates)
frozen = frozenset({1, 2}) # frozenset (immutable set)

flag = True      # bool
nothing = None   # NoneType

# Check type
print(type(x))   # <class 'int'>
print(isinstance(x, int))  # True
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 4. What is the difference between mutable and immutable types?

| Feature | Mutable | Immutable |
| ------- | ------- | --------- |
| Can be changed after creation? | ✅ Yes | ❌ No |
| Examples | `list`, `dict`, `set`, `bytearray` | `int`, `float`, `str`, `tuple`, `frozenset` |
| Memory | Same object modified in-place | New object created on every change |
| As dict key? | ❌ No (unhashable) | ✅ Yes (hashable) |

```python
# Mutable — modified in-place, same memory address
my_list = [1, 2, 3]
print(id(my_list))   # e.g. 140234567890
my_list.append(4)
print(id(my_list))   # SAME id — same object modified
print(my_list)       # [1, 2, 3, 4]

# Immutable — new object created on change
my_str = "hello"
print(id(my_str))    # e.g. 140234567999
my_str += " world"
print(id(my_str))    # DIFFERENT id — new string object
print(my_str)        # "hello world"

# Tuple is immutable
t = (1, 2, 3)
# t[0] = 10   # TypeError: 'tuple' object does not support item assignment

# ⚠️ Mutable default argument trap — common interview trick!
def add_item(item, lst=[]):   # ❌ BAD — list shared across calls
    lst.append(item)
    return lst

def add_item(item, lst=None): # ✅ GOOD
    if lst is None:
        lst = []
    lst.append(item)
    return lst
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 5. What is the difference between a list, tuple, set, and dictionary?

| Feature | List | Tuple | Set | Dictionary |
| ------- | ---- | ----- | --- | ---------- |
| Syntax | `[1, 2]` | `(1, 2)` | `{1, 2}` | `{"k": "v"}` |
| Ordered? | ✅ Yes | ✅ Yes | ❌ No | ✅ Yes (Python 3.7+) |
| Mutable? | ✅ Yes | ❌ No | ✅ Yes | ✅ Yes |
| Duplicates? | ✅ Yes | ✅ Yes | ❌ No | ❌ No (keys) |
| Indexed? | ✅ Yes | ✅ Yes | ❌ No | ✅ By key |
| Hashable? | ❌ No | ✅ Yes | ❌ No | ❌ No |
| Use case | General collection | Fixed data, dict key | Unique values | Key-value mapping |

```python
# List — ordered, mutable, allows duplicates
fruits = ["apple", "mango", "apple"]
fruits.append("banana")

# Tuple — ordered, immutable, allows duplicates
point = (10, 20)
# point[0] = 5  # TypeError

# Set — unordered, unique elements only
unique_nums = {1, 2, 2, 3}  # → {1, 2, 3}
unique_nums.add(4)
print(1 in unique_nums)     # True (O(1) lookup)

# Dictionary — key-value pairs
user = {"name": "Sisi", "age": 20, "city": "Tirupati"}
print(user["name"])         # "Sisi"
user["role"] = "CEO"        # add new key
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 6. What is the difference between == and is operators?

| Operator | Compares | Returns True when |
| -------- | -------- | ----------------- |
| `==` | **Value** (equality) | Both objects have same value |
| `is` | **Identity** (memory address) | Both variables point to same object |

```python
a = [1, 2, 3]
b = [1, 2, 3]
c = a             # c references the SAME object as a

print(a == b)     # True  — same values
print(a is b)     # False — different objects in memory
print(a is c)     # True  — same object

print(id(a))      # e.g. 140234567890
print(id(b))      # e.g. 140234567999 (different)
print(id(c))      # e.g. 140234567890 (same as a)

# ✅ Always use `is` for None checks (best practice)
x = None
if x is None:     # Correct
    print("x is None")
if x == None:     # Works, but not recommended
    print("x equals None")

# ⚠️ Small integer caching (CPython implementation detail)
x = 100
y = 100
print(x is y)     # True  — CPython caches -5 to 256
x = 1000
y = 1000
print(x is y)     # False — outside cache range
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 7. What are *args and **kwargs in Python?

`*args` and `**kwargs` allow functions to accept a **variable number of arguments**.

| Syntax | Type | Receives |
| ------ | ---- | -------- |
| `*args` | Positional | Extra positional args as a **tuple** |
| `**kwargs` | Keyword | Extra keyword args as a **dict** |

```python
# *args — variable positional arguments
def add(*args):
    print(type(args))  # <class 'tuple'>
    return sum(args)

print(add(1, 2, 3))       # 6
print(add(1, 2, 3, 4, 5)) # 15

# **kwargs — variable keyword arguments
def user_info(**kwargs):
    print(type(kwargs))   # <class 'dict'>
    for key, value in kwargs.items():
        print(f"{key}: {value}")

user_info(name="Sisi", age=20, role="CEO")
# name: Sisi
# age: 20
# role: CEO

# Combining both — order matters: normal → *args → **kwargs
def full_function(required, *args, **kwargs):
    print(f"Required: {required}")
    print(f"Args: {args}")
    print(f"Kwargs: {kwargs}")

full_function("hello", 1, 2, 3, name="Sisi", age=20)

# Unpacking with * and **
nums = [1, 2, 3]
print(add(*nums))        # same as add(1, 2, 3)

info = {"name": "Sisi", "age": 20}
user_info(**info)        # same as user_info(name="Sisi", age=20)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 8. What is the difference between a shallow copy and a deep copy?

| Type | What gets copied | Nested objects |
| ---- | --------------- | -------------- |
| **Assignment** (`=`) | Reference only | Shared completely |
| **Shallow copy** | Outer object | Inner objects still shared |
| **Deep copy** | Everything | Completely independent |

```python
import copy

original = [[1, 2, 3], [4, 5, 6]]

# Assignment — same object reference
ref = original
ref[0].append(99)
print(original)    # [[1, 2, 3, 99], [4, 5, 6]] — original changed!

# Shallow copy — new outer object, but inner lists still shared
shallow = copy.copy(original)
# OR: shallow = original.copy()  OR  shallow = original[:]
shallow[0].append(88)
print(original)    # [[1, 2, 3, 99, 88], [4, 5, 6]] — still affected!
shallow.append([7, 8, 9])
print(original)    # unchanged at outer level

# Deep copy — completely independent copy
deep = copy.deepcopy(original)
deep[0].append(77)
print(original)    # unchanged — deep copy is truly independent
```

> **Rule of thumb:** If your object contains nested mutable objects, always use `deepcopy`. For flat structures, `copy` or slicing `[:]` is fine.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 9. What are list comprehensions? How do they work?

List comprehensions provide a **concise, readable way to create lists** from existing iterables with optional filtering.

```python
# Syntax: [expression for item in iterable if condition]

# Basic — squares of numbers
squares = [x**2 for x in range(1, 6)]
print(squares)  # [1, 4, 9, 16, 25]

# With condition — even numbers only
evens = [x for x in range(20) if x % 2 == 0]
print(evens)    # [0, 2, 4, 6, 8, 10, 12, 14, 16, 18]

# String manipulation
words = ["hello", "world", "python"]
upper = [w.upper() for w in words]
print(upper)    # ['HELLO', 'WORLD', 'PYTHON']

# Nested comprehension — flatten 2D list
matrix = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
flat = [num for row in matrix for num in row]
print(flat)     # [1, 2, 3, 4, 5, 6, 7, 8, 9]

# Dict comprehension
squared_dict = {x: x**2 for x in range(1, 6)}
print(squared_dict)  # {1: 1, 2: 4, 3: 9, 4: 16, 5: 25}

# Set comprehension
unique_squares = {x**2 for x in [-2, -1, 0, 1, 2]}
print(unique_squares)  # {0, 1, 4}

# Equivalent for loop (less Pythonic)
squares_loop = []
for x in range(1, 6):
    squares_loop.append(x**2)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 10. What is the difference between range() and xrange()?

| Feature | `range()` Python 3 | `xrange()` Python 2 |
| ------- | ------------------ | -------------------- |
| Returns | Range object (lazy) | xrange object (lazy) |
| Memory | ✅ O(1) — generates on demand | ✅ O(1) — generates on demand |
| Status | ✅ Used in Python 3 | ❌ Removed in Python 3 |

```python
# Python 3 — range() is already memory-efficient (like Python 2's xrange)
r = range(1, 1_000_000)
print(type(r))       # <class 'range'>
print(r[0])          # 1 — supports indexing
print(len(r))        # 999999

# range() doesn't generate all numbers at once:
import sys
print(sys.getsizeof(range(1000000)))  # 48 bytes — always constant!
print(sys.getsizeof(list(range(1000000))))  # ~8MB — stores all numbers

# Common uses
for i in range(5):            # 0, 1, 2, 3, 4
    print(i)

for i in range(0, 10, 2):    # 0, 2, 4, 6, 8 (step)
    print(i)

for i in range(10, 0, -1):   # 10, 9, 8, ..., 1 (reverse)
    print(i)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 11. What are Python's scope rules? What is LEGB?

Python resolves variable names using the **LEGB rule** — searching scopes in this order:

| Letter | Scope | Description |
| ------ | ----- | ----------- |
| **L** | Local | Variables defined inside the current function |
| **E** | Enclosing | Variables in enclosing (outer) functions (for closures) |
| **G** | Global | Variables defined at the module level |
| **B** | Built-in | Python's built-in names (`len`, `print`, `range`, etc.) |

```python
x = "global"         # G — global scope

def outer():
    x = "enclosing"  # E — enclosing scope

    def inner():
        x = "local"  # L — local scope
        print(x)     # "local" — found in L first

    inner()
    print(x)         # "enclosing"

outer()
print(x)             # "global"

# global keyword — modify global variable inside function
count = 0
def increment():
    global count     # declare we want to use/modify global `count`
    count += 1

increment()
print(count)         # 1

# nonlocal keyword — modify enclosing scope variable
def counter():
    total = 0
    def add(n):
        nonlocal total   # modify enclosing `total`
        total += n
    add(5)
    add(3)
    return total

print(counter())     # 8
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 12. What is the difference between break, continue, and pass?

| Keyword | Action | Use case |
| ------- | ------ | -------- |
| `break` | Exits the loop entirely | Stop when condition is met |
| `continue` | Skips current iteration, moves to next | Skip specific items |
| `pass` | Does nothing — placeholder | Empty function/class/block |

```python
# break — stop the loop
for i in range(10):
    if i == 5:
        break
    print(i)         # 0, 1, 2, 3, 4

# continue — skip current iteration
for i in range(10):
    if i % 2 == 0:
        continue     # skip even numbers
    print(i)         # 1, 3, 5, 7, 9

# pass — placeholder (does nothing)
def my_function():
    pass             # TODO: implement later

class EmptyClass:
    pass

for i in range(5):
    if i == 3:
        pass         # placeholder for future logic
    print(i)         # 0, 1, 2, 3, 4 — all printed (pass does nothing)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 13. How does Python handle memory management?

Python uses **automatic memory management** through three mechanisms:

**1. Reference Counting** — every object has a count of references pointing to it. When count drops to 0, memory is freed immediately.

**2. Cyclic Garbage Collector** — handles reference cycles (objects referencing each other) that reference counting can't resolve.

**3. Memory Pools (pymalloc)** — Python allocates memory in pools for small objects (≤512 bytes) to avoid OS overhead.

```python
import gc
import sys

# Reference counting
a = [1, 2, 3]
print(sys.getrefcount(a))  # 2 (a + getrefcount arg)
b = a                       # ref count becomes 3
del b                       # ref count back to 2
del a                       # ref count = 0 → memory freed

# Reference cycle — requires garbage collector
class Node:
    def __init__(self):
        self.ref = None

n1 = Node()
n2 = Node()
n1.ref = n2    # n1 → n2
n2.ref = n1    # n2 → n1  (cycle!)
del n1, n2     # ref count doesn't reach 0 — GC needed

# Manual GC control
gc.collect()               # force garbage collection
gc.disable()               # disable automatic GC
print(gc.get_count())      # (gen0, gen1, gen2) collection counts

# Memory size of objects
print(sys.getsizeof([]))            # 56 bytes (empty list)
print(sys.getsizeof([1, 2, 3]))     # 88 bytes
print(sys.getsizeof("hello"))       # 54 bytes
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 14. What is a lambda function in Python?

A lambda function is an **anonymous, single-expression function** defined with the `lambda` keyword. It's used for short, throwaway functions — especially with `map()`, `filter()`, `sorted()`.

```python
# Syntax: lambda arguments: expression

# Regular function
def square(x):
    return x ** 2

# Equivalent lambda
square = lambda x: x ** 2
print(square(5))   # 25

# Lambda with multiple arguments
add = lambda x, y: x + y
print(add(3, 4))   # 7

# Common uses — sorting with key
students = [("Sisi", 20), ("Yamini", 22), ("Pavani", 19)]
students.sort(key=lambda s: s[1])   # sort by age
print(students)  # [('Pavani', 19), ('Sisi', 20), ('Yamini', 22)]

# With map() — apply function to each element
nums = [1, 2, 3, 4, 5]
squared = list(map(lambda x: x**2, nums))
print(squared)   # [1, 4, 9, 16, 25]

# With filter() — keep elements where condition is True
evens = list(filter(lambda x: x % 2 == 0, nums))
print(evens)     # [2, 4]

# ⚠️ Limitations: lambdas can't contain statements (if/else must be ternary)
# ❌ lambda x: if x > 0: return x   # SyntaxError
# ✅ lambda x: x if x > 0 else 0    # ternary works
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 15. What are map(), filter(), and reduce() functions?

These are **functional programming tools** for transforming and filtering iterables.

```python
from functools import reduce

nums = [1, 2, 3, 4, 5]

# map(function, iterable) — apply function to every element
squares = list(map(lambda x: x**2, nums))
print(squares)    # [1, 4, 9, 16, 25]

# map with multiple iterables
a = [1, 2, 3]
b = [10, 20, 30]
sums = list(map(lambda x, y: x + y, a, b))
print(sums)       # [11, 22, 33]

# filter(function, iterable) — keep elements where function returns True
evens = list(filter(lambda x: x % 2 == 0, nums))
print(evens)      # [2, 4]

# None as function — filters out falsy values
mixed = [0, 1, "", "hello", None, True, False]
truthy = list(filter(None, mixed))
print(truthy)     # [1, 'hello', True]

# reduce(function, iterable) — cumulatively apply function to reduce to single value
total = reduce(lambda x, y: x + y, nums)
print(total)      # 15  (1+2=3, 3+3=6, 6+4=10, 10+5=15)

product = reduce(lambda x, y: x * y, nums)
print(product)    # 120  (1*2*3*4*5)

# Modern Python prefers list comprehensions over map/filter
# squares = [x**2 for x in nums]      — more readable
# evens   = [x for x in nums if x%2==0]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 16. What is the difference between append() and extend() in a list?

| Method | Adds | Input type |
| ------ | ---- | ---------- |
| `append(x)` | Single element as-is | Any object |
| `extend(iterable)` | Each element from iterable individually | Must be iterable |

```python
lst = [1, 2, 3]

# append — adds the object as a single element
lst.append([4, 5])
print(lst)    # [1, 2, 3, [4, 5]]  ← nested list added as one element

lst = [1, 2, 3]
lst.append(4)
print(lst)    # [1, 2, 3, 4]

# extend — unpacks iterable and adds each element
lst = [1, 2, 3]
lst.extend([4, 5])
print(lst)    # [1, 2, 3, 4, 5]  ← elements added individually

lst.extend("abc")
print(lst)    # [1, 2, 3, 4, 5, 'a', 'b', 'c']  ← string unpacked

# insert(index, item) — insert at specific position
lst = [1, 2, 3]
lst.insert(1, 10)    # insert 10 at index 1
print(lst)           # [1, 10, 2, 3]

# += operator behaves like extend for lists
lst = [1, 2, 3]
lst += [4, 5]        # same as lst.extend([4, 5])
print(lst)           # [1, 2, 3, 4, 5]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 17. What is string formatting in Python? What are the methods?

```python
name = "Sisi"
age = 20
score = 98.5

# Method 1: % operator (old style)
print("Hello %s, you are %d years old" % (name, age))

# Method 2: str.format() (Python 2.6+)
print("Hello {}, you are {} years old".format(name, age))
print("Hello {name}, you are {age}".format(name=name, age=age))

# Method 3: f-strings (Python 3.6+ — recommended)
print(f"Hello {name}, you are {age} years old")
print(f"Score: {score:.2f}")      # 98.50 — format float to 2 decimals
print(f"Score: {score:>10.2f}")   # right-align in 10-char field
print(f"{name!r}")                # 'Sisi' — repr() formatting
print(f"{name!u}")                # 'SISI' — uppercase (Python 3.12+)

# f-strings support expressions
print(f"Next year you'll be {age + 1}")     # 21
print(f"Upper: {name.upper()}")             # SISI
print(f"Type: {type(name).__name__}")       # str

# Method 4: Template strings (safe for user input)
from string import Template
t = Template("Hello $name!")
print(t.substitute(name=name))    # Hello Sisi!
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 18. What is exception handling in Python?

Exception handling lets you **gracefully handle errors** at runtime — preventing crashes and allowing recovery.

```python
# Basic try-except
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")

# Multiple exceptions
try:
    x = int(input("Enter a number: "))
    result = 10 / x
except ValueError:
    print("That's not a valid number!")
except ZeroDivisionError:
    print("Cannot divide by zero!")
except (TypeError, AttributeError) as e:  # multiple in one except
    print(f"Error: {e}")

# Catch all exceptions (use carefully)
try:
    risky_operation()
except Exception as e:           # catches all non-system-exiting exceptions
    print(f"Unexpected error: {e}")
    raise                        # re-raise after logging

# try-except-else-finally
try:
    file = open("data.txt", "r")
    content = file.read()
except FileNotFoundError:
    print("File not found!")
else:
    print("File read successfully!")  # runs ONLY if no exception
    print(content[:100])
finally:
    file.close()                 # ALWAYS runs — cleanup code
    print("Done.")

# Common built-in exceptions:
# ValueError, TypeError, KeyError, IndexError, AttributeError
# FileNotFoundError, ZeroDivisionError, ImportError
# StopIteration, OverflowError, MemoryError, RecursionError
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 19. What is the purpose of the finally block?

The `finally` block **always executes** regardless of whether an exception was raised, caught, or not. It's used for cleanup operations like closing files, releasing locks, or disconnecting from databases.

```python
import sqlite3

def get_user(user_id):
    conn = None
    try:
        conn = sqlite3.connect("users.db")
        cursor = conn.cursor()
        cursor.execute("SELECT * FROM users WHERE id=?", (user_id,))
        return cursor.fetchone()
    except sqlite3.Error as e:
        print(f"Database error: {e}")
        return None
    finally:
        if conn:
            conn.close()   # ALWAYS closes connection, even if exception
        print("DB connection closed.")

# finally runs even with return in try
def demo():
    try:
        return "from try"
    finally:
        print("finally runs!")   # prints BEFORE return
        # return "from finally"  # would override try's return

result = demo()   # prints "finally runs!", then result = "from try"
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 20. What are Python modules and packages?

**Module:** A single `.py` file containing Python code (functions, classes, variables).
**Package:** A directory containing multiple modules and an `__init__.py` file.

```python
# math_utils.py — this is a module
def add(a, b):
    return a + b

def multiply(a, b):
    return a * b

PI = 3.14159

# Using the module
import math_utils
print(math_utils.add(2, 3))     # 5
print(math_utils.PI)            # 3.14159

from math_utils import add, PI
print(add(2, 3))                # 5

# Package structure:
# mypackage/
# ├── __init__.py        ← makes it a package
# ├── utils.py
# ├── validators.py
# └── models/
#     ├── __init__.py
#     └── user.py

# __init__.py can expose selected items:
# from .utils import add, multiply
# from .validators import validate_email

# Built-in modules
import os, sys, math, datetime, json, re, random, time
import collections, itertools, functools, pathlib
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 21. What is the difference between import module and from module import?

```python
# Method 1: import module — imports the module object
import math
print(math.pi)       # 3.14159...
print(math.sqrt(16)) # 4.0
# Access via math.function() — avoids namespace collision

# Method 2: from module import name — imports specific names
from math import pi, sqrt
print(pi)            # 3.14159...
print(sqrt(16))      # 4.0
# Direct access — cleaner but can cause name conflicts

# Method 3: import with alias
import numpy as np   # standard convention
import pandas as pd
print(np.array([1, 2, 3]))

from datetime import datetime as dt
print(dt.now())

# Method 4: from module import * — imports all public names (avoid!)
from math import *   # ❌ pollutes namespace, hard to trace where names came from
print(sin(pi/2))     # 1.0 — but where did sin come from?

# Best practice: use explicit imports
from os.path import join, exists, dirname  # explicit
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 22. What is PEP 8?

PEP 8 is Python's **official style guide** — a set of conventions for writing clean, readable Python code. Written by Guido van Rossum.

```python
# ── Naming conventions ──
variable_name = "snake_case"          # variables and functions
CONSTANT_VALUE = 42                   # constants (ALL_CAPS)
ClassName = "PascalCase"              # classes
_protected = "single underscore"      # protected (convention only)
__private = "double underscore"       # triggers name mangling

# ── Indentation ──
# Use 4 spaces (NOT tabs)
def my_function():
    if True:
        return "hello"

# ── Line length ──
# Max 79 characters per line (79 for code, 72 for docstrings)
result = (first_value + second_value +
          third_value + fourth_value)  # line continuation

# ── Spacing ──
x = 5              # spaces around = in assignments
def fn(x, y=10):   # no spaces around = in default args
    return x + y

# ── Imports ──
# Standard library first, then third-party, then local
import os
import sys

import numpy as np

from mypackage import mymodule

# ── Blank lines ──
# 2 blank lines around top-level definitions
# 1 blank line inside class between methods

# Tools to enforce PEP 8:
# flake8, pylint, black (auto-formatter), isort (import sorter)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 23. What are docstrings in Python?

Docstrings are **string literals** placed as the first statement inside a module, function, class, or method — used to document what the code does. Accessible via `.__doc__` or `help()`.

```python
def calculate_bmi(weight_kg, height_m):
    """
    Calculate Body Mass Index (BMI).

    Args:
        weight_kg (float): Weight in kilograms.
        height_m (float): Height in metres.

    Returns:
        float: BMI value rounded to 2 decimal places.

    Raises:
        ValueError: If weight or height is non-positive.

    Example:
        >>> calculate_bmi(70, 1.75)
        22.86
    """
    if weight_kg <= 0 or height_m <= 0:
        raise ValueError("Weight and height must be positive")
    return round(weight_kg / (height_m ** 2), 2)

# Access docstring
print(calculate_bmi.__doc__)
help(calculate_bmi)

# Module docstring — at top of file
"""
mymodule.py
Utility functions for Webortex project.
Author: Sisi
"""

# Docstring formats:
# Google style (above example)
# NumPy style
# reStructuredText (Sphinx)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 24. What is the difference between del, remove(), and pop()?

| Method | Operates by | Returns | Raises if not found |
| ------ | ----------- | ------- | ------------------- |
| `del lst[i]` | Index | Nothing | `IndexError` |
| `lst.remove(val)` | Value | Nothing | `ValueError` |
| `lst.pop(i)` | Index (default: last) | Removed element | `IndexError` |
| `del variable` | Variable name | Nothing | `NameError` |

```python
lst = [10, 20, 30, 40, 50]

# del — delete by index or slice
del lst[1]          # removes 20 (index 1)
print(lst)          # [10, 30, 40, 50]

del lst[1:3]        # removes 30, 40 (slice)
print(lst)          # [10, 50]

# remove() — delete by value (first occurrence)
lst = [10, 20, 30, 20, 40]
lst.remove(20)      # removes first occurrence of 20
print(lst)          # [10, 30, 20, 40]

# pop() — delete by index, returns the element
lst = [10, 20, 30, 40]
removed = lst.pop()    # removes last element (50 default)
print(removed)         # 40
print(lst)             # [10, 20, 30]

removed = lst.pop(0)   # removes element at index 0
print(removed)         # 10
print(lst)             # [20, 30]

# del on variable — unbinds the name
x = 42
del x
# print(x)  # NameError: name 'x' is not defined
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 25. What is type casting in Python?

Type casting is **explicitly converting one data type to another** using built-in conversion functions.

```python
# int() — convert to integer
print(int("42"))      # 42
print(int(3.9))       # 3  (truncates, doesn't round!)
print(int("0xFF", 16))# 255 (hex string to int)
print(int("0b1010", 2))# 10 (binary string to int)

# float() — convert to float
print(float("3.14"))  # 3.14
print(float(5))       # 5.0

# str() — convert to string
print(str(42))        # "42"
print(str(3.14))      # "3.14"
print(str(True))      # "True"

# bool() — convert to boolean
# Falsy: 0, 0.0, "", [], {}, (), set(), None
print(bool(0))        # False
print(bool(""))       # False
print(bool([]))       # False
print(bool(1))        # True
print(bool("hi"))     # True
print(bool([0]))      # True (non-empty list)

# list(), tuple(), set() — convert sequences
s = "hello"
print(list(s))        # ['h', 'e', 'l', 'l', 'o']
print(tuple([1,2,3])) # (1, 2, 3)
print(set([1,2,2,3])) # {1, 2, 3}

# dict() — from key-value pairs
pairs = [("a", 1), ("b", 2)]
print(dict(pairs))    # {'a': 1, 'b': 2}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — OOP in Python

<br>

### 26. What are the four pillars of OOP in Python?

| Pillar | Definition | Python feature |
| ------ | ---------- | -------------- |
| **Encapsulation** | Bundling data + methods, hiding internal state | `_protected`, `__private`, `@property` |
| **Abstraction** | Hiding implementation details, showing only interface | Abstract classes (`ABC`), methods |
| **Inheritance** | Child class inherits attributes/methods from parent | `class Child(Parent)` |
| **Polymorphism** | Same interface, different behaviour | Method overriding, duck typing |

```python
from abc import ABC, abstractmethod

# Abstraction + Encapsulation
class Shape(ABC):              # Abstract base class
    @abstractmethod
    def area(self):            # Forces subclasses to implement
        pass

    @abstractmethod
    def perimeter(self):
        pass

# Inheritance + Polymorphism
class Circle(Shape):
    def __init__(self, radius):
        self.__radius = radius  # Encapsulation — private attribute

    @property
    def radius(self):           # Controlled access via property
        return self.__radius

    def area(self):             # Polymorphism — own implementation
        return 3.14159 * self.__radius ** 2

    def perimeter(self):
        return 2 * 3.14159 * self.__radius

class Rectangle(Shape):
    def __init__(self, w, h):
        self.__width = w
        self.__height = h

    def area(self):             # Same interface, different behavior
        return self.__width * self.__height

    def perimeter(self):
        return 2 * (self.__width + self.__height)

shapes = [Circle(5), Rectangle(4, 6)]
for shape in shapes:
    print(f"Area: {shape.area():.2f}")  # Polymorphism in action
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 27. What is the difference between a class and an object?

| Concept | Description |
| ------- | ----------- |
| **Class** | Blueprint/template that defines attributes and methods |
| **Object** | A specific instance created from a class |

```python
# Class — blueprint
class Dog:
    # Class variable — shared by ALL instances
    species = "Canis familiaris"

    def __init__(self, name, breed, age):
        # Instance variables — unique to each object
        self.name = name
        self.breed = breed
        self.age = age

    def bark(self):
        return f"{self.name} says: Woof!"

    def __repr__(self):
        return f"Dog(name='{self.name}', breed='{self.breed}', age={self.age})"

# Objects — instances of the class
dog1 = Dog("Bruno", "Labrador", 3)
dog2 = Dog("Max", "Poodle", 5)

print(dog1.name)      # Bruno
print(dog2.name)      # Max
print(dog1.species)   # Canis familiaris (class variable — shared)
print(dog2.species)   # Canis familiaris

print(dog1.bark())    # Bruno says: Woof!
print(dog1)           # Dog(name='Bruno', breed='Labrador', age=3)

# type() and isinstance()
print(type(dog1))               # <class '__main__.Dog'>
print(isinstance(dog1, Dog))   # True
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 28. What is __init__? Is it a constructor?

`__init__` is Python's **initializer method** — called automatically after an object is created to set up its initial state. It's often called a constructor, but technically `__new__` creates the object and `__init__` initializes it.

```python
class Person:
    # Class variable
    count = 0

    def __init__(self, name, age, email=None):
        # Instance initialization
        self.name = name
        self.age = age
        self.email = email
        Person.count += 1           # track how many people created
        print(f"Person created: {self.name}")

    def __del__(self):              # destructor — called when object is garbage collected
        Person.count -= 1
        print(f"Person deleted: {self.name}")

p1 = Person("Sisi", 20, "sisi@webortex.com")  # Person created: Sisi
p2 = Person("Yamini", 22)                      # Person created: Yamini
print(Person.count)   # 2

del p1                # Person deleted: Sisi
print(Person.count)   # 1

# __init__ can call super() for parent initialization
class Employee(Person):
    def __init__(self, name, age, company):
        super().__init__(name, age)   # initialize parent
        self.company = company

emp = Employee("Sisi", 20, "Webortex")
print(emp.name, emp.company)  # Sisi Webortex
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 29. What is the difference between __str__ and __repr__?

| Method | Purpose | Called by |
| ------ | ------- | --------- |
| `__str__` | Human-readable string (for end users) | `print()`, `str()` |
| `__repr__` | Developer-readable, unambiguous (for debugging) | `repr()`, interactive console, `!r` in f-strings |

```python
class Product:
    def __init__(self, name, price):
        self.name = name
        self.price = price

    def __str__(self):
        return f"{self.name} — ₹{self.price}"   # readable for users

    def __repr__(self):
        return f"Product(name='{self.name}', price={self.price})"  # debug-friendly

p = Product("Laptop", 50000)

print(p)          # Product.__str__: "Laptop — ₹50000"
print(str(p))     # "Laptop — ₹50000"
print(repr(p))    # "Product(name='Laptop', price=50000)"
print(f"{p}")     # "Laptop — ₹50000"  (uses __str__)
print(f"{p!r}")   # "Product(name='Laptop', price=50000)"  (forces __repr__)

# If only __repr__ defined — used for both str() and repr()
# If only __str__ defined — repr() falls back to default "<__main__.Product object at 0x...>"
# Best practice: always define __repr__; define __str__ if user-facing output needed
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 30. What is the difference between instance, class, and static methods?

| Method type | First parameter | Access to | Use case |
| ----------- | --------------- | --------- | -------- |
| **Instance method** | `self` | Instance + Class data | Most common — works with object data |
| **Class method** | `cls` | Class data only | Factory methods, alternative constructors |
| **Static method** | None | Nothing via implicit param | Utility functions logically related to class |

```python
class Temperature:
    unit = "Celsius"   # class variable

    def __init__(self, value):
        self.value = value   # instance variable

    # Instance method — has access to self (instance)
    def to_fahrenheit(self):
        return (self.value * 9/5) + 32

    # Class method — has access to cls (class itself)
    @classmethod
    def from_fahrenheit(cls, f_value):
        celsius = (f_value - 32) * 5/9
        return cls(celsius)   # creates new instance

    @classmethod
    def change_unit(cls, new_unit):
        cls.unit = new_unit   # modifies class variable

    # Static method — no access to self or cls
    @staticmethod
    def is_valid(value):
        return -273.15 <= value   # absolute zero check

t1 = Temperature(100)
print(t1.to_fahrenheit())         # 212.0 — instance method

t2 = Temperature.from_fahrenheit(212)  # class method used as factory
print(t2.value)                   # 100.0

print(Temperature.is_valid(-300)) # False — static method
print(Temperature.is_valid(25))   # True
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 31. What is inheritance in Python? What are its types?

Inheritance allows a **child class to inherit attributes and methods from a parent class**, enabling code reuse and extension.

```python
# Single Inheritance
class Animal:
    def __init__(self, name):
        self.name = name
    def speak(self):
        return "..."

class Dog(Animal):
    def speak(self):        # overrides parent method
        return f"{self.name} says Woof!"

# Multi-level Inheritance
class GuideDog(Dog):        # GuideDog → Dog → Animal
    def guide(self):
        return f"{self.name} is guiding its owner"

# Multiple Inheritance
class Flyable:
    def fly(self):
        return "I can fly"

class Swimmable:
    def swim(self):
        return "I can swim"

class Duck(Animal, Flyable, Swimmable):  # inherits from both
    def speak(self):
        return f"{self.name} says Quack!"

d = Duck("Donald")
print(d.speak())    # Donald says Quack!
print(d.fly())      # I can fly
print(d.swim())     # I can swim

# Hierarchical Inheritance — multiple children, one parent
class Cat(Animal):
    def speak(self):
        return f"{self.name} says Meow!"

# Check inheritance
print(issubclass(Dog, Animal))    # True
print(issubclass(Cat, Dog))       # False
print(isinstance(d, Animal))      # True (Duck inherits Animal)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 32. What is MRO (Method Resolution Order)?

MRO determines the **order in which Python searches classes** for a method or attribute in case of multiple inheritance. Python uses the **C3 linearization algorithm**.

```python
class A:
    def method(self):
        return "A"

class B(A):
    def method(self):
        return "B"

class C(A):
    def method(self):
        return "C"

class D(B, C):   # Multiple inheritance — diamond problem
    pass

d = D()
print(d.method())          # "B" — follows MRO

# View MRO
print(D.__mro__)
# (<class 'D'>, <class 'B'>, <class 'C'>, <class 'A'>, <class 'object'>)
print(D.mro())
# [D, B, C, A, object]

# MRO rule (C3 linearization):
# Search order: D → B → C → A → object
# Python checks left-to-right in inheritance list, then goes up

class E(B, C):
    def method(self):
        return "E + " + super().method()  # super() follows MRO

e = E()
print(e.method())  # "E + B" — super() calls B.method() (next in MRO)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 33. What is polymorphism in Python?

Polymorphism means **"many forms"** — the same interface (method name) behaves differently for different objects.

```python
# Method overriding — runtime polymorphism
class Shape:
    def area(self):
        raise NotImplementedError

class Circle(Shape):
    def __init__(self, r): self.r = r
    def area(self): return 3.14 * self.r ** 2

class Rectangle(Shape):
    def __init__(self, w, h): self.w, self.h = w, h
    def area(self): return self.w * self.h

class Triangle(Shape):
    def __init__(self, b, h): self.b, self.h = b, h
    def area(self): return 0.5 * self.b * self.h

shapes = [Circle(5), Rectangle(4, 6), Triangle(3, 8)]

# Same method call — different behavior per object
for shape in shapes:
    print(f"{type(shape).__name__}: area = {shape.area():.2f}")

# Duck typing — polymorphism without inheritance
class Dog:
    def speak(self): return "Woof!"

class Cat:
    def speak(self): return "Meow!"

class Robot:
    def speak(self): return "Beep Boop!"

# Any object with a speak() method works here
def make_noise(animal):
    print(animal.speak())

for entity in [Dog(), Cat(), Robot()]:
    make_noise(entity)   # works for all — duck typing

# Operator overloading — polymorphism with operators
class Vector:
    def __init__(self, x, y): self.x, self.y = x, y
    def __add__(self, other):
        return Vector(self.x + other.x, self.y + other.y)
    def __repr__(self):
        return f"Vector({self.x}, {self.y})"

v1 = Vector(1, 2)
v2 = Vector(3, 4)
print(v1 + v2)   # Vector(4, 6) — + operator overloaded
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 34. What is encapsulation in Python?

Encapsulation is **bundling data (attributes) and methods together**, and restricting direct access to internal implementation details.

```python
class BankAccount:
    def __init__(self, owner, initial_balance=0):
        self.owner = owner                    # public
        self._account_number = "1234567890"  # protected (convention — don't access outside)
        self.__balance = initial_balance     # private (name-mangled to _BankAccount__balance)

    # Public interface — controlled access to private data
    @property
    def balance(self):
        return self.__balance

    def deposit(self, amount):
        if amount <= 0:
            raise ValueError("Deposit amount must be positive")
        self.__balance += amount
        print(f"Deposited ₹{amount}. New balance: ₹{self.__balance}")

    def withdraw(self, amount):
        if amount <= 0:
            raise ValueError("Withdrawal amount must be positive")
        if amount > self.__balance:
            raise ValueError("Insufficient funds")
        self.__balance -= amount
        print(f"Withdrawn ₹{amount}. New balance: ₹{self.__balance}")

acc = BankAccount("Sisi", 10000)
print(acc.owner)         # Sisi — public
print(acc.balance)       # 10000 — via property (read-only)
acc.deposit(5000)        # controlled modification
acc.withdraw(2000)

# Cannot access private directly:
# print(acc.__balance)   # AttributeError
print(acc._BankAccount__balance)  # 13000 — name mangling (accessible but discouraged)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 35. What are dunder (magic) methods in Python?

Dunder (double underscore) methods are **special methods** with `__name__` format that Python calls implicitly for built-in operations.

```python
class Book:
    def __init__(self, title, author, pages):
        self.title = title
        self.author = author
        self.pages = pages

    def __str__(self):          # print(book)
        return f"'{self.title}' by {self.author}"

    def __repr__(self):         # repr(book), interactive console
        return f"Book('{self.title}', '{self.author}', {self.pages})"

    def __len__(self):          # len(book)
        return self.pages

    def __lt__(self, other):    # book1 < book2 (comparison)
        return self.pages < other.pages

    def __eq__(self, other):    # book1 == book2
        return self.title == other.title and self.author == other.author

    def __add__(self, other):   # book1 + book2 (custom behavior)
        return Book(f"{self.title} & {other.title}", "Various", self.pages + other.pages)

    def __contains__(self, item): # 'Python' in book
        return item.lower() in self.title.lower()

    def __getitem__(self, key): # book[key]
        return getattr(self, key)

    def __call__(self, discount):  # book(0.1) — make object callable
        return self.pages * (1 - discount)

b1 = Book("Python Basics", "Sisi", 300)
b2 = Book("Advanced Python", "Yamini", 450)

print(b1)              # 'Python Basics' by Sisi
print(len(b1))         # 300
print(b1 < b2)         # True (300 < 450)
print("Python" in b1)  # True
print(b1["title"])     # Python Basics
print(b1(0.1))         # 270.0 (callable)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 36. What is the difference between __new__ and __init__?

| Method | Role | When called | Returns |
| ------ | ---- | ----------- | ------- |
| `__new__` | Creates the instance (allocates memory) | Before `__init__` | New instance |
| `__init__` | Initializes the created instance | After `__new__` | `None` |

```python
class MyClass:
    def __new__(cls, *args, **kwargs):
        print(f"1. __new__ called — creating instance of {cls.__name__}")
        instance = super().__new__(cls)   # allocate and return new instance
        return instance

    def __init__(self, value):
        print(f"2. __init__ called — initializing with {value}")
        self.value = value

obj = MyClass(42)
# Output:
# 1. __new__ called — creating instance of MyClass
# 2. __init__ called — initializing with 42

# Real use case: Singleton pattern using __new__
class Singleton:
    _instance = None

    def __new__(cls):
        if cls._instance is None:
            cls._instance = super().__new__(cls)
        return cls._instance     # always returns same instance

s1 = Singleton()
s2 = Singleton()
print(s1 is s2)   # True — same object

# Subclassing immutable types uses __new__
class PositiveInt(int):
    def __new__(cls, value):
        if value <= 0:
            raise ValueError("Must be positive")
        return super().__new__(cls, value)

n = PositiveInt(5)
print(n, type(n))   # 5 <class '__main__.PositiveInt'>
# PositiveInt(-1)   # ValueError
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 37. What is duck typing in Python?

Duck typing is a programming concept: **"If it walks like a duck and quacks like a duck, it's a duck."** In Python, the type/class of an object matters less than whether it has the required methods and attributes.

```python
# No inheritance required — just needs the right method
class Dog:
    def speak(self): return "Woof!"

class Cat:
    def speak(self): return "Meow!"

class Person:
    def speak(self): return "Hello!"

def make_sound(entity):
    # Doesn't check type — just calls speak()
    print(entity.speak())

# Works for all — duck typing
for obj in [Dog(), Cat(), Person()]:
    make_sound(obj)

# File-like objects — duck typing in standard library
class StringIO_Custom:
    def __init__(self, text):
        self._data = text
        self._pos = 0

    def read(self):          # acts like a file
        return self._data

    def write(self, text):   # acts like a file
        self._data += text

def process_file(file_obj):
    print(file_obj.read())   # works with any file-like object

import io
process_file(io.StringIO("from StringIO"))   # standard StringIO
process_file(StringIO_Custom("from custom")) # custom class — duck typing
# process_file(open("data.txt"))             # real file — also works

# EAFP vs LBYL
# LBYL: Look Before You Leap (type checking — non-Pythonic)
def process_lbyl(obj):
    if hasattr(obj, 'read'):
        return obj.read()

# EAFP: Easier to Ask Forgiveness than Permission (Pythonic — duck typing)
def process_eafp(obj):
    try:
        return obj.read()
    except AttributeError:
        raise TypeError(f"{type(obj)} is not file-like")
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 38. What are abstract classes and interfaces in Python?

An **abstract class** is a class that cannot be instantiated directly — it defines a contract that subclasses must fulfill by implementing abstract methods.

```python
from abc import ABC, abstractmethod

class Vehicle(ABC):    # Abstract Base Class
    def __init__(self, brand, model):
        self.brand = brand
        self.model = model

    @abstractmethod
    def start_engine(self):      # must be implemented by subclass
        pass

    @abstractmethod
    def fuel_type(self):
        pass

    def info(self):              # concrete method — subclasses inherit this
        return f"{self.brand} {self.model}"

class Car(Vehicle):
    def start_engine(self):
        return "Vroom! Petrol engine started."

    def fuel_type(self):
        return "Petrol"

class ElectricCar(Vehicle):
    def start_engine(self):
        return "Whirr... Electric motor activated."

    def fuel_type(self):
        return "Electric"

# vehicle = Vehicle("X", "Y")  # TypeError: Can't instantiate abstract class

car = Car("Toyota", "Camry")
ev  = ElectricCar("Tesla", "Model 3")

print(car.start_engine())    # Vroom! Petrol engine started.
print(ev.fuel_type())        # Electric
print(ev.info())             # Tesla Model 3

# Abstract properties
class Shape(ABC):
    @property
    @abstractmethod
    def area(self):
        pass

class Square(Shape):
    def __init__(self, side):
        self._side = side

    @property
    def area(self):
        return self._side ** 2

s = Square(5)
print(s.area)   # 25
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 39. What is the super() function?

`super()` returns a **proxy object that delegates method calls to the parent class** — used to call parent's methods without hardcoding the class name.

```python
class Animal:
    def __init__(self, name, age):
        self.name = name
        self.age = age
        print(f"Animal.__init__: {name}")

    def describe(self):
        return f"Name: {self.name}, Age: {self.age}"

class Dog(Animal):
    def __init__(self, name, age, breed):
        super().__init__(name, age)   # calls Animal.__init__
        self.breed = breed
        print(f"Dog.__init__: {breed}")

    def describe(self):
        base = super().describe()     # calls Animal.describe()
        return f"{base}, Breed: {self.breed}"

class GuideDog(Dog):
    def __init__(self, name, age, breed, owner):
        super().__init__(name, age, breed)  # calls Dog.__init__ (which calls Animal.__init__)
        self.owner = owner

    def describe(self):
        base = super().describe()           # calls Dog.describe()
        return f"{base}, Owner: {self.owner}"

gd = GuideDog("Bruno", 3, "Labrador", "Sisi")
print(gd.describe())
# Name: Bruno, Age: 3, Breed: Labrador, Owner: Sisi

# super() in multiple inheritance follows MRO
class A:
    def method(self): return "A"

class B(A):
    def method(self): return f"B → {super().method()}"

class C(A):
    def method(self): return f"C → {super().method()}"

class D(B, C):
    def method(self): return f"D → {super().method()}"

print(D().method())  # D → B → C → A
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 40. What are dataclasses in Python?

Dataclasses (Python 3.7+) **automatically generate boilerplate methods** (`__init__`, `__repr__`, `__eq__`) for classes that mainly store data.

```python
from dataclasses import dataclass, field, asdict, astuple
from typing import List

# Without dataclass — lots of boilerplate
class ProductManual:
    def __init__(self, name, price, category, tags):
        self.name = name
        self.price = price
        self.category = category
        self.tags = tags
    def __repr__(self): ...
    def __eq__(self, other): ...

# With @dataclass — clean and concise
@dataclass
class Product:
    name: str
    price: float
    category: str
    tags: List[str] = field(default_factory=list)  # mutable default
    in_stock: bool = True

    def discounted_price(self, discount: float) -> float:
        return self.price * (1 - discount)

p1 = Product("Laptop", 50000.0, "Electronics", ["tech", "portable"])
p2 = Product("Laptop", 50000.0, "Electronics", ["tech", "portable"])

print(p1)               # Product(name='Laptop', price=50000.0, ...)  — auto __repr__
print(p1 == p2)         # True — auto __eq__ compares field values
print(p1.discounted_price(0.1))  # 45000.0

# Convert to dict or tuple
print(asdict(p1))       # {'name': 'Laptop', 'price': 50000.0, ...}
print(astuple(p1))      # ('Laptop', 50000.0, 'Electronics', ...)

# frozen=True — makes dataclass immutable (hashable)
@dataclass(frozen=True)
class Point:
    x: float
    y: float

pt = Point(1.0, 2.0)
# pt.x = 5.0  # FrozenInstanceError
print(hash(pt))    # hashable because frozen
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Functions, Decorators & Generators

<br>

### 41. What are closures in Python?

A closure is a **function that remembers variables from its enclosing scope** even after the outer function has finished executing.

```python
# Basic closure
def make_multiplier(factor):
    # `factor` is captured by the inner function
    def multiplier(number):
        return number * factor   # accesses `factor` from enclosing scope
    return multiplier

double = make_multiplier(2)
triple = make_multiplier(3)

print(double(5))    # 10 — `factor` = 2, still remembered
print(triple(5))    # 15 — `factor` = 3, still remembered
print(double.__closure__[0].cell_contents)  # 2 — inspect closure variable

# Closure with state — simple counter
def make_counter(start=0, step=1):
    count = [start]   # list to allow mutation in closure
    def counter():
        count[0] += step
        return count[0]
    return counter

counter = make_counter(0, 5)
print(counter())  # 5
print(counter())  # 10
print(counter())  # 15

# Real-world: decorator factories, callbacks, partial application
def logger(prefix):
    def log(message):
        print(f"[{prefix}] {message}")
    return log

info  = logger("INFO")
error = logger("ERROR")

info("Server started")         # [INFO] Server started
error("Connection refused")    # [ERROR] Connection refused
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 42. What are decorators in Python? How do they work?

A decorator is a **function that takes another function as input, wraps it with additional behaviour, and returns the enhanced function** — without modifying the original function's source code.

```python
import time
import functools

# Step by step: what @decorator actually does
def my_decorator(func):
    @functools.wraps(func)    # preserve original function metadata
    def wrapper(*args, **kwargs):
        print("Before function runs")
        result = func(*args, **kwargs)   # call original function
        print("After function runs")
        return result
    return wrapper

# Using decorator syntax
@my_decorator
def greet(name):
    print(f"Hello, {name}!")

# Equivalent to: greet = my_decorator(greet)
greet("Sisi")
# Before function runs
# Hello, Sisi!
# After function runs

# Real-world decorators
# 1. Timer decorator
def timer(func):
    @functools.wraps(func)
    def wrapper(*args, **kwargs):
        start = time.perf_counter()
        result = func(*args, **kwargs)
        end = time.perf_counter()
        print(f"{func.__name__} took {end - start:.4f}s")
        return result
    return wrapper

# 2. Retry decorator
def retry(max_attempts=3):
    def decorator(func):
        @functools.wraps(func)
        def wrapper(*args, **kwargs):
            for attempt in range(1, max_attempts + 1):
                try:
                    return func(*args, **kwargs)
                except Exception as e:
                    print(f"Attempt {attempt} failed: {e}")
                    if attempt == max_attempts:
                        raise
        return wrapper
    return decorator

# Stacking decorators — applied bottom-up
@timer
@retry(max_attempts=3)
def fetch_data(url):
    # ...
    pass
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 43. How do you write a decorator with arguments?

A decorator with arguments needs **three levels of nesting**: outer function (receives args) → decorator (receives function) → wrapper (receives function arguments).

```python
import functools

# Decorator with arguments — 3 layers
def repeat(times):               # level 1: accepts decorator arguments
    def decorator(func):         # level 2: accepts the function
        @functools.wraps(func)
        def wrapper(*args, **kwargs):  # level 3: wraps the function
            for _ in range(times):
                result = func(*args, **kwargs)
            return result
        return wrapper
    return decorator

@repeat(3)
def greet(name):
    print(f"Hello, {name}!")

greet("Sisi")
# Hello, Sisi!
# Hello, Sisi!
# Hello, Sisi!

# Decorator with validation
def validate_types(**type_map):
    def decorator(func):
        @functools.wraps(func)
        def wrapper(*args, **kwargs):
            import inspect
            sig = inspect.signature(func)
            bound = sig.bind(*args, **kwargs)
            for param, value in bound.arguments.items():
                if param in type_map and not isinstance(value, type_map[param]):
                    raise TypeError(f"'{param}' must be {type_map[param].__name__}, got {type(value).__name__}")
            return func(*args, **kwargs)
        return wrapper
    return decorator

@validate_types(name=str, age=int)
def register(name, age):
    print(f"Registered: {name}, age {age}")

register("Sisi", 20)      # OK
# register("Sisi", "20") # TypeError: 'age' must be int, got str

# Class-based decorator (alternative to 3-level nesting)
class Retry:
    def __init__(self, max_attempts=3, exceptions=(Exception,)):
        self.max_attempts = max_attempts
        self.exceptions = exceptions

    def __call__(self, func):
        @functools.wraps(func)
        def wrapper(*args, **kwargs):
            for attempt in range(self.max_attempts):
                try:
                    return func(*args, **kwargs)
                except self.exceptions as e:
                    if attempt == self.max_attempts - 1:
                        raise
            return None
        return wrapper

@Retry(max_attempts=5, exceptions=(ConnectionError, TimeoutError))
def connect_to_api():
    pass
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 44. What are generators in Python?

Generators are **functions that use `yield` to produce values one at a time** — pausing execution between each yield. They are memory-efficient for large sequences.

```python
# Regular function — builds entire list in memory
def get_squares_list(n):
    return [x**2 for x in range(n)]   # all n values stored at once

# Generator — produces values one at a time (lazy evaluation)
def get_squares_gen(n):
    for x in range(n):
        yield x**2           # pauses here, resumes on next()

# Memory comparison
import sys
lst = get_squares_list(1_000_000)
gen = get_squares_gen(1_000_000)
print(sys.getsizeof(lst))    # ~8MB
print(sys.getsizeof(gen))    # ~128 bytes!

# Using a generator
gen = get_squares_gen(5)
print(next(gen))    # 0
print(next(gen))    # 1
print(next(gen))    # 4
# ...
# StopIteration raised after last value

# Iterate with for loop
for sq in get_squares_gen(5):
    print(sq)       # 0, 1, 4, 9, 16

# Infinite generator (impossible with a list)
def fibonacci():
    a, b = 0, 1
    while True:         # infinite sequence!
        yield a
        a, b = b, a + b

fib = fibonacci()
for _ in range(10):
    print(next(fib), end=" ")   # 0 1 1 2 3 5 8 13 21 34

# Generator with send() — send values back into generator
def accumulator():
    total = 0
    while True:
        value = yield total    # yield sends total out, receives value back
        if value is None:
            break
        total += value

acc = accumulator()
next(acc)             # prime the generator (advance to first yield)
print(acc.send(10))   # 10
print(acc.send(5))    # 15
print(acc.send(20))   # 35
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 45. What is the difference between yield and return?

| Feature | `return` | `yield` |
| ------- | -------- | ------- |
| Function type | Regular function | Generator function |
| Execution after | Terminates function | Suspends, resumes on `next()` |
| Multiple values | ❌ Returns once | ✅ Can yield many times |
| Memory | Stores all at once | Lazy — one at a time |
| State retained? | ❌ No | ✅ Yes — local variables preserved |

```python
# return — terminates function, returns value
def get_all_numbers(n):
    return list(range(n))   # creates and returns entire list

result = get_all_numbers(5)
print(result)   # [0, 1, 2, 3, 4]

# yield — suspends function, returns value lazily
def generate_numbers(n):
    for i in range(n):
        print(f"  Generating {i}")
        yield i            # pause here, return i, resume on next()
    print("  Generator exhausted")

gen = generate_numbers(3)
print("Before first next()")
print(next(gen))    # Generating 0 → 0
print(next(gen))    # Generating 1 → 1
print(next(gen))    # Generating 2 → 2
# next(gen)         # StopIteration

# yield from — delegate to another generator
def flatten(nested):
    for item in nested:
        if isinstance(item, list):
            yield from flatten(item)   # delegate to recursive call
        else:
            yield item

nested = [1, [2, 3, [4, 5]], 6]
print(list(flatten(nested)))   # [1, 2, 3, 4, 5, 6]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 46. What is a generator expression?

A generator expression is a **concise, one-line generator** using the same syntax as list comprehensions, but with **parentheses** instead of square brackets. It's lazy — values computed on demand.

```python
import sys

# List comprehension — eager, all in memory
list_comp = [x**2 for x in range(1_000_000)]
print(sys.getsizeof(list_comp))   # ~8MB

# Generator expression — lazy, one value at a time
gen_exp = (x**2 for x in range(1_000_000))
print(sys.getsizeof(gen_exp))     # ~112 bytes!

# Use in sum, max, any, all — no intermediate list needed
total = sum(x**2 for x in range(100))     # sum consumes generator
print(total)   # 328350

max_val = max(x**2 for x in range(10))
print(max_val) # 81

# Generator expression with condition
evens_squared = (x**2 for x in range(20) if x % 2 == 0)
print(list(evens_squared))   # [0, 4, 16, 36, 64, 100, 144, 196, 256, 324]

# Chaining generators (pipeline — each processes lazily)
numbers = range(1_000_000)
squared = (x**2 for x in numbers)
even_squares = (x for x in squared if x % 2 == 0)
first_five = list(next(even_squares) for _ in range(5))
print(first_five)   # [0, 4, 16, 36, 64]
# All lazy — only computes what's needed!
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 47. What is the difference between an iterator and an iterable?

| Concept | Definition | Has method | Example |
| ------- | ---------- | ---------- | ------- |
| **Iterable** | Object that can be iterated over | `__iter__()` | `list`, `str`, `dict`, `set`, `range` |
| **Iterator** | Object that produces values one at a time | `__iter__()` + `__next__()` | `iter(list)`, generator, file object |

```python
# Iterable — can be passed to iter()
my_list = [1, 2, 3]           # iterable
print(hasattr(my_list, '__iter__'))   # True
print(hasattr(my_list, '__next__'))   # False — NOT an iterator

# Iterator — obtained from iter()
my_iter = iter(my_list)        # creates iterator from iterable
print(hasattr(my_iter, '__iter__'))   # True
print(hasattr(my_iter, '__next__'))   # True — IS an iterator

print(next(my_iter))  # 1
print(next(my_iter))  # 2
print(next(my_iter))  # 3
# next(my_iter)        # StopIteration

# For loop uses this protocol internally:
# for x in my_list:
#     ...
# Is equivalent to:
# _iter = iter(my_list)
# while True:
#     try:
#         x = next(_iter)
#         ...
#     except StopIteration:
#         break

# Custom iterator class
class CountDown:
    def __init__(self, start):
        self.start = start

    def __iter__(self):    # makes it an iterable
        return self        # returns self (since it's also an iterator)

    def __next__(self):    # makes it an iterator
        if self.start < 0:
            raise StopIteration
        value = self.start
        self.start -= 1
        return value

for n in CountDown(5):
    print(n)   # 5, 4, 3, 2, 1, 0
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 48. What are context managers? How does the with statement work?

A context manager **manages resources** by defining setup (`__enter__`) and teardown (`__exit__`) logic — ensuring cleanup always happens even if an exception occurs.

```python
# with statement — calls __enter__ and __exit__ automatically
with open("data.txt", "w") as f:
    f.write("Hello, Sisi!")
# File automatically closed after block — even if exception occurs

# Equivalent without `with`:
f = open("data.txt", "w")
try:
    f.write("Hello, Sisi!")
finally:
    f.close()

# Custom context manager — class-based
class DatabaseConnection:
    def __init__(self, host, db_name):
        self.host = host
        self.db_name = db_name
        self.connection = None

    def __enter__(self):
        print(f"Connecting to {self.db_name} at {self.host}...")
        self.connection = "mock_connection"  # simulate connection
        return self.connection  # value assigned to `as` variable

    def __exit__(self, exc_type, exc_value, traceback):
        print("Closing connection...")
        self.connection = None
        if exc_type:
            print(f"Exception occurred: {exc_value}")
        return False   # False = don't suppress exceptions; True = suppress

with DatabaseConnection("localhost", "mydb") as conn:
    print(f"Using connection: {conn}")
    # raises exception here → __exit__ still called

# Custom context manager — using @contextmanager (simpler)
from contextlib import contextmanager

@contextmanager
def timer(label):
    import time
    start = time.perf_counter()
    try:
        yield   # code inside `with` block runs here
    finally:
        end = time.perf_counter()
        print(f"{label} took {end - start:.4f}s")

with timer("Data processing"):
    result = sum(range(1_000_000))
# Data processing took 0.0234s
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 49. What is functools.wraps and why is it important?

`functools.wraps` is a decorator that **copies the original function's metadata** (`__name__`, `__doc__`, `__module__`, etc.) to the wrapper function — preserving the original function's identity.

```python
import functools

# Without functools.wraps — metadata is lost
def bad_decorator(func):
    def wrapper(*args, **kwargs):
        """Wrapper docstring"""
        return func(*args, **kwargs)
    return wrapper

@bad_decorator
def greet(name):
    """Greet a person by name."""
    return f"Hello, {name}!"

print(greet.__name__)   # "wrapper" — wrong!
print(greet.__doc__)    # "Wrapper docstring" — wrong!

# With functools.wraps — metadata preserved
def good_decorator(func):
    @functools.wraps(func)   # copies metadata from func to wrapper
    def wrapper(*args, **kwargs):
        """Wrapper docstring"""
        return func(*args, **kwargs)
    return wrapper

@good_decorator
def greet(name):
    """Greet a person by name."""
    return f"Hello, {name}!"

print(greet.__name__)    # "greet" — correct!
print(greet.__doc__)     # "Greet a person by name." — correct!
print(greet.__wrapped__) # original function — accessible via __wrapped__

# Why it matters:
# 1. Debugging — stack traces show correct function names
# 2. Documentation — help() shows correct docstrings
# 3. Introspection — inspect module works correctly
# 4. Testing — mock patching and assertions use __name__
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 50. What is memoization? How do you implement it in Python?

Memoization is a **caching technique** that stores the results of expensive function calls and returns the cached result when the same inputs occur again — trading memory for speed.

```python
import functools
import time

# Manual memoization
def memoize(func):
    cache = {}
    @functools.wraps(func)
    def wrapper(*args):
        if args not in cache:
            cache[args] = func(*args)
        return cache[args]
    return wrapper

@memoize
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n - 1) + fibonacci(n - 2)

print(fibonacci(50))   # instant — vs exponential without memoization

# Built-in: functools.lru_cache — Least Recently Used cache
@functools.lru_cache(maxsize=128)   # caches up to 128 unique calls
def expensive_calculation(n):
    time.sleep(0.1)   # simulate slow computation
    return n ** 2

print(expensive_calculation(10))   # slow (0.1s)
print(expensive_calculation(10))   # instant — cache hit!
print(expensive_calculation(20))   # slow again — new argument

print(expensive_calculation.cache_info())
# CacheInfo(hits=1, misses=2, maxsize=128, currsize=2)

expensive_calculation.cache_clear()  # clear cache

# functools.cache (Python 3.9+) — unlimited cache size
@functools.cache
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)

print(fib(100))   # 354224848179261915075 — instant with cache
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — File Handling & Exceptions

<br>

### 51. How do you read and write files in Python?

```python
# Writing files
with open("output.txt", "w") as f:    # 'w' overwrites, 'a' appends
    f.write("Hello, Sisi!\n")
    f.writelines(["Line 1\n", "Line 2\n", "Line 3\n"])

# Reading files
with open("output.txt", "r") as f:
    content = f.read()             # entire file as string
    print(content)

with open("output.txt", "r") as f:
    lines = f.readlines()          # list of lines (with \n)
    print(lines)

with open("output.txt", "r") as f:
    for line in f:                 # iterate line by line (memory efficient)
        print(line.strip())

with open("output.txt", "r") as f:
    first_line = f.readline()      # read one line

# File modes:
# 'r'  — read (default)
# 'w'  — write (creates/overwrites)
# 'a'  — append (creates/adds to end)
# 'x'  — exclusive creation (fails if exists)
# 'rb' — read binary
# 'wb' — write binary
# 'r+' — read and write

# Using pathlib (modern approach — Python 3.4+)
from pathlib import Path

path = Path("data") / "output.txt"
path.parent.mkdir(parents=True, exist_ok=True)  # create directories

path.write_text("Hello from pathlib!")           # write
content = path.read_text()                       # read
print(path.exists())                             # True
print(path.stat().st_size)                       # file size in bytes
print(list(Path(".").glob("*.txt")))             # find all .txt files
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 52. How do you handle CSV and JSON files in Python?

```python
import csv
import json

# ── CSV ──
# Writing CSV
data = [
    ["Name", "Age", "City"],
    ["Sisi", 20, "Tirupati"],
    ["Yamini", 22, "Hyderabad"]
]

with open("users.csv", "w", newline="") as f:
    writer = csv.writer(f)
    writer.writerows(data)

# Reading CSV as rows
with open("users.csv", "r") as f:
    reader = csv.reader(f)
    for row in reader:
        print(row)

# Reading CSV as dicts (DictReader — preferred)
with open("users.csv", "r") as f:
    reader = csv.DictReader(f)   # uses header row as keys
    for row in reader:
        print(row["Name"], row["Age"])

# Writing CSV as dicts
users = [{"name": "Sisi", "age": 20}, {"name": "Yamini", "age": 22}]
with open("users2.csv", "w", newline="") as f:
    writer = csv.DictWriter(f, fieldnames=["name", "age"])
    writer.writeheader()
    writer.writerows(users)

# ── JSON ──
# Writing JSON
user = {"name": "Sisi", "age": 20, "skills": ["React", "Python"]}
with open("user.json", "w") as f:
    json.dump(user, f, indent=2)   # pretty-print with indent

# Reading JSON
with open("user.json", "r") as f:
    loaded = json.load(f)
    print(loaded["name"])          # Sisi
    print(type(loaded))            # dict

# JSON string ↔ Python object
json_str = json.dumps(user, indent=2)  # dict → JSON string
parsed  = json.loads(json_str)         # JSON string → dict

# Custom serialization (e.g., datetime)
from datetime import datetime
import json

class DateTimeEncoder(json.JSONEncoder):
    def default(self, obj):
        if isinstance(obj, datetime):
            return obj.isoformat()
        return super().default(obj)

data = {"created": datetime.now()}
print(json.dumps(data, cls=DateTimeEncoder))
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 53. What are custom exceptions in Python?

Custom exceptions are **user-defined exception classes** that inherit from `Exception` (or its subclasses) — allowing more specific error types for your application.

```python
# Base custom exception for your app
class AppError(Exception):
    """Base exception for the application."""
    def __init__(self, message, code=None):
        super().__init__(message)
        self.code = code

    def __str__(self):
        if self.code:
            return f"[Error {self.code}] {super().__str__()}"
        return super().__str__()

# Specific exceptions inheriting from AppError
class ValidationError(AppError):
    """Raised when input validation fails."""
    pass

class DatabaseError(AppError):
    """Raised when database operations fail."""
    pass

class AuthenticationError(AppError):
    """Raised when authentication fails."""
    def __init__(self, username):
        super().__init__(f"Authentication failed for user: {username}", code=401)
        self.username = username

class InsufficientFundsError(AppError):
    """Raised when account has insufficient funds."""
    def __init__(self, amount, balance):
        super().__init__(f"Cannot withdraw ₹{amount}. Balance: ₹{balance}", code=402)
        self.amount = amount
        self.balance = balance

# Usage
def withdraw(amount, balance):
    if amount <= 0:
        raise ValidationError("Withdrawal amount must be positive", code=400)
    if amount > balance:
        raise InsufficientFundsError(amount, balance)
    return balance - amount

try:
    result = withdraw(5000, 3000)
except InsufficientFundsError as e:
    print(e)              # [Error 402] Cannot withdraw ₹5000. Balance: ₹3000
    print(e.amount)       # 5000
    print(e.balance)      # 3000
except ValidationError as e:
    print(e)
except AppError as e:     # catches any AppError subclass
    print(f"App error: {e}")
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 54. What is the difference between raise and raise from in Python?

```python
# raise — re-raise current exception or raise new one
try:
    result = 1 / 0
except ZeroDivisionError:
    raise ValueError("Invalid operation")   # new exception, original context shown

# raise without argument — re-raises current exception
try:
    result = 1 / 0
except ZeroDivisionError:
    print("Logging the error...")
    raise   # re-raises ZeroDivisionError with original traceback

# raise ... from — explicit exception chaining
try:
    int("not_a_number")
except ValueError as e:
    raise RuntimeError("Config parsing failed") from e
# Shows: RuntimeError: Config parsing failed
#        The above exception was the direct cause of the following exception:

# raise ... from None — suppress exception chaining (hide original)
try:
    int("not_a_number")
except ValueError:
    raise ValueError("Invalid configuration value") from None
# Only shows: ValueError: Invalid configuration value
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 55. How do you use regular expressions in Python?

```python
import re

text = "Contact Sisi at sisi@webortex.com or call +91-9876543210"

# re.search() — find first match anywhere in string
match = re.search(r'\b\w+@\w+\.\w+\b', text)
if match:
    print(match.group())    # sisi@webortex.com

# re.match() — match only at the BEGINNING of string
m = re.match(r'Contact', text)
print(m.group() if m else "No match")  # Contact

# re.findall() — return all matches as list
emails = re.findall(r'[\w.+-]+@[\w-]+\.[\w.]+', text)
print(emails)   # ['sisi@webortex.com']

# re.finditer() — return iterator of match objects
for m in re.finditer(r'\d+', text):
    print(m.group(), m.start(), m.end())  # number, start pos, end pos

# re.sub() — substitute matches
cleaned = re.sub(r'\d', 'X', text)   # replace all digits
print(cleaned)  # Contact Sisi at sisi@webortex.com or call +XX-XXXXXXXXXX

# re.split() — split by pattern
parts = re.split(r'[\s,]+', "hello   world,  python")
print(parts)    # ['hello', 'world', 'python']

# Common patterns
patterns = {
    'email':   r'^[\w.+-]+@[\w-]+\.[\w.]+$',
    'phone':   r'^(\+91)?[6-9]\d{9}$',
    'url':     r'https?://(?:[-\w.]|(?:%[\da-fA-F]{2}))+',
    'integer': r'^-?\d+$',
    'date':    r'\d{2}/\d{2}/\d{4}'
}

# Compiled pattern — reuse for better performance
email_pattern = re.compile(r'^[\w.+-]+@[\w-]+\.[\w.]+$', re.IGNORECASE)
print(bool(email_pattern.match("sisi@webortex.com")))  # True
print(bool(email_pattern.match("not-an-email")))       # False

# Groups — capture specific parts
phone = re.search(r'(\+\d{2})-(\d{10})', text)
if phone:
    print(phone.group(0))   # +91-9876543210 (full match)
    print(phone.group(1))   # +91 (country code)
    print(phone.group(2))   # 9876543210 (number)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Data Structures & Built-in Tools

<br>

### 56. What is the collections module? Name its key classes

The `collections` module provides **specialized container data types** beyond the built-ins.

```python
from collections import Counter, defaultdict, OrderedDict, deque, namedtuple, ChainMap

# Counter — count occurrences
words = ["apple", "mango", "apple", "banana", "mango", "apple"]
c = Counter(words)
print(c)                        # Counter({'apple': 3, 'mango': 2, 'banana': 1})
print(c.most_common(2))         # [('apple', 3), ('mango', 2)]
print(c["apple"])               # 3

# Counter for strings
char_count = Counter("mississippi")
print(char_count)               # Counter({'i': 4, 's': 4, 'p': 2, 'm': 1})

# defaultdict — default value for missing keys (no KeyError)
dd = defaultdict(list)
dd["fruits"].append("apple")   # no KeyError — creates empty list first
dd["fruits"].append("mango")
print(dd["veggies"])            # [] — default is empty list (not KeyError)

word_positions = defaultdict(list)
for i, word in enumerate(["the", "cat", "the", "dog"]):
    word_positions[word].append(i)
print(word_positions)  # {'the': [0, 2], 'cat': [1], 'dog': [3]}

# OrderedDict — remembers insertion order (now built into dict in Python 3.7+)
od = OrderedDict([("a", 1), ("b", 2), ("c", 3)])
od.move_to_end("a")     # move "a" to end
print(list(od.keys()))  # ['b', 'c', 'a']

# deque — double-ended queue (O(1) append/pop from both ends)
dq = deque([1, 2, 3])
dq.appendleft(0)        # O(1) — list.insert(0, 0) is O(n)
dq.append(4)
print(dq)               # deque([0, 1, 2, 3, 4])
dq.popleft()            # O(1) — remove from left
dq.rotate(2)            # rotate right by 2

# ChainMap — search multiple dicts as one
defaults = {"color": "blue", "font": "Arial"}
user_prefs = {"color": "red"}
config = ChainMap(user_prefs, defaults)
print(config["color"])  # "red"  — user_prefs wins
print(config["font"])   # "Arial" — falls back to defaults
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 57. What is the difference between a list and a deque?

| Operation | `list` | `deque` |
| --------- | ------ | ------- |
| Append to right | O(1) | O(1) |
| Pop from right | O(1) | O(1) |
| Append to left | O(n) — shifts all | O(1) |
| Pop from left | O(n) — shifts all | O(1) |
| Random access (index) | O(1) | O(n) |
| Memory | Less overhead | Slightly more |
| Best for | Random access, general | Queue/stack operations at both ends |

```python
from collections import deque

# deque as queue (FIFO)
queue = deque()
queue.append("task1")      # enqueue
queue.append("task2")
queue.append("task3")
print(queue.popleft())     # dequeue → "task1" (O(1))

# deque as stack (LIFO)
stack = deque()
stack.append("a")
stack.append("b")
print(stack.pop())         # → "b" (O(1))

# deque with maxlen — sliding window
window = deque(maxlen=3)
for i in range(6):
    window.append(i)
    print(list(window))
# [0]
# [0, 1]
# [0, 1, 2]
# [1, 2, 3]  — auto-removes oldest when full
# [2, 3, 4]
# [3, 4, 5]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 58. What is enumerate() and zip() in Python?

```python
# enumerate() — iterate with index
fruits = ["apple", "mango", "banana"]

for i, fruit in enumerate(fruits):
    print(f"{i}: {fruit}")
# 0: apple  1: mango  2: banana

for i, fruit in enumerate(fruits, start=1):  # start index from 1
    print(f"{i}. {fruit}")
# 1. apple  2. mango  3. banana

# zip() — iterate multiple iterables simultaneously
names = ["Sisi", "Yamini", "Pavani"]
ages  = [20, 22, 21]
cities = ["Tirupati", "Hyderabad", "Chennai"]

for name, age, city in zip(names, ages, cities):
    print(f"{name} ({age}) from {city}")

# zip stops at shortest iterable
a = [1, 2, 3, 4]
b = ["a", "b"]
print(list(zip(a, b)))   # [(1, 'a'), (2, 'b')]  — stops at b's length

# itertools.zip_longest — continue with fillvalue
from itertools import zip_longest
print(list(zip_longest(a, b, fillvalue=None)))
# [(1, 'a'), (2, 'b'), (3, None), (4, None)]

# Unzipping — use * to unzip
pairs = [(1, "a"), (2, "b"), (3, "c")]
numbers, letters = zip(*pairs)
print(numbers)   # (1, 2, 3)
print(letters)   # ('a', 'b', 'c')

# Creating dict from two lists
d = dict(zip(names, ages))
print(d)   # {'Sisi': 20, 'Yamini': 22, 'Pavani': 21}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 59. What is the difference between sorted() and list.sort()?

| Feature | `sorted()` | `list.sort()` |
| ------- | ---------- | ------------- |
| Returns | New sorted list | `None` (in-place) |
| Modifies original | ❌ No | ✅ Yes |
| Works on | Any iterable | Lists only |
| Memory | More (new list created) | Less (in-place) |

```python
nums = [3, 1, 4, 1, 5, 9, 2, 6]

# sorted() — returns new list, original unchanged
sorted_nums = sorted(nums)
print(sorted_nums)   # [1, 1, 2, 3, 4, 5, 6, 9]
print(nums)          # [3, 1, 4, 1, 5, 9, 2, 6] — unchanged!

# list.sort() — modifies in-place, returns None
nums.sort()
print(nums)          # [1, 1, 2, 3, 4, 5, 6, 9] — modified!
result = nums.sort()
print(result)        # None — common mistake!

# Both support reverse and key
words = ["banana", "Apple", "cherry", "date"]
print(sorted(words))                             # ['Apple', 'banana', 'cherry', 'date']
print(sorted(words, key=str.lower))             # ['Apple', 'banana', 'cherry', 'date'] — case-insensitive
print(sorted(words, key=len))                   # ['date', 'Apple', 'banana', 'cherry']
print(sorted(words, reverse=True))              # ['date', 'cherry', 'banana', 'Apple']

# Sort complex objects
students = [("Sisi", 20, 9.2), ("Yamini", 22, 8.5), ("Pavani", 19, 9.5)]
print(sorted(students, key=lambda s: s[2], reverse=True))  # by GPA, high to low

# Multi-key sort
print(sorted(students, key=lambda s: (-s[2], s[0])))  # by GPA desc, then name asc

# Stable sort — equal elements maintain original order (Python's Timsort)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 60. What are *unpacking and **unpacking in Python?

```python
# * unpacking — unpack iterables
a, *b, c = [1, 2, 3, 4, 5]
print(a)   # 1
print(b)   # [2, 3, 4]  — middle elements
print(c)   # 5

first, *rest = "hello"
print(first)   # 'h'
print(rest)    # ['e', 'l', 'l', 'o']

# Merge lists with *
list1 = [1, 2, 3]
list2 = [4, 5, 6]
merged = [*list1, *list2, 7, 8]
print(merged)   # [1, 2, 3, 4, 5, 6, 7, 8]

# Merge sets
s1 = {1, 2, 3}
s2 = {3, 4, 5}
combined = {*s1, *s2}
print(combined)  # {1, 2, 3, 4, 5}

# ** unpacking — unpack dicts
d1 = {"name": "Sisi", "age": 20}
d2 = {"city": "Tirupati", "role": "CEO"}
merged_dict = {**d1, **d2}
print(merged_dict)  # {'name': 'Sisi', 'age': 20, 'city': 'Tirupati', 'role': 'CEO'}

# Override values
updated = {**d1, "age": 21, "company": "Webortex"}
print(updated)  # {'name': 'Sisi', 'age': 21, 'company': 'Webortex'}

# Pass list/dict as function arguments
def add(a, b, c):
    return a + b + c

args = [1, 2, 3]
print(add(*args))      # 6

kwargs = {"a": 1, "b": 2, "c": 3}
print(add(**kwargs))   # 6
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 61. What is the difference between dict.get() and dict[key]?

| Method | Missing key behavior | Returns |
| ------ | -------------------- | ------- |
| `dict[key]` | Raises `KeyError` | Value |
| `dict.get(key)` | Returns `None` (default) | Value or default |
| `dict.get(key, default)` | Returns `default` | Value or default |

```python
user = {"name": "Sisi", "age": 20}

# dict[key] — KeyError if missing
print(user["name"])     # "Sisi"
# print(user["email"]) # KeyError: 'email'

# dict.get() — safe access
print(user.get("name"))          # "Sisi"
print(user.get("email"))         # None (no error)
print(user.get("email", "N/A"))  # "N/A" (custom default)

# setdefault() — get value, set default if missing
user.setdefault("role", "user")  # sets if not present
print(user["role"])              # "user"
user.setdefault("role", "admin") # won't overwrite existing
print(user["role"])              # "user" (unchanged)

# Pattern: counting with get()
text = "mississippi"
freq = {}
for char in text:
    freq[char] = freq.get(char, 0) + 1
print(freq)   # {'m': 1, 'i': 4, 's': 4, 'p': 2}

# dict.pop() — remove and return (with default)
removed = user.pop("role", None)   # safe remove
print(removed)    # "user"
print(user.pop("nonexistent", "default"))  # "default" (no KeyError)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 62. What are frozensets in Python?

A `frozenset` is an **immutable version of a set** — it's hashable, can be used as dictionary keys or set elements, but cannot be modified after creation.

```python
# frozenset creation
fs = frozenset([1, 2, 3, 4, 5])
fs2 = frozenset("hello")
print(fs)     # frozenset({1, 2, 3, 4, 5})
print(fs2)    # frozenset({'e', 'h', 'l', 'o'}) — unique chars

# Immutable — cannot add or remove
# fs.add(6)     # AttributeError: 'frozenset' object has no attribute 'add'
# fs.remove(1)  # AttributeError

# All set operations work (return new frozensets)
a = frozenset([1, 2, 3])
b = frozenset([2, 3, 4])
print(a | b)   # frozenset({1, 2, 3, 4}) — union
print(a & b)   # frozenset({2, 3}) — intersection
print(a - b)   # frozenset({1}) — difference

# Hashable — can be dict key or element in set
seen_combinations = set()
combo = frozenset(["React", "Node", "MongoDB"])
seen_combinations.add(combo)   # ✅ works

skill_levels = {frozenset(["Python", "ML"]): "Senior", frozenset(["React"]): "Junior"}
print(skill_levels[frozenset(["Python", "ML"])])  # "Senior"

# Common use: represent immutable groups (permissions, tags)
READ_ONLY = frozenset(["read"])
READ_WRITE = frozenset(["read", "write"])
ADMIN = frozenset(["read", "write", "delete", "admin"])
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 63. What are named tuples?

Named tuples are **tuples with named fields** — they give meaning to each position, making code more readable while remaining immutable and memory-efficient.

```python
from collections import namedtuple
from typing import NamedTuple  # typed version

# collections.namedtuple
Point = namedtuple("Point", ["x", "y"])
p = Point(10, 20)
print(p.x, p.y)        # 10 20 — access by name
print(p[0], p[1])      # 10 20 — also by index (still a tuple)
print(p)               # Point(x=10, y=20) — nice repr

# Immutable
# p.x = 5   # AttributeError

# Methods
print(p._asdict())              # {'x': 10, 'y': 20}
p2 = p._replace(x=99)          # creates new namedtuple with x=99
print(p2)                       # Point(x=99, y=20)
print(Point._fields)            # ('x', 'y')

# Typed NamedTuple (Python 3.6+) — preferred modern syntax
class Employee(NamedTuple):
    name: str
    department: str
    salary: float
    is_active: bool = True      # default value

emp = Employee("Sisi", "Engineering", 75000.0)
print(emp)                      # Employee(name='Sisi', department='Engineering', salary=75000.0, is_active=True)
print(emp.name)                 # Sisi
print(emp._asdict())            # OrderedDict with all fields

# Named tuple vs dict vs dataclass:
# namedtuple: immutable, lightweight, tuple-compatible, no methods
# dict: mutable, flexible, heavier
# dataclass: mutable (or frozen), can have methods, OOP-friendly
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 64. What is the difference between any() and all()?

| Function | Returns True when | Returns False when | Empty iterable |
| -------- | ----------------- | ------------------ | -------------- |
| `any(iterable)` | At least ONE element is truthy | ALL elements are falsy | `False` |
| `all(iterable)` | ALL elements are truthy | At least ONE is falsy | `True` |

```python
nums = [1, 2, 3, 4, 5]

# any() — like OR chain
print(any([0, 0, 1]))      # True  — at least one truthy
print(any([0, 0, 0]))      # False — all falsy
print(any([]))             # False — empty iterable

# all() — like AND chain
print(all([1, 2, 3]))      # True  — all truthy
print(all([1, 0, 3]))      # False — 0 is falsy
print(all([]))             # True  — vacuously true (empty)

# With generator expressions (short-circuits!)
nums = range(1, 100)
print(any(n > 50 for n in nums))    # True — stops at 51
print(all(n > 0 for n in nums))     # True — all positive

# Practical examples
scores = [85, 92, 78, 96, 88]
print(all(s >= 70 for s in scores))   # True — all passed
print(any(s >= 90 for s in scores))   # True — some scored 90+

users = [{"name": "Sisi", "active": True}, {"name": "X", "active": False}]
print(all(u["active"] for u in users))   # False
print(any(u["active"] for u in users))   # True

# Check if string contains any digit
print(any(c.isdigit() for c in "hello123"))  # True
print(all(c.isalpha() for c in "hello"))     # True
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 65. What is __slots__ in Python?

`__slots__` is a class-level declaration that **restricts instance attributes to a predefined set**, replacing the per-instance `__dict__` with a fixed-size structure — reducing memory usage significantly for classes with many instances.

```python
import sys

# Without __slots__ — each instance has a __dict__
class RegularPoint:
    def __init__(self, x, y):
        self.x = x
        self.y = y

# With __slots__ — no __dict__, fixed attribute set
class SlottedPoint:
    __slots__ = ["x", "y"]   # only these attributes allowed

    def __init__(self, x, y):
        self.x = x
        self.y = y

rp = RegularPoint(1, 2)
sp = SlottedPoint(1, 2)

print(sys.getsizeof(rp))    # ~48+ bytes (plus __dict__ overhead ~232 bytes)
print(sys.getsizeof(sp))    # ~64 bytes — significantly less

# __dict__ exists for regular, not for slotted
print(hasattr(rp, '__dict__'))  # True
print(hasattr(sp, '__dict__'))  # False

# Cannot add new attributes to slotted class
rp.z = 3          # OK for regular
# sp.z = 3        # AttributeError — z not in __slots__

# Inheritance with __slots__
class Point3D(SlottedPoint):
    __slots__ = ["z"]   # adds only 'z'; inherits x, y from parent

p3d = Point3D(1, 2, 3) if False else None  # simplified

# When to use __slots__:
# - Classes creating thousands/millions of instances (e.g., data records, nodes)
# - Memory-constrained environments
# - When you want to restrict attribute creation
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Concurrency & Performance

<br>

### 66. What is the GIL (Global Interpreter Lock)?

The GIL is a **mutex (lock) in CPython** that allows only one thread to execute Python bytecode at a time — even on multi-core processors. It protects Python's memory management (reference counting) from race conditions.

```python
import threading
import time

# GIL impact — CPU-bound task with threads
def cpu_task(n):
    total = 0
    for _ in range(n):
        total += 1
    return total

# Single thread
start = time.time()
cpu_task(100_000_000)
print(f"Single: {time.time() - start:.2f}s")   # e.g. 4.5s

# Two threads — GIL prevents true parallelism, may be SLOWER!
start = time.time()
t1 = threading.Thread(target=cpu_task, args=(50_000_000,))
t2 = threading.Thread(target=cpu_task, args=(50_000_000,))
t1.start(); t2.start()
t1.join(); t2.join()
print(f"Two threads: {time.time() - start:.2f}s")  # e.g. 5.2s (GIL overhead!)

# I/O-bound tasks — threads work well (GIL released during I/O)
import urllib.request

urls = ["http://example.com"] * 5

def fetch(url):
    urllib.request.urlopen(url).read()  # GIL released while waiting for network

start = time.time()
threads = [threading.Thread(target=fetch, args=(url,)) for url in urls]
for t in threads: t.start()
for t in threads: t.join()
print(f"Threaded I/O: {time.time() - start:.2f}s")  # much faster than sequential

# Solutions to GIL limitations:
# 1. multiprocessing — separate processes, each with own GIL
# 2. concurrent.futures — ProcessPoolExecutor for CPU-bound
# 3. Cython with `nogil` blocks
# 4. PyPy (alternative Python implementation, no GIL issues)
# 5. NumPy/SciPy (release GIL for C-level operations)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 67. What is the difference between threading and multiprocessing?

| Feature | `threading` | `multiprocessing` |
| ------- | ----------- | ----------------- |
| GIL affected? | ✅ Yes — one thread at a time | ❌ No — separate interpreter per process |
| True parallelism | ❌ No (CPU-bound) | ✅ Yes |
| Memory | Shared memory | Separate memory space |
| Communication | Shared variables (with locks) | Queue, Pipe, Manager |
| Overhead | Low | Higher (process creation) |
| Best for | I/O-bound tasks | CPU-bound tasks |

```python
import threading
import multiprocessing
import time

def square(n):
    return sum(i*i for i in range(n))

n = 5_000_000

# Threading — concurrent but not parallel for CPU work
start = time.time()
threads = [threading.Thread(target=square, args=(n,)) for _ in range(4)]
for t in threads: t.start()
for t in threads: t.join()
print(f"Threading: {time.time() - start:.2f}s")  # ~same as serial

# Multiprocessing — true parallelism
if __name__ == "__main__":
    start = time.time()
    with multiprocessing.Pool(processes=4) as pool:
        results = pool.map(square, [n, n, n, n])
    print(f"Multiprocessing: {time.time() - start:.2f}s")  # ~4x faster!

# concurrent.futures — high-level interface
from concurrent.futures import ThreadPoolExecutor, ProcessPoolExecutor

# I/O-bound → ThreadPoolExecutor
def fetch_data(url):
    import urllib.request
    return urllib.request.urlopen(url).read()[:100]

with ThreadPoolExecutor(max_workers=5) as executor:
    futures = [executor.submit(fetch_data, "http://example.com") for _ in range(5)]
    results = [f.result() for f in futures]

# CPU-bound → ProcessPoolExecutor
def compute(n):
    return sum(range(n))

with ProcessPoolExecutor(max_workers=4) as executor:
    results = list(executor.map(compute, [10**7] * 4))
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 68. What is asyncio? How does it work?

`asyncio` is Python's **built-in library for asynchronous programming** using an event loop and coroutines. It achieves concurrency in a single thread through cooperative multitasking.

```python
import asyncio
import time
import aiohttp  # async HTTP (pip install aiohttp)

# Basic coroutine
async def greet(name, delay):
    await asyncio.sleep(delay)   # yield control during wait
    print(f"Hello, {name}!")
    return f"Greeted {name}"

# Running coroutines
async def main():
    # Sequential — takes 2 + 1 = 3 seconds
    # await greet("Sisi", 2)
    # await greet("Yamini", 1)

    # Concurrent — takes max(2, 1) = 2 seconds!
    results = await asyncio.gather(
        greet("Sisi", 2),
        greet("Yamini", 1),
        greet("Pavani", 0.5)
    )
    print(results)

asyncio.run(main())   # Python 3.7+

# Real-world: async HTTP requests
async def fetch_url(session, url):
    async with session.get(url) as response:
        return await response.text()

async def fetch_all(urls):
    async with aiohttp.ClientSession() as session:
        tasks = [fetch_url(session, url) for url in urls]
        return await asyncio.gather(*tasks)

# Event loop phases:
# 1. Create coroutines (async def functions)
# 2. Submit to event loop
# 3. Event loop runs, hitting await → yields control
# 4. When I/O completes → coroutine resumes
# No OS threads involved — single thread, cooperative scheduling

# asyncio.create_task() — run concurrently
async def producer():
    for i in range(5):
        await asyncio.sleep(0.5)
        yield i   # async generator

async def consume():
    async for item in producer():
        print(f"Got: {item}")
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 69. What is the difference between concurrency and parallelism?

| Concept | Definition | Threads/Processes | Python mechanism |
| ------- | ---------- | ----------------- | ---------------- |
| **Concurrency** | Multiple tasks make progress (may interleave) | 1+ threads/coroutines | `threading`, `asyncio` |
| **Parallelism** | Multiple tasks execute simultaneously | Multiple CPU cores | `multiprocessing` |

```
Concurrency (one cook, multiple tasks — switches between):
Time: ---task1---task2---task1---task2---task1---task2-->
      [Start soup] [Chop veg] [Stir soup] [Boil veg] [Serve]

Parallelism (multiple cooks, each on own task):
Time: ---task1------>
      ---task2------>
      ---task3------>
      All simultaneously!
```

```python
# Analogy in code:

# Concurrency with asyncio — single thread, cooperative
import asyncio
async def task(name, delay):
    print(f"{name} started")
    await asyncio.sleep(delay)    # yields during I/O wait
    print(f"{name} done")

# Both tasks appear to run simultaneously (interleaved)
# But only ONE is actually executing at any moment

# Parallelism with multiprocessing — truly simultaneous
from multiprocessing import Pool
def cpu_work(x): return x ** 2
with Pool(4) as pool:
    results = pool.map(cpu_work, range(100))
# 4 CPU cores working simultaneously!

# Rule:
# I/O-bound (network, disk, DB) → concurrency (threading or asyncio)
# CPU-bound (calculations, compression, ML) → parallelism (multiprocessing)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 70. How do you share data between processes in Python?

```python
from multiprocessing import Process, Queue, Pipe, Value, Array, Manager
import multiprocessing

# Method 1: Queue — safe FIFO communication between processes
def producer(queue):
    for i in range(5):
        queue.put(f"item_{i}")
    queue.put(None)   # sentinel to signal done

def consumer(queue):
    while True:
        item = queue.get()
        if item is None: break
        print(f"Consumed: {item}")

if __name__ == "__main__":
    q = Queue()
    p = Process(target=producer, args=(q,))
    c = Process(target=consumer, args=(q,))
    p.start(); c.start()
    p.join(); c.join()

# Method 2: Pipe — bidirectional communication
def sender(conn):
    conn.send({"data": [1, 2, 3], "status": "ok"})
    conn.close()

parent_conn, child_conn = Pipe()
p = Process(target=sender, args=(child_conn,))
p.start()
print(parent_conn.recv())   # {'data': [1, 2, 3], 'status': 'ok'}
p.join()

# Method 3: Shared memory (Value, Array) — for simple types
shared_counter = Value('i', 0)   # 'i' = int
shared_array = Array('d', [1.0, 2.0, 3.0])  # 'd' = double

# Method 4: Manager — for complex shared objects (dict, list)
with Manager() as manager:
    shared_dict = manager.dict()
    shared_list = manager.list()
    # Can share across processes (uses server process internally)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 71. What is a thread lock? How do you prevent race conditions?

A **lock (mutex)** prevents multiple threads from accessing a shared resource simultaneously — preventing race conditions where the final result depends on thread execution order.

```python
import threading

# Race condition without lock
counter = 0
def increment_unsafe():
    global counter
    for _ in range(100_000):
        counter += 1   # NOT atomic — read-modify-write can interleave!

threads = [threading.Thread(target=increment_unsafe) for _ in range(5)]
for t in threads: t.start()
for t in threads: t.join()
print(f"Unsafe: {counter}")   # Less than 500,000 — race condition!

# Fix with Lock
counter = 0
lock = threading.Lock()

def increment_safe():
    global counter
    for _ in range(100_000):
        with lock:             # acquire lock, release after block
            counter += 1       # only one thread at a time

threads = [threading.Thread(target=increment_safe) for _ in range(5)]
for t in threads: t.start()
for t in threads: t.join()
print(f"Safe: {counter}")    # 500,000 — always correct

# RLock — reentrant lock (same thread can acquire multiple times)
rlock = threading.RLock()

# Semaphore — limit concurrent access to N threads
semaphore = threading.Semaphore(3)  # max 3 threads at a time

def limited_access():
    with semaphore:
        # at most 3 threads here simultaneously
        time.sleep(1)

# Event — signal between threads
event = threading.Event()

def waiter():
    print("Waiting for signal...")
    event.wait()           # block until event is set
    print("Signal received!")

def signaler():
    time.sleep(2)
    event.set()            # release all waiters
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 72. What is the difference between async/await and threading?

| Feature | `async/await` (asyncio) | `threading` |
| ------- | ----------------------- | ----------- |
| Concurrency model | Cooperative (yields control explicitly) | Preemptive (OS switches threads) |
| Threads used | 1 (event loop) | Multiple OS threads |
| GIL impact | Avoids GIL (single thread) | Subject to GIL |
| Overhead | Very low | Context switch overhead |
| Best for | Many I/O-bound tasks (thousands of connections) | Simpler I/O tasks, legacy code |
| Complexity | Higher (async code infects codebase) | Lower |

```python
# Async — handles 1000s of connections in 1 thread
import asyncio
import aiohttp

async def fetch(session, url):
    async with session.get(url) as r:
        return await r.text()

async def main():
    async with aiohttp.ClientSession() as session:
        # 100 requests, all concurrent, in 1 thread!
        tasks = [fetch(session, f"http://example.com/{i}") for i in range(100)]
        results = await asyncio.gather(*tasks)

# Threading — simpler but more overhead for 100+ concurrent tasks
from concurrent.futures import ThreadPoolExecutor
import urllib.request

def fetch_sync(url):
    return urllib.request.urlopen(url).read()

with ThreadPoolExecutor(max_workers=20) as executor:
    futures = [executor.submit(fetch_sync, url) for url in urls]
    # 20 threads, not 100 — OS can't handle 100 threads efficiently
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Memory, Internals & Metaclasses

<br>

### 73. How does Python's garbage collector work?

Python uses **two-phase garbage collection**: reference counting (primary) + cyclic garbage collector (secondary).

```python
import gc
import sys

# Phase 1: Reference counting
a = [1, 2, 3]
print(sys.getrefcount(a))   # 2 (a + getrefcount parameter)
b = a                        # ref count = 3
del b                        # ref count = 2
del a                        # ref count = 0 → immediately freed

# Phase 2: Cyclic garbage collector (for reference cycles)
class Node:
    def __init__(self, val):
        self.val = val
        self.next = None

n1 = Node(1)
n2 = Node(2)
n1.next = n2    # n1 → n2
n2.next = n1    # n2 → n1 (cycle! ref counts never reach 0)

del n1, n2   # ref counts = 1 each (not 0!) — needs GC

gc.collect()   # manually trigger garbage collection

# Generational GC — objects promoted through 3 generations
# Gen 0: new objects — collected most frequently
# Gen 1: survived Gen 0 collection — collected less often
# Gen 2: long-lived objects — collected rarely

print(gc.get_threshold())   # (700, 10, 10) — collection triggers
print(gc.get_count())       # (gen0, gen1, gen2) current counts

gc.disable()   # disable GC (if you manage cycles manually)
gc.enable()    # re-enable

# __del__ finalizer — called when object is about to be destroyed
class Resource:
    def __init__(self, name):
        self.name = name
    def __del__(self):
        print(f"Resource {self.name} released")
# Use context managers instead of __del__ for reliable cleanup!
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 74. What are metaclasses in Python?

A metaclass is **the class of a class** — it controls how classes themselves are created. If a class is an instance of `type`, then `type` is a metaclass.

```python
# type() creates classes dynamically
# type(name, bases, dict) → creates a new class
Dog = type("Dog", (object,), {
    "species": "Canis familiaris",
    "bark": lambda self: f"{self.name} says Woof!",
    "__init__": lambda self, name: setattr(self, "name", name)
})

d = Dog("Bruno")
print(d.bark())   # Bruno says Woof!

# Custom metaclass — control class creation
class ValidatedMeta(type):
    def __new__(mcs, name, bases, namespace):
        # Enforce all methods have docstrings
        for key, value in namespace.items():
            if callable(value) and not key.startswith("__"):
                if not value.__doc__:
                    raise TypeError(f"Method '{key}' in class '{name}' must have a docstring!")
        return super().__new__(mcs, name, bases, namespace)

class MyService(metaclass=ValidatedMeta):
    def process(self):
        """Process the request."""   # required!
        return "processed"

    # def undocumented(self):      # would raise TypeError at class creation!
    #     pass

# Singleton via metaclass
class SingletonMeta(type):
    _instances = {}
    def __call__(cls, *args, **kwargs):
        if cls not in cls._instances:
            cls._instances[cls] = super().__call__(*args, **kwargs)
        return cls._instances[cls]

class Database(metaclass=SingletonMeta):
    def __init__(self, url):
        self.url = url

db1 = Database("mongodb://localhost")
db2 = Database("mongodb://other")    # ignored — returns same instance
print(db1 is db2)   # True
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 75. What are descriptors in Python?

Descriptors are objects that **define how attribute access is handled** by implementing `__get__`, `__set__`, and/or `__delete__` methods — the mechanism behind `@property`, `@classmethod`, `@staticmethod`.

```python
# Descriptor class
class Validator:
    """Descriptor that validates attribute values."""
    def __init__(self, min_val, max_val):
        self.min_val = min_val
        self.max_val = max_val
        self.name = None

    def __set_name__(self, owner, name):   # called when descriptor is assigned to class
        self.name = name

    def __get__(self, obj, objtype=None):
        if obj is None:
            return self   # accessed on class, not instance
        return obj.__dict__.get(self.name)

    def __set__(self, obj, value):
        if not self.min_val <= value <= self.max_val:
            raise ValueError(f"{self.name} must be between {self.min_val} and {self.max_val}")
        obj.__dict__[self.name] = value

    def __delete__(self, obj):
        del obj.__dict__[self.name]

class Student:
    age   = Validator(0, 150)    # descriptor instance
    grade = Validator(0, 100)

    def __init__(self, name, age, grade):
        self.name = name
        self.age = age       # calls Validator.__set__
        self.grade = grade

s = Student("Sisi", 20, 95)
print(s.age)     # 20  — calls Validator.__get__
# s.age = 200   # ValueError: age must be between 0 and 150

# This is how @property works internally:
class Circle:
    def __init__(self, radius):
        self._radius = radius

    @property              # property is a built-in descriptor
    def radius(self):
        return self._radius

    @radius.setter
    def radius(self, value):
        if value < 0:
            raise ValueError("Radius cannot be negative")
        self._radius = value
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 76. What is monkey patching in Python?

Monkey patching is **dynamically modifying or extending a module, class, or object at runtime** — adding or replacing methods/attributes without changing the original source code.

```python
# Monkey patching a class
class Dog:
    def speak(self):
        return "Woof!"

def fancy_speak(self):
    return f"🐕 {self.__class__.__name__} says: WOOF WOOF WOOF! 🐕"

Dog.speak = fancy_speak   # patch the class method

d = Dog()
print(d.speak())   # 🐕 Dog says: WOOF WOOF WOOF! 🐕

# Monkey patching a module (common in testing)
import math

original_sqrt = math.sqrt

def safe_sqrt(x):
    if x < 0:
        raise ValueError(f"Cannot take square root of negative: {x}")
    return original_sqrt(x)

math.sqrt = safe_sqrt   # patch the module function

# In testing — mock external dependencies
# import requests
# requests.get = lambda url, **kwargs: MockResponse(200, {"data": "test"})

# ⚠️ Risks of monkey patching:
# - Hard to debug (unexpected behavior from patched code)
# - Can break when library updates
# - Creates hidden dependencies
# Use sparingly — prefer proper subclassing or dependency injection

# Legitimate uses:
# - Testing (mock external APIs)
# - Adding methods to third-party classes you can't modify
# - Hotfixes for bugs in dependencies
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 77. What is the difference between __getattr__ and __getattribute__?

| Method | Called when | Can cause infinite recursion? |
| ------ | ----------- | ----------------------------- |
| `__getattribute__` | Every attribute access (always) | ✅ Yes — be careful |
| `__getattr__` | Only when attribute NOT found via normal lookup (fallback) | ❌ No |

```python
class SmartObject:
    def __init__(self):
        self.name = "Sisi"
        self._cache = {}

    def __getattribute__(self, name):
        # Called for EVERY attribute access — even 'name', '_cache'
        print(f"__getattribute__ called for: {name}")
        return object.__getattribute__(self, name)  # use object's to avoid recursion!
        # ❌ NEVER: return self.__dict__[name]  — causes infinite recursion!

    def __getattr__(self, name):
        # Called ONLY when attribute not found via normal lookup
        print(f"__getattr__ called for: {name}")
        if name.startswith("get_"):
            key = name[4:]     # strip "get_"
            return lambda: self._cache.get(key, f"No value for {key}")
        raise AttributeError(f"'{type(self).__name__}' has no attribute '{name}'")

obj = SmartObject()
print(obj.name)           # __getattribute__ called → "Sisi"
print(obj.get_status())   # __getattr__ called → "No value for status"
# print(obj.nonexistent) # AttributeError (from __getattr__)

# Common use case: dynamic attribute proxy
class Config:
    def __init__(self, data):
        self._data = data

    def __getattr__(self, key):
        try:
            return self._data[key]
        except KeyError:
            raise AttributeError(f"No config key: {key}")

config = Config({"debug": True, "port": 5000})
print(config.debug)   # True (dynamic — no actual attribute)
print(config.port)    # 5000
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 78. What is pickling and unpickling in Python?

Pickling is **serializing a Python object into a byte stream** (for storage or network transmission). Unpickling deserializes it back.

```python
import pickle

# Pickling — object → bytes
data = {
    "name": "Sisi",
    "scores": [95, 87, 92],
    "metadata": {"role": "CEO", "company": "Webortex"}
}

# Serialize to file
with open("data.pkl", "wb") as f:   # 'wb' — write binary
    pickle.dump(data, f)

# Serialize to bytes (in-memory)
serialized = pickle.dumps(data)
print(type(serialized))   # <class 'bytes'>

# Unpickling — bytes → object
with open("data.pkl", "rb") as f:   # 'rb' — read binary
    loaded = pickle.load(f)
print(loaded)   # original dict reconstructed

from_bytes = pickle.loads(serialized)
print(from_bytes == data)   # True

# Pickling custom classes
class Model:
    def __init__(self, name, weights):
        self.name = name
        self.weights = weights

    def predict(self, x):
        return sum(w * xi for w, xi in zip(self.weights, x))

model = Model("LinearRegressor", [0.5, 0.3, 0.8])
saved = pickle.dumps(model)
loaded_model = pickle.loads(saved)
print(loaded_model.predict([1, 2, 3]))   # same model, restored!

# ⚠️ Security warning: NEVER unpickle data from untrusted sources!
# Pickle can execute arbitrary code during deserialization.
# Use JSON for data exchange, pickle only for trusted internal use.
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 79. What are weak references in Python?

Weak references **reference an object without preventing it from being garbage collected** — useful for caches, observers, and avoiding circular references.

```python
import weakref
import gc

class BigObject:
    def __init__(self, name):
        self.name = name
    def __del__(self):
        print(f"{self.name} garbage collected!")

# Strong reference — prevents GC
obj = BigObject("strong")
ref = obj             # strong reference — ref count = 2
del obj               # ref count = 1 — NOT collected!
del ref               # ref count = 0 → garbage collected

# Weak reference — does NOT prevent GC
obj = BigObject("weak")
weak_ref = weakref.ref(obj)      # weak reference

print(weak_ref())      # <BigObject object> — access via call
print(weak_ref().name) # "weak"

del obj               # object IS collected (weak ref doesn't prevent it)
print(weak_ref())      # None — object is gone!

# WeakValueDictionary — auto-removes entries when values are GC'd
cache = weakref.WeakValueDictionary()

big_data = BigObject("cached_data")
cache["key"] = big_data

print(cache["key"].name)  # "cached_data"
del big_data              # object collected → entry auto-removed from cache
print(list(cache.keys())) # [] — entry automatically removed!

# Use case: caching computed results without preventing memory cleanup
class ImageCache:
    def __init__(self):
        self._cache = weakref.WeakValueDictionary()

    def get(self, path):
        img = self._cache.get(path)
        if img is None:
            img = load_image(path)   # expensive operation
            self._cache[path] = img  # cache without preventing GC
        return img
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 80. What is the difference between @staticmethod, @classmethod, and @property?

```python
class Circle:
    PI = 3.14159   # class variable

    def __init__(self, radius):
        self._radius = radius

    # @property — computed attribute (controlled access)
    @property
    def radius(self):
        """Read-only access to radius."""
        return self._radius

    @radius.setter
    def radius(self, value):
        if value < 0:
            raise ValueError("Radius cannot be negative")
        self._radius = value

    @property
    def area(self):
        return Circle.PI * self._radius ** 2    # computed, not stored

    # @classmethod — receives cls, accesses class state
    @classmethod
    def from_diameter(cls, diameter):
        """Alternative constructor — factory method."""
        return cls(diameter / 2)    # creates instance using cls

    @classmethod
    def update_pi(cls, new_pi):
        cls.PI = new_pi             # modifies class variable

    # @staticmethod — receives nothing (no self or cls)
    @staticmethod
    def validate_radius(value):
        """Utility — logically belongs here but needs no class/instance data."""
        return value > 0

# Usage
c1 = Circle(5)
print(c1.area)            # 78.53975 — property (no parentheses!)
c1.radius = 10            # setter
print(c1.radius)          # 10

c2 = Circle.from_diameter(20)  # classmethod — alternative constructor
print(c2.radius)          # 10.0

print(Circle.validate_radius(5))   # True — staticmethod (no instance needed)
print(Circle.validate_radius(-1))  # False
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Libraries & Frameworks

<br>

### 81. What is NumPy? How is it different from a Python list?

NumPy is the **foundational library for numerical computing in Python** — provides fast, memory-efficient N-dimensional arrays and mathematical operations.

```python
import numpy as np
import sys

# Memory comparison
py_list = list(range(1_000_000))
np_array = np.arange(1_000_000)

print(sys.getsizeof(py_list))     # ~8.8 MB
print(np_array.nbytes)            # ~4 MB (int32) or ~8 MB (int64)

# Speed comparison
import time
py_list = list(range(1_000_000))
np_arr  = np.arange(1_000_000)

start = time.time()
py_result = [x**2 for x in py_list]
print(f"Python list: {time.time()-start:.4f}s")     # ~0.15s

start = time.time()
np_result = np_arr ** 2          # vectorized — no Python loop
print(f"NumPy array: {time.time()-start:.4f}s")     # ~0.001s (100x faster!)

# NumPy array creation
a = np.array([1, 2, 3, 4, 5])
b = np.zeros((3, 4))             # 3x4 array of zeros
c = np.ones((2, 3))              # 2x3 array of ones
d = np.linspace(0, 1, 5)         # [0., 0.25, 0.5, 0.75, 1.]
e = np.random.rand(3, 3)         # 3x3 random array

# Operations — all vectorized
arr = np.array([[1, 2, 3], [4, 5, 6]])
print(arr.shape)     # (2, 3)
print(arr.dtype)     # int64
print(arr.sum())     # 21
print(arr.mean())    # 3.5
print(arr.T)         # transpose

# Slicing — similar to lists but multi-dimensional
print(arr[0, :])     # [1 2 3] — first row
print(arr[:, 1])     # [2 5] — second column
print(arr[arr > 3])  # [4 5 6] — boolean indexing

# Broadcasting — operate on different shapes
a = np.array([1, 2, 3])
b = np.array([[1], [2], [3]])
print(a + b)   # 3x3 matrix (broadcasting)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 82. What is Pandas? Explain Series and DataFrame

Pandas is the **standard library for data manipulation and analysis** in Python — provides two main data structures: Series and DataFrame.

```python
import pandas as pd
import numpy as np

# Series — 1D labeled array
s = pd.Series([10, 20, 30, 40], index=["a", "b", "c", "d"])
print(s["b"])       # 20
print(s[s > 15])    # a:10, b:20, c:30, d:40 — filter
print(s.mean())     # 25.0

# DataFrame — 2D labeled table
data = {
    "name":   ["Sisi", "Yamini", "Pavani", "Charitha"],
    "age":    [20, 22, 21, 23],
    "score":  [9.2, 8.5, 9.5, 8.0],
    "city":   ["Tirupati", "Hyderabad", "Chennai", "Vijayawada"]
}

df = pd.DataFrame(data)
print(df.head(2))      # first 2 rows
print(df.shape)        # (4, 4)
print(df.dtypes)       # data types of each column
print(df.describe())   # statistics (mean, std, min, max, etc.)

# Column selection
print(df["name"])               # Series — single column
print(df[["name", "score"]])    # DataFrame — multiple columns

# Filtering
print(df[df["score"] >= 9.0])           # rows where score >= 9.0
print(df[(df["age"] > 20) & (df["score"] > 8.5)])  # multiple conditions

# Adding columns
df["grade"] = df["score"].apply(lambda x: "A" if x >= 9 else "B")
df["age_next_year"] = df["age"] + 1

# GroupBy
print(df.groupby("grade")["score"].mean())  # avg score per grade

# Sorting
print(df.sort_values("score", ascending=False))

# Handling missing data
df.loc[1, "score"] = None
print(df.isnull().sum())        # count nulls per column
df.fillna(df["score"].mean(), inplace=True)  # fill with mean
df.dropna(inplace=True)         # drop rows with nulls

# Reading/writing
df.to_csv("students.csv", index=False)
df_loaded = pd.read_csv("students.csv")

df.to_json("students.json", orient="records")
df_excel = pd.read_excel("data.xlsx")
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 83. What is the difference between loc and iloc in Pandas?

| Method | Indexing by | Type | Slice end inclusive? |
| ------ | ----------- | ---- | ------------------- |
| `.loc[]` | Label (row/column names) | Label-based | ✅ Yes |
| `.iloc[]` | Integer position | Position-based | ❌ No (like Python slicing) |

```python
import pandas as pd

df = pd.DataFrame({
    "name":  ["Sisi", "Yamini", "Pavani", "Charitha"],
    "age":   [20, 22, 21, 23],
    "score": [9.2, 8.5, 9.5, 8.0]
}, index=["a", "b", "c", "d"])   # custom index

# loc — label-based (uses row labels and column names)
print(df.loc["a"])                       # row with label "a"
print(df.loc["a", "score"])              # 9.2 — row "a", column "score"
print(df.loc["a":"c", "name":"age"])     # rows a to c (inclusive!), cols name to age
print(df.loc[df["score"] > 9.0])         # boolean indexing with loc

# iloc — integer position-based (like Python lists)
print(df.iloc[0])                        # first row
print(df.iloc[0, 2])                     # row 0, col 2 → 9.2
print(df.iloc[0:3, 0:2])                 # rows 0-2 (exclusive!), cols 0-1
print(df.iloc[-1])                       # last row
print(df.iloc[[0, 2, 3]])                # rows 0, 2, 3

# Practical difference
# When index is 0-based integers — loc and iloc give DIFFERENT results!
df2 = pd.DataFrame({"val": [10, 20, 30]}, index=[5, 10, 15])
print(df2.loc[5])       # row with label 5 → val=10
print(df2.iloc[0])      # first position → val=10
print(df2.loc[10])      # row with label 10 → val=20
print(df2.iloc[1])      # second position → val=20
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 84. What is Django? What are its key components?

Django is a **high-level, batteries-included Python web framework** that follows the MVT (Model-View-Template) architectural pattern.

```python
# Django project structure
# myproject/
# ├── manage.py
# ├── myproject/
# │   ├── settings.py    ← configuration
# │   ├── urls.py        ← URL routing
# │   └── wsgi.py
# └── myapp/
#     ├── models.py      ← database models (ORM)
#     ├── views.py       ← business logic
#     ├── urls.py        ← app-level routing
#     ├── serializers.py ← (DRF) API serialization
#     └── templates/     ← HTML templates

# models.py — Django ORM (similar to Mongoose)
from django.db import models

class User(models.Model):
    name = models.CharField(max_length=100)
    email = models.EmailField(unique=True)
    age = models.IntegerField()
    created_at = models.DateTimeField(auto_now_add=True)

    class Meta:
        db_table = "users"

    def __str__(self):
        return self.name

# views.py — class-based views
from django.views import View
from django.http import JsonResponse

class UserView(View):
    def get(self, request, user_id):
        user = User.objects.get(id=user_id)
        return JsonResponse({"name": user.name, "email": user.email})

    def post(self, request):
        import json
        data = json.loads(request.body)
        user = User.objects.create(**data)
        return JsonResponse({"id": user.id}, status=201)

# Django ORM queries
users = User.objects.all()
user  = User.objects.get(id=1)
users = User.objects.filter(age__gte=18).order_by("name")
users = User.objects.filter(name__icontains="sisi")  # case-insensitive search
User.objects.update(is_active=True)                  # bulk update

# Django REST Framework (DRF) — for APIs
from rest_framework import serializers, viewsets
from rest_framework.response import Response

class UserSerializer(serializers.ModelSerializer):
    class Meta:
        model = User
        fields = ["id", "name", "email", "age"]

class UserViewSet(viewsets.ModelViewSet):
    queryset = User.objects.all()
    serializer_class = UserSerializer
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 85. What is Flask? How does it differ from Django?

Flask is a **minimal, micro web framework** for Python — gives you the basics and lets you choose everything else.

| Feature | Django | Flask |
| ------- | ------ | ----- |
| Type | Full-stack framework | Micro-framework |
| ORM | Built-in | Optional (SQLAlchemy) |
| Admin panel | ✅ Built-in | ❌ Extension needed |
| Auth | ✅ Built-in | ❌ Extension (Flask-Login) |
| Learning curve | Steeper | Gentle |
| Flexibility | Less (opinionated) | More (you decide) |
| Best for | Large apps, rapid dev | APIs, small apps, prototypes |

```python
from flask import Flask, request, jsonify
from functools import wraps
import jwt

app = Flask(__name__)
app.config["SECRET_KEY"] = "your-secret-key"

# Route definition
@app.route("/")
def home():
    return "Hello from Flask!"

# REST API endpoint
@app.route("/api/users", methods=["GET", "POST"])
def users():
    if request.method == "GET":
        users = User.query.all()
        return jsonify([u.to_dict() for u in users])
    elif request.method == "POST":
        data = request.get_json()
        user = User(**data)
        db.session.add(user)
        db.session.commit()
        return jsonify(user.to_dict()), 201

# URL parameters and query strings
@app.route("/api/users/<int:user_id>")
def get_user(user_id):
    page = request.args.get("page", 1, type=int)
    user = User.query.get_or_404(user_id)
    return jsonify(user.to_dict())

# Middleware (before_request)
@app.before_request
def log_request():
    print(f"{request.method} {request.url}")

if __name__ == "__main__":
    app.run(debug=True, port=5000)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 86. What is FastAPI and why is it gaining popularity?

FastAPI is a **modern, high-performance Python web framework** for building APIs with automatic OpenAPI documentation, async support, and type hint-based validation.

```python
from fastapi import FastAPI, HTTPException, Depends
from pydantic import BaseModel, EmailStr, validator
from typing import Optional, List
import uvicorn

app = FastAPI(title="Webortex API", version="1.0.0")

# Pydantic models — automatic validation and serialization
class UserCreate(BaseModel):
    name: str
    email: EmailStr
    age: int
    skills: List[str] = []

    @validator("age")
    def age_must_be_positive(cls, v):
        if v < 0 or v > 150:
            raise ValueError("Age must be between 0 and 150")
        return v

class UserResponse(BaseModel):
    id: int
    name: str
    email: str

    class Config:
        from_attributes = True  # for SQLAlchemy models

# Endpoints — automatic OpenAPI docs at /docs
@app.get("/")
async def root():
    return {"message": "Hello from FastAPI!"}

@app.post("/api/users", response_model=UserResponse, status_code=201)
async def create_user(user: UserCreate):   # auto-validates request body!
    # If validation fails → 422 Unprocessable Entity (automatic)
    db_user = create_user_in_db(user)
    return db_user

@app.get("/api/users/{user_id}", response_model=UserResponse)
async def get_user(user_id: int):          # path param — auto-converts to int
    user = get_user_from_db(user_id)
    if not user:
        raise HTTPException(status_code=404, detail="User not found")
    return user

@app.get("/api/users")
async def list_users(page: int = 1, limit: int = 10, search: Optional[str] = None):
    return get_users_paginated(page, limit, search)

# FastAPI is 3-10x faster than Flask — uses Starlette + async Python
if __name__ == "__main__":
    uvicorn.run(app, host="0.0.0.0", port=8000)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 87. What is SQLAlchemy?

SQLAlchemy is Python's most popular **ORM (Object-Relational Mapper)** — allows you to work with SQL databases using Python objects instead of raw SQL queries.

```python
from sqlalchemy import create_engine, Column, Integer, String, Float, ForeignKey
from sqlalchemy.orm import declarative_base, Session, relationship

Base = declarative_base()

# Define models
class User(Base):
    __tablename__ = "users"
    id    = Column(Integer, primary_key=True, autoincrement=True)
    name  = Column(String(100), nullable=False)
    email = Column(String(255), unique=True, nullable=False)
    posts = relationship("Post", back_populates="author")  # one-to-many

class Post(Base):
    __tablename__ = "posts"
    id      = Column(Integer, primary_key=True)
    title   = Column(String(200))
    content = Column(String)
    user_id = Column(Integer, ForeignKey("users.id"))
    author  = relationship("User", back_populates="posts")

# Create engine and tables
engine = create_engine("sqlite:///app.db", echo=True)  # or postgresql://...
Base.metadata.create_all(engine)  # creates tables if they don't exist

# CRUD operations
with Session(engine) as session:
    # Create
    user = User(name="Sisi", email="sisi@webortex.com")
    session.add(user)
    session.commit()

    # Read
    user = session.get(User, 1)
    users = session.query(User).filter(User.name.ilike("%sisi%")).all()

    # Update
    user.name = "Sisindri"
    session.commit()

    # Delete
    session.delete(user)
    session.commit()

    # Join query
    results = session.query(User, Post).join(Post).filter(User.id == 1).all()
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🎯 Scenario & Conceptual Questions (MNC Favourites)

<br>

### 88. How is Python interpreted? What is bytecode?

```
Source code (.py)
      ↓
CPython Compiler (parsing + compilation)
      ↓
Bytecode (.pyc — in __pycache__)
      ↓
Python Virtual Machine (PVM) — executes bytecode
      ↓
Machine executes result
```

```python
import dis
import py_compile

# Compile to bytecode manually
py_compile.compile("hello.py")   # creates __pycache__/hello.cpython-311.pyc

# Inspect bytecode with dis module
def add(a, b):
    return a + b

dis.dis(add)
# Output shows bytecode instructions:
#   LOAD_FAST    a       ← push 'a' onto stack
#   LOAD_FAST    b       ← push 'b' onto stack
#   BINARY_OP   +       ← pop both, push result
#   RETURN_VALUE        ← return top of stack

# Python implementations:
# CPython  — default (C) — has GIL
# PyPy     — JIT compiled — faster for long-running programs
# Jython   — JVM-based
# IronPython — .NET-based

# .pyc files
# - Cached bytecode — Python reuses if .py hasn't changed
# - Stored in __pycache__/
# - Speeds up startup (no need to recompile)
# - Platform-specific (can't share .pyc across Python versions)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 89. What is the difference between is None and == None?

```python
# ✅ Always use `is None` — correct and Pythonic
x = None

if x is None:       # checks identity (same object in memory)
    print("x is None")

if x == None:       # checks equality — works but can be overridden!
    print("x equals None")

# Why `is None` is preferred:
class Tricky:
    def __eq__(self, other):
        return True    # always returns True for any comparison!

t = Tricky()
print(t == None)     # True — __eq__ overridden!
print(t is None)     # False — correct!

# None is a singleton — there's only ONE None object in Python
a = None
b = None
print(a is b)        # True — same object!

# PEP 8 explicitly states:
# Comparisons to singletons like None should ALWAYS use is or is not
# NEVER use == or != for None checks

# Same applies to True and False (though bool comparison is less common)
if flag is True:     # identity check
    pass
if flag == True:     # value check — works but anti-pattern
    pass
if flag:             # ✅ most Pythonic for truthy check
    pass
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 90. What happens when you pass a list to a function and modify it inside?

Python uses **pass-by-object-reference** (sometimes called "pass-by-assignment") — the function receives a reference to the same object, not a copy.

```python
# Mutable argument — modifications affect original
def add_item(lst, item):
    lst.append(item)   # modifies the SAME list object

my_list = [1, 2, 3]
add_item(my_list, 4)
print(my_list)   # [1, 2, 3, 4] — original IS modified!

# Immutable argument — cannot modify (creates new object)
def try_modify(s):
    s = s + " world"   # creates NEW string object, local rebinding

my_str = "hello"
try_modify(my_str)
print(my_str)    # "hello" — unchanged!

# Reassigning the parameter doesn't affect original
def reassign(lst):
    lst = [10, 20, 30]   # rebinds LOCAL name, doesn't affect original
    lst.append(40)

my_list = [1, 2, 3]
reassign(my_list)
print(my_list)   # [1, 2, 3] — unchanged! (reassignment broke the reference)

# To avoid unintended modification — pass a copy
def safe_add(lst, item):
    lst = lst.copy()   # work on copy
    lst.append(item)
    return lst

result = safe_add(my_list, 99)
print(my_list)   # [1, 2, 3] — unchanged
print(result)    # [1, 2, 3, 99]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 91. What is the output of this code and why? (tricky questions)

```python
# Tricky 1: Mutable default argument bug
def append_to(element, to=[]):
    to.append(element)
    return to

print(append_to(1))   # [1]
print(append_to(2))   # [1, 2] — NOT [2]! Default list is shared!
print(append_to(3))   # [1, 2, 3] — same list reused!

# Tricky 2: Late binding in closures
funcs = [lambda: i for i in range(5)]
print([f() for f in funcs])   # [4, 4, 4, 4, 4] — all see final i=4!
# Fix: lambda i=i: i  — capture i at creation time

# Tricky 3: is vs == with integers
a = 256; b = 256
print(a is b)   # True  — CPython caches -5 to 256
a = 257; b = 257
print(a is b)   # False — outside cache range (usually)

# Tricky 4: List multiplication with nested lists
matrix = [[0] * 3] * 3   # ❌ all rows are the SAME object!
matrix[0][0] = 1
print(matrix)   # [[1, 0, 0], [1, 0, 0], [1, 0, 0]] — all changed!

matrix = [[0]*3 for _ in range(3)]  # ✅ separate lists
matrix[0][0] = 1
print(matrix)   # [[1, 0, 0], [0, 0, 0], [0, 0, 0]] — correct

# Tricky 5: Exception in for loop
for i in [1, 2, 3]:
    pass
print(i)   # 3 — loop variable persists after loop!

# Tricky 6: Chained comparison
x = 5
print(1 < x < 10)    # True — Python supports chained comparisons
print(1 < x and x < 10)  # equivalent

# Tricky 7: += on list vs int
a = [1, 2]
b = a
a += [3, 4]    # list: in-place (mutates), b also changes!
print(b)       # [1, 2, 3, 4]

x = 5
y = x
x += 1         # int: creates new object (immutable), y unchanged
print(y)       # 5
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 92. How would you find duplicates in a list in Python?

```python
# Method 1: Using set
def find_duplicates_set(lst):
    seen = set()
    duplicates = set()
    for item in lst:
        if item in seen:
            duplicates.add(item)
        seen.add(item)
    return list(duplicates)

nums = [1, 2, 3, 2, 4, 5, 1, 6, 3]
print(find_duplicates_set(nums))   # [1, 2, 3]

# Method 2: Counter (most Pythonic for counting)
from collections import Counter

def find_duplicates_counter(lst):
    counts = Counter(lst)
    return [item for item, count in counts.items() if count > 1]

print(find_duplicates_counter(nums))  # [1, 2, 3]

# Method 3: List comprehension
def find_duplicates_comp(lst):
    return list({x for x in lst if lst.count(x) > 1})
# ⚠️ O(n²) — slow for large lists; use Counter instead

# Method 4: Using pandas (for DataFrames)
import pandas as pd
s = pd.Series(nums)
print(s[s.duplicated()].unique().tolist())   # [2, 1, 3]

# Find duplicate indices
def find_duplicate_indices(lst):
    from collections import defaultdict
    indices = defaultdict(list)
    for i, val in enumerate(lst):
        indices[val].append(i)
    return {val: idxs for val, idxs in indices.items() if len(idxs) > 1}

print(find_duplicate_indices(nums))
# {2: [1, 3], 1: [0, 6], 3: [2, 8]}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 93. How do you reverse a string in Python?

```python
s = "Hello, Sisi!"

# Method 1: Slicing (most Pythonic)
reversed_s = s[::-1]
print(reversed_s)      # "!isiS ,olleH"

# Method 2: reversed() + join
reversed_s = "".join(reversed(s))
print(reversed_s)      # "!isiS ,olleH"

# Method 3: loop
reversed_s = ""
for char in s:
    reversed_s = char + reversed_s

# Method 4: list + reverse
lst = list(s)
lst.reverse()
print("".join(lst))

# Check if palindrome
def is_palindrome(s):
    s = s.lower().replace(" ", "")
    return s == s[::-1]

print(is_palindrome("racecar"))    # True
print(is_palindrome("A man a plan a canal Panama"))  # True
print(is_palindrome("hello"))      # False

# Reverse words (not characters)
sentence = "Hello World Python"
reversed_words = " ".join(sentence.split()[::-1])
print(reversed_words)   # "Python World Hello"
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 94. How do you merge two dictionaries in Python?

```python
d1 = {"name": "Sisi", "age": 20}
d2 = {"city": "Tirupati", "role": "CEO"}

# Method 1: | operator (Python 3.9+) — most modern
merged = d1 | d2
print(merged)   # {'name': 'Sisi', 'age': 20, 'city': 'Tirupati', 'role': 'CEO'}

# In-place merge
d1 |= d2   # d1 updated with d2

# Method 2: ** unpacking (Python 3.5+) — most common
merged = {**d1, **d2}
print(merged)

# Method 3: dict.update()
d1 = {"name": "Sisi", "age": 20}
d1.update(d2)   # modifies d1 in-place
print(d1)

# Method 4: dict() with unpacking
merged = dict(**d1, **d2)

# Handling conflicts — right dict wins in all above methods
d1 = {"a": 1, "b": 2}
d2 = {"b": 99, "c": 3}
print({**d1, **d2})   # {'a': 1, 'b': 99, 'c': 3} — d2's b wins

# Merge preserving both values (combine, don't overwrite)
from collections import defaultdict
def merge_preserve_all(d1, d2):
    result = defaultdict(list)
    for d in (d1, d2):
        for key, val in d.items():
            result[key].append(val)
    return dict(result)

d1 = {"a": 1, "b": 2}
d2 = {"b": 99, "c": 3}
print(merge_preserve_all(d1, d2))  # {'a': [1], 'b': [2, 99], 'c': [3]}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 95. What is the Singleton design pattern in Python?

The Singleton pattern ensures **only one instance of a class exists** throughout the application lifetime.

```python
# Method 1: Using __new__
class Singleton:
    _instance = None

    def __new__(cls, *args, **kwargs):
        if cls._instance is None:
            cls._instance = super().__new__(cls)
        return cls._instance

s1 = Singleton()
s2 = Singleton()
print(s1 is s2)   # True — same object

# Method 2: Using a decorator
def singleton(cls):
    instances = {}
    def get_instance(*args, **kwargs):
        if cls not in instances:
            instances[cls] = cls(*args, **kwargs)
        return instances[cls]
    return get_instance

@singleton
class DatabaseConfig:
    def __init__(self, host, port):
        self.host = host
        self.port = port

db1 = DatabaseConfig("localhost", 5432)
db2 = DatabaseConfig("other", 3306)   # ignored — returns existing
print(db1 is db2)   # True

# Method 3: Using metaclass
class SingletonMeta(type):
    _instances = {}
    def __call__(cls, *args, **kwargs):
        if cls not in cls._instances:
            cls._instances[cls] = super().__call__(*args, **kwargs)
        return cls._instances[cls]

class AppConfig(metaclass=SingletonMeta):
    def __init__(self):
        self.debug = False
        self.log_level = "INFO"

# Method 4: Module-level singleton (most Pythonic!)
# config.py
# _instance = None
# def get_config():
#     global _instance
#     if _instance is None:
#         _instance = Config()
#     return _instance
# Python modules are singletons by nature — imported once!
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 96. How do you profile and optimize Python code?

```python
import cProfile
import timeit
import line_profiler
import memory_profiler

# 1. timeit — measure small code snippets
time_list_comp = timeit.timeit("[x**2 for x in range(1000)]", number=10000)
time_map = timeit.timeit("list(map(lambda x: x**2, range(1000)))", number=10000)
print(f"List comp: {time_list_comp:.4f}s, map: {time_map:.4f}s")

# 2. cProfile — full program profiling
def slow_function():
    return sum(i**2 for i in range(100_000))

cProfile.run("slow_function()")
# Shows: ncalls, tottime, percall, cumtime, filename:lineno(function)

# 3. Manual timing
import time
start = time.perf_counter()     # high-resolution timer
result = slow_function()
print(f"Took: {time.perf_counter() - start:.6f}s")

# Optimization techniques:
# 1. Use built-ins (sum, max, min) — implemented in C
# 2. List comprehensions over loops — faster
# 3. Local variables faster than global in functions
# 4. Use generators for large sequences (memory)
# 5. Avoid repeated lookups — cache in variable
# 6. Use NumPy for numerical operations
# 7. functools.lru_cache for repeated function calls
# 8. __slots__ for many instances

# Before optimization: always profile first!
# "Premature optimization is the root of all evil" — Donald Knuth

# Use sets for membership testing (O(1) vs O(n) for lists)
items = list(range(100_000))
items_set = set(items)

print(99999 in items)      # O(n) — slow
print(99999 in items_set)  # O(1) — instant
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 97. What are Python type hints? Why are they used?

Type hints (PEP 484, Python 3.5+) are **optional annotations** that specify the expected types of variables, function parameters, and return values — enabling static analysis without runtime enforcement.

```python
from typing import Optional, List, Dict, Tuple, Union, Any, Callable
from typing import TypeVar, Generic

# Basic type hints
def greet(name: str, age: int) -> str:
    return f"Hello {name}, you are {age} years old"

# Optional — parameter can be None
def find_user(user_id: int, default: Optional[str] = None) -> Optional[dict]:
    pass

# Complex types
def process_data(
    items: List[int],
    config: Dict[str, Any],
    transform: Callable[[int], int]
) -> Tuple[List[int], int]:
    pass

# Union — multiple possible types
def parse_value(value: Union[int, str, float]) -> str:
    return str(value)

# Python 3.10+ — simpler union syntax with |
def parse_v2(value: int | str | float) -> str:
    return str(value)

# Variable annotations
user_count: int = 0
user_names: List[str] = []

# TypeVar — generic functions
T = TypeVar("T")
def first(lst: List[T]) -> T:
    return lst[0]

# TypedDict — typed dictionaries
from typing import TypedDict
class UserDict(TypedDict):
    name: str
    age: int
    email: str

# Benefits of type hints:
# ✅ IDE autocomplete and error detection
# ✅ Static analysis with mypy: mypy script.py
# ✅ Documentation (self-documenting code)
# ✅ Catches bugs before runtime
# ✅ Better refactoring support

# ⚠️ Type hints are NOT enforced at runtime by default
# def add(a: int, b: int) -> int: return a + b
# add("hello", "world")  # works at runtime (no error)! But mypy catches it
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 98. How do you write unit tests in Python?

```python
import unittest

# Function to test
def divide(a, b):
    if b == 0:
        raise ZeroDivisionError("Cannot divide by zero")
    return a / b

def is_palindrome(s):
    s = s.lower().replace(" ", "")
    return s == s[::-1]

# Test class
class TestDivide(unittest.TestCase):
    def test_positive_numbers(self):
        self.assertEqual(divide(10, 2), 5.0)

    def test_negative_numbers(self):
        self.assertEqual(divide(-10, 2), -5.0)

    def test_float_result(self):
        self.assertAlmostEqual(divide(1, 3), 0.3333, places=4)

    def test_zero_division(self):
        with self.assertRaises(ZeroDivisionError):
            divide(10, 0)

    def setUp(self):    # runs before each test
        self.sample_data = [1, 2, 3]

    def tearDown(self): # runs after each test
        pass

class TestPalindrome(unittest.TestCase):
    def test_is_palindrome(self):
        self.assertTrue(is_palindrome("racecar"))
        self.assertTrue(is_palindrome("A man a plan a canal Panama"))

    def test_not_palindrome(self):
        self.assertFalse(is_palindrome("hello"))

# pytest (preferred over unittest — simpler syntax)
# pip install pytest
def test_divide_basic():
    assert divide(10, 2) == 5.0

def test_divide_zero():
    import pytest
    with pytest.raises(ZeroDivisionError):
        divide(10, 0)

def test_palindrome_true():
    assert is_palindrome("racecar") is True

# Run: python -m pytest tests/ -v
# Run: python -m unittest discover tests/

# Mocking
from unittest.mock import Mock, patch, MagicMock

def test_fetch_user():
    with patch("requests.get") as mock_get:
        mock_get.return_value.json.return_value = {"id": 1, "name": "Sisi"}
        mock_get.return_value.status_code = 200
        result = fetch_user(1)
        assert result["name"] == "Sisi"
        mock_get.assert_called_once_with("https://api.example.com/users/1")
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 99. What is virtual environment in Python and why is it important?

A virtual environment is an **isolated Python environment** with its own Python interpreter and packages — preventing conflicts between different projects.

```bash
# Without venv — all packages in global Python installation
# Project A needs Django 3.2
# Project B needs Django 4.2
# CONFLICT!

# Creating virtual environment
python -m venv myenv              # create venv in 'myenv' folder
python -m venv myenv --python=python3.11  # specific version

# Activating
source myenv/bin/activate         # Linux/macOS
myenv\Scripts\activate            # Windows
.\myenv\Scripts\Activate.ps1      # Windows PowerShell

# After activation — pip installs only in this venv
pip install django==4.2
pip install flask requests pandas

# Save dependencies
pip freeze > requirements.txt     # list all installed packages + versions

# requirements.txt example:
# Django==4.2.7
# Flask==3.0.0
# requests==2.31.0
# pandas==2.1.2

# Restore environment
pip install -r requirements.txt   # install all listed packages

# Deactivate
deactivate

# Tools that manage venvs:
# venv      — built-in (basic)
# virtualenv — older, more features
# conda     — for data science (manages Python versions too)
# pipenv    — combines pip + venv
# poetry    — modern dependency management + packaging
# pyenv     — manage multiple Python versions

# Best practice:
# - Never commit venv/ folder to git — add to .gitignore
# - Always commit requirements.txt
# - Use virtual environments for EVERY Python project
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 100. What are the latest features in Python 3.10, 3.11, 3.12, and 3.13?

| Version | Year | Key Features |
| ------- | ---- | ------------ |
| **3.10** | 2021 | Structural pattern matching (`match/case`), better error messages, `TypeAlias` |
| **3.11** | 2022 | 60% faster than 3.10, `tomllib`, exception groups (`ExceptionGroup`), `Self` type |
| **3.12** | 2023 | f-string improvements, `@override` decorator, `type` statement, `pathlib` improvements |
| **3.13** | 2024 | Free-threaded mode (no GIL!), JIT compiler (experimental), better REPL, improved errors |

```python
# Python 3.10 — match/case (pattern matching)
def handle_command(command):
    match command:
        case {"action": "quit"}:
            return "Quitting..."
        case {"action": "move", "direction": direction}:
            return f"Moving {direction}"
        case {"action": "attack", "weapon": weapon, "target": target}:
            return f"Attacking {target} with {weapon}"
        case _:
            return "Unknown command"

print(handle_command({"action": "move", "direction": "north"}))

# Match with types
def classify(value):
    match value:
        case int(n) if n > 0: return "positive int"
        case int(): return "non-positive int"
        case str(): return "string"
        case list(): return "list"
        case _: return "other"

# Python 3.11 — Exception groups
try:
    raise ExceptionGroup("multiple errors", [
        ValueError("invalid input"),
        TypeError("wrong type"),
        KeyError("missing key")
    ])
except* ValueError as eg:      # except* handles ExceptionGroup
    print(f"Value errors: {eg.exceptions}")
except* TypeError as eg:
    print(f"Type errors: {eg.exceptions}")

# Python 3.12 — type statement (type alias)
type Vector = list[float]      # cleaner than TypeAlias
type Matrix = list[Vector]

# f-string improvements — can now contain quotes
name = "Sisi"
print(f"{'Hello' if name else 'World'}")   # nested quotes now allowed!

# Python 3.13 — free-threaded mode (experimental)
# Run Python without GIL: python3.13t myapp.py
# Allows true parallelism in threads for CPU-bound tasks!

# Python 3.13 — improved REPL
# Multiline editing, color output, better history

# Check your Python version
import sys
print(sys.version)   # e.g., 3.12.0 (main, Oct 2 2023, ...)
print(sys.version_info)  # sys.version_info(major=3, minor=12, micro=0, ...)
```

**[⬆ Back to Top](#table-of-contents)**

<br>
<br>

<div align="center">

## 🎉 You've covered all 100 Python Interview Questions!

<br>

**If this repo helped you prepare, please give it a ⭐**

[![Star this repo](https://img.shields.io/github/stars/sisi-tarak/python-interview-questions?style=social)](https://github.com/sisi-tarak/python-interview-questions)


### 📲 Follow Sisi for more tech interview prep content

[![Instagram](https://img.shields.io/badge/Instagram-%40sisi__tarakk-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/sisi_tarakk)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sisindri%20Singamsetti-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sisitarak)
[![GitHub](https://img.shields.io/badge/GitHub-sisi--tarak-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sisi-tarak)

---

### 🤝 Want to contribute?

Found a mistake, have a better explanation, or want to add more questions?

**[Open a Pull Request](https://github.com/sisi-tarak/python-interview-questions/pulls)** — all contributions are welcome! 🙌

---

### 📦 More Interview Repos

| Status | Repository |
| ------ | ---------- |
| ✅ Live | [react-interview-questions](https://github.com/sisi-tarak/react-interview-questions) |
| ✅ Live | [mern-interview-questions](https://github.com/sisi-tarak/mern-interview-questions) |
| ✅ Live | [python-interview-questions](https://github.com/sisi-tarak/python-interview-questions) |
| 🔜 Coming | nodejs-interview-questions |
| 🔜 Coming | dsa-interview-questions |
| 🔜 Coming | java-interview-questions |

⭐ **Star this repo to get notified when new repos drop!**

---

## Disclaimer

The questions in this repository are compiled from frequently asked interview questions across MNC companies including TCS, Infosys, Wipro, Cognizant, HCL, Capgemini, Accenture, and product companies. We cannot guarantee these exact questions will appear in your interview. The goal is to build conceptual clarity and real-world Python understanding, not memorization.

Good luck with your interview! 😊

*Made with ❤️ by [Sisi](https://instagram.com/sisi_tarakk) | Helping Telugu tech students crack their dream jobs 🚀*

</div>
