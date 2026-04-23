# Leaning Python 

## Fundamentals Python

### Introduction

### Intro to Python

Basic syntax and constructs: variables, data types (int, float, bool, str), expressions, operators, control flow (if/elif/else), loops (for, while), basic error handling with try/except, and importing modules. Understand indentation significance and how to write and run simple functions.

### Python Lists & Strings

Lists: ordered, mutable collections; creation, indexing, slicing, methods (append, extend, insert, pop, remove, sort, reverse), list comprehensions, and common patterns (iteration, mapping, filtering).
Strings: immutable sequences of characters; creation, indexing, slicing, formatting (f-strings, format()), common methods (split, join, replace, lower/upper, strip), and basic regex usage for pattern matching.

### Dictionaries & Reading, Writing & Appending to files

Dictionaries: key-value mappings; creation, accessing values with keys, .get(), adding/updating/removing items, iterating keys/values/items, nested dictionaries, and use cases.
File I/O: opening files with open() and context managers (with), reading modes ('r', 'w', 'a', 'rb', 'wb'), reading methods (read, readline, readlines), writing and appending, encoding considerations, and basic CSV/JSON handling using csv and json modules.

### Sets, Tuples & Decorators with Args and Kwargs

Sets: unordered, unique collections; creation, membership tests, set operations (union, intersection, difference), useful for deduplication and membership checks.
Tuples: ordered, immutable sequences; creation, unpacking, using as dictionary keys, and when immutability is desirable.
Decorators: higher-order functions that wrap other functions to modify behavior; function decorator syntax using @decorator; common patterns for logging, timing, caching; use of *args and **kwargs to accept arbitrary positional and keyword arguments in wrapper functions.

### Object Oriented Programming

Core OOP concepts in Python: classes and instances, init constructor, instance vs class attributes, methods, inheritance, method overriding, super(), encapsulation (convention: single underscore), properties (@property), magic methods (str, repr, eq, len, iter), and composition vs inheritance. Practical patterns: designing small, testable classes and using dataclasses for boilerplate reduction.