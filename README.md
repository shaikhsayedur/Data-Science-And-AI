*Description:-

*Introduction of Python:-
                      - python is a high level , easy to learn programming language that is widely used in Data science .
- Python have easy to Write & Read Syntax.
- Python have large no.of labraries.
-Strong communication Supports.

*Why Python For Data Science:-
                           -In Data Science Python is Used to collect,clean,analyze,visualize and help to predict data.
-It's used Labraries like 
Pandas
Numpy
Matplotib
Scikit-learn

^^^^
# Variaables and DataTypes :-
                            - Variables are containers for storing data values.
                            - You don’t need to declare the type; Python automatically understands it.
                            - python variables are case sensitive.
                            - pyhton allow assinging values to multiple variables in a single line.
*Example:-
x = 10 ----> x is name of the variable and 10 is value store in x variable.

*Datatype :-
x = " hello " ----> String
y = 10  -----> integer
z = 3.4 -----> float
a = True ----> Boolean
b = 1+2j ----> Complex

*Pyhton-TypeCasting:-
                   -Type Casting in Python refers to the process of converting the data type of a variable from one type to another, such as from a string to an integer, a float to an integer, etc.

# Data Structure in pyhton :-

*Data Type :-
                -User or Developer define only one value.
*Data Structure :-
                 -User or Developer can define more than one values.
*Matrix :-
          -tables(rows and columns )
^^^^^^
matrix = collection of data structures .
data structure = collection of data types.

^^^^^
#python Data Structure are devided into 2 types :-
                                                 1) Inbuild DS :- List , Tuples , Set , Dict .
                                                 2) User def DS :- Stack, Linkedlist , Heap , Tree , ( normally used by some labraries ).


^^^^^^
# Inbuild Data Structure
1) List :-
         - List is Growable.
         - List define with []
         - Duplicates are allowed.
         - Multiple datatypes can declare.
         - List is Mutable (you can change values).

* Methods of List :-
1) append() :-
- It's a build in method in pyhton used to add an item to the end of a list.
2) copy() :-
- copy() is a built-in method used to create a shallow copy of a list.
3) Count() :-
- count() returns the number of times a specific value appears in a list.
4) pop() :-
- pop() removes and returns an element from a list by index; if no index is given, it removes the last item.
5) remove() :-
- remove() deletes the first occurrence of a specified value from the list (does not return it).
6) Difference Between pop() and remove():-
- pop(index) removes and returns an item by index.
- remove(value) deletes the first matching value (does not return it).
7) insert():-
- insert(index, value) adds a value at the specified index in the list without replacing existing elements.
8) extned():-
-extend() adds each element from another list to the end of the current list.
9) reverse() :-
- reverse() reverses the elements of the list in place (modifies the original list).
10) sort() :-
- sort() arranges the elements of a list in ascending (default) or descending order.
11) clear() :-
- clear() removes all elements from the list, making it an empty list.
12) del listname :-
- del deletes the entire list from memory (not just its contents).
13) len() :-
- len() returns the total number of items in a list.

^^^^^
#pyhton indexing :-
- pyhton index begins with 0 .
- index can be divided into 3 part.
1) forword indexing -- left to right.
2) backword indexing -- right to left.
3) step indexing -- every step count jumpes.

^^^^^
#Tuple :-

-Tuple is an ordered collection of elements.
-Tuple are immutable.
-Once created, you cannot change its values.
ex----> tup1 = (1,2,3,4,"rehan") # tuple

🔹 Only 2 Built-in Tuple Methods:
1) count(x)	:-
-Counts how many times x appears	
2)index(x) :-
-Returns the first index where x is located	.

# Dictionary :-
- Dictionary is an unordered collection of key values pairs enclosed with {}.
- Dict is Mutable.
- keys() :-
-Returns a view of all the keys.
- values() :-
- Returns a view of all the values.
- update() :-
- Updates dictionary with another dictionary or key-value pair.
- pop():-
- Removes a key and returns its value.
- clear() :-
- clear all dict elements.

# Set :-
- set is an unorderd collection of elemnts enclosed in {}.
- Duplicates are not allowed in set.
- Automatically removes repeated items
- s.add(4) - add new element
- s.remove(2)  # remove if found , Error if not found
- s.discard(5) # No error if not found
- s.union(s2) # Combines sets (all unique elements)
- intersection() # print Common elements from two sets
* Superset , Subset , Disjoint :-
- issuperset() :-
-Checks if a set contains all elements of another set.
- issubset():-
- Checks if all elements of one set are present in another.
- isdisjoint() :-
- Checks if two sets have no elements in common.

# range() :-
- range() is used to generate a sequence of numbers.
- example ---> list(range(0,10)) 
- [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
- start → (Optional) Starting number (default is 0)
- stop → (Required) The number at which the range stops (not included)
- step → (Optional) The increment (default is 1)
* Common Use Cases:-
- For loops
- Generating sequences
- Iterating indexes in lists

^^^^^
# Operators in pyhton :-
- Operators :-
- Symbols that perform operations on variables and values.
- ex:- +, -, *, /, ==, and, etc.
- Operands :-
- The values or variables on which the operator works.

* Types of operators :-
1) Arithmetic Operators :-
- Used for mathematical calculations.
-  +  ---> Addition  ---> 'a + b'
-  -  ---> Subtraction ---> 'a - b'
-  *  ---> Multiplication ---> 'a * b'
-  /   ---> Division ---> 'a / b'
-  // ---> Floor Division ---> 'a // b'
-  % ---> Modulus ---> 'a % b' (remainder)
-  ** ---> Exponentiation ---> 'a ** b' (power) 
2) Comparison(Relational) operators :-
- Used to compare values.
- == ---> Equal to ---> 'a == b'
- !=  ---> Not equal to ---> 'a != b'
-  > ---> Greater than ---> 'a > b'
-  < ---> Less than ---> 'a < b'
-  >= ---> Greater or equal ---> 'a >= b'
-  <= ---> Less or equal ---> 'a <= b'
3) Assignment Operators :-
- Assignment operators are used to assign values to variables.
- The basic operator is ' = '.
- but Python offers several shortcut operators that combine assignment with other operations like addition, subtraction, multiplication, etc.
- ex ---> x = 10 # Assigns the value 10 to variable x.
- '+=' ---> 'x += 5' ---> 'x = x + 5' ---> Adds and assigns.
- '-=' ---> 'x -= 3' ---> 'x = x - 3' ---> Subtracts and assigns.
- '*=' ---> 'x *= 2' ---> 'x = x * 2' ---> Multiplies and assigns.
- '/=' ---> 'x /= 4' ---> 'x = x / 4' ---> Divides and assigns.
4) Logical Operators :-
- Logical operators are used to combine multiple Boolean conditions and return either True or False.
- and -----> Returns True only if both conditions are True.
- or ---->  Returns True if at least one condition is True.
- not ---> Reverses the result — True becomes False.
5) Unary Operator :-
- Unary operators are operators that operate on only one operand.
- ' - ' ----> Unary Minus	----> Negates the value (makes it negative).

# Number System Conversion :-

- Number systems are ways to represent numbers in different bases:
- Decimal – Base 10 (0–9), our regular number system.
- Binary – Base 2 (0, 1), used in computers.
- Octal – Base 8 (0–7), used in low-level computing.
- Hexadecimal – Base 16 (0–9, A–F), compact form for binary.

* Python provides built-in functions to convert between these systems:
- bin() – Converts a decimal to binary.
- oct() – Converts a decimal to octal.
- hex() – Converts a decimal to hexadecimal.

# Swap Variables in python :-
- In Python, swapping values between two variables is very easy and doesn’t need a third variable.
- ex :- a, b = b, a

# Introduce id() :-
- The id() function returns the unique memory address (identity) of an object in Python.
- ex :- id(object) 

^^^^
# String :-
- A string is a sequence of characters enclosed in quotes — single ('), double ("), or triple (''' or """).
- ex :- name = 'Rehan'
greet = "Hello!"
paragraph = """This is a
multi-line string."""
- strings are immutable.

* methods :-
- upper() --->  Converts to UPPERCASE
- lower() ---> Converts to lowercase
- title() ---> Capitalizes first letter of each word
- strip() ---> Removes leading/trailing spaces
- replace() ---> Replaces part of the string
- split() ---> Splits into a list
- join() ---> Joins list elements into string
- find() ---> Finds index of a substring 
- rfind() ---> Finds last index of substring
- count() ---> Counts occurrences 
- startswith() ---> Checks if starts with substring 
- endswith() ---> Checks if ends with substring 
- isalpha() ---> True if all characters are letters
- isdigit() ---> True if all characters are digits
* Escape :-
- \n ---> New line
- \t  ---> Tab 
- \\ ---> Backslash
- \' ---> Single quote
- \" ---> Double quote 
* Raw Strings :-
- Ignore escape characters by prefixing r:

# Bitwise Operator :-
- Bitwise operators operate on integers at the binary (bit) level.
- They compare or manipulate individual bits (0s and 1s) of numbers.
- &	---> AND ---> 1 if both bits are 1.
- | ---> or ---> 1 if at least one bit is 1	.
- ~ ---> complement ---> first thing we need to understand what is mean by complement.
complement means it will do reverse of the binary format i.e. - ~0 it will give you 1 ~1 it will give 0.
12 binary format is 00001100 ( complement of ~00001100 reverse the number - 11110011 which is (-13).
- ^ ---> XOR ---> 1 if bits are different	.
- << ---> left shift ---> Shifts bits left (adds 0s at right)	
- >> ---> right shift ---> Shifts bits right (drops bits at right)	
