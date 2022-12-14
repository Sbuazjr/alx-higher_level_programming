0x03. Python - Data Structures: Lists, Tuples

About

An introductory project on:

1. Lists, their methods, and how to use them

2. How to use lists as stacks and queues

3. List comprehensions and how to use them

4. Tuples and how to use them

5. Sequences

6. Tuple packing

7. Sequence unpacking

8. The del statement and how to use it

Requirements

Python Scripts

Python 3.4

pep8 1.7

C Files

Ubuntu 14.04 LTS

gcc 4.8.4 using the flags -Wall -Werror -Wextra and -pedantic

Betty Style

File Descriptions

Mandatory

0-print_list_integer.py - Write a function that prints all integers of a list.

Prototype: def print_list_integer(my_list=[]):
Format: one integer per line
You are not allowed to import any module
You can assume that the list only contains integers
You are not allowed to cast integers into strings
You have to use str.format() to print integers

1-element_at.py - Write a function that retrieves an element from a list like on C.

Prototype: def element_at(my_list, idx):
If idx is negative, the function should return None
If idx is out of range (> of number of element in my_list), the function should return None
You are not allowed to import any module
You are not allowed to use try/except

2-replace_in_list.py - Write a function that replaces an element of a list at a specific position (like in C).

Prototype: def replace_in_list(my_list, idx, element):
If idx is negative, the function should not modify anything, and returns the original list
If idx is out of range (> of number of element in my_list), the function should not modify anything, and returns the original list
You are not allowed to import any module
You are not allowed to use try/except

3-print_reversed_list_integer.py - Write a function that prints all integers of a list, in reverse order.

Prototype: def print_reversed_list_integer(my_list=[]):
Format: one integer per line. See example
You are not allowed to import any module
You can assume that the list only contains integers
You are not allowed to cast integers into strings
You have to use str.format() to print integers

4-new_in_list.py - Write a function that replaces an element in a list at a specific position without modifying the original list (like in C).

Prototype: def new_in_list(my_list, idx, element):
If idx is negative, the function should return a copy of the original list
If idx is out of range (> of number of element in my_list), the function should return a copy of the original list
You are not allowed to import any module
You are not allowed to use try/except

5-no_c.py - Write a function that removes all characters c and C from a string.

Prototype: def no_c(my_string):
The function shoud return the new string
You are not allowed to import any module
You are not allowed to use str.replace()

6-print_matrix_integer.py - Write a function that prints a matrix of integers.

Prototype: def print_matrix_integer(matrix=[[]]):
Format: see example
You are not allowed to import any module
You can assume that the list only contains integers
You are not allowed to cast integers into strings
You have to use str.format() to print integers
 
7-add_tuple.py - Write a function that adds 2 tuples.

Prototype: def add_tuple(tuple_a=(), tuple_b=()):
Returns a tuple with 2 integers:
The first element should be the addition of the first element of each argument
The second element should be the addition of the second element of each argument
You are not allowed to import any module
You can assume that the two tuples will only contain integers
If a tuple is smaller than 2, use the value 0 for each missing integer
If a tuple is bigger than 2, use only the first 2 integers

8-multiple_returns.py - Write a function that returns a tuple with the length of a string and its first character.

Prototype: def multiple_returns(sentence):
If the sentence is empty, the first character should be equal to None
You are not allowed to import any module

9-max_integer.py - Write a function that finds the biggest integer of a list.

Prototype: def max_integer(my_list=[]):
If the list is empty, return None
You can assume that the list only contains integers
You are not allowed to import any module
You are not allowed to use the builtin max()

10-divisible_by_2.py - Write a function that finds all multiples of 2 in a list.

Prototype: def divisible_by_2(my_list=[]):
Return a new list with True or False, depending on wether the integer at the same position in the original list is a multiple of 2
The new list should have the same size as the original list
You are not allowed to import any module

11-delete_at.py - Write a function that deletes the item at a specific position in a list.

Prototype: def delete_at(my_list=[], idx=0):
If idx is negative or out of range, nothing change
You are not allowed to use pop()
You are not allowed to import any module

12-switch.py - Complete the [source code](https://intranet.hbtn.io/rltoken/RfHRsVZK5IVZ5e4-0WAOJQ in order to switch value of a and b

Your program should be exactly 5 lines long

Advanced

100-print_python_list_info.c - Create a C function that prints some basic info about Python lists.

Prototype: void print_python_list_info(PyObject *p);
Your shared library will be compiled with this command line: gcc -Wall -Werror -Wextra -pedantic -std=c99 -shared -Wl,-soname,PyList -o libPyList.so -fPIC -I/usr/include/python3.4 100-print_python_list_info.c
