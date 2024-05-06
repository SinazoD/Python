# Python
What is Python?

Python is a popular programming language that was created by Guido van Rossum and released in 1991.

It is used for:
•	web development (server-side),
•	software development,
•	mathematics,
•	system scripting.

Syntax

Indentation: 

•	In Python, indentation refers to the spaces or tabs at the beginning of a line of code that determines its grouping within a block of code.
•	 Python uses indentation to define blocks of code, unlike some languages that uses key words or braces.
Example
If condition:
       #indented block
        Statement 1
        Statement 2
        #end of indented block

Comments: 

•	In Python Single line comments are created using the hash (#) symbol and multi-line symbols are created using triple quotes (’’’or”””).

Variables: 
•	In python variables are simply declared by assigning a value to them using the equal operator, unlike some languages where you need to first declare a datatype of a variable.

Naming conventions: 

•	Variables and function names in python are case sensitive and should follow certain conventions, such as using lowercase letters with underscores (snake_case) for variables and lowercase letters with no underscores(lowwercamelcase) for functions.

Python uses a new line to complete a command as opposed to other languages which often use semicolons or parenthesis. 

Data types

Here are some commonly used data types in python:

Numeric data types
•	The int type represents integers and the float represents decimal numbers.
Strings
•	Strings are used to represent text data.
•	They can be enclosed using single quotes (‘) or double quotes (“).

Lists
•	Lists are unordered list of collections of items enclosed with in square brackets [].
•	They can hold elements of different data types.
•	They can be modified mutable.

Tuples
•	These are like lists but are modified immutable, meaning they can not be modified after creation.
•	The are enclosed within parenthesis ().

Dictionaries
•	These are key value pairs enclosed with curly braces {}.
•	They allow you to store and retrieve values based on unique keys.

Sets
•	Sets are unordered collections of unique items enclosed with curly braces {}.
•	They are useful for performing mathematical operations like union, intersection and difference.

Control structures

Control structures allow you to control the flow of execution based on specific conditions.

Conditional statements

•	Allow you to execute certain blocks of code based on whether the condition is true or false.
•	if, elif, and else statements are used to perform different actions based on certain conditions.
•	If is used to check a condition
•	Elif (short for elseif) allows for additional condition checks.

Loops

•	Python provides two types of loops - for and while. 
•	for loops are used to iterate over a sequence
•	 while loops repeatedly execute a block of code until a condition becomes false. 

Break and continue:

•	 The break statement is used to exit a loop prematurely, while the continue statement skips the current iteration and moves to the next iteration.

Functions

A function in Python is a group of organised reusable code that is used to perform a single, related action. They perform better modularity for your application and a high degree code of reusing.

Defining Function:

•	Functions are defined using the def key word followed by the name and the parentheses ().
•	You can also define parameters inside the parentheses.
•	The code block within a function starts with a semi colon (:).


Returning Values:

•	Functions can return one or more values using the return statement.
•	If no return is specified, the function returns none by default.

Function Arguments:

•	The process of a function often depends on certain data provided to it while calling it. 
•	While defining a function, you must give a list of variables in which the data passed to it is collected. 
•	The variables in the parentheses are called formal arguments.
When the function is called, value to each of the formal arguments must be provided. Those are called actual arguments.

Recursion:

•	Python allows you to define recursive functions, which are functions that call themselves within their own body.


Control flow structures and loops:

In programming, control flow refers to the order in which the statements are executed within a program. Conditional statements allow us to control the flow of execution based on certain conditions. 

The most common conditional statement in Python is the if statement.

•	It allows us to execute a block of code only if a certain condition is true. 
•	The if statement can be followed by an optional else statement, which is executed only if the condition is false.

We can also use the elif statement to include multiple conditions.

•	It allows us to check for additional conditions after the initial if statement.
•	 The elif statement is only executed if the previous conditions are false.


Loops

Loops are used in programming to repeatedly execute a block of code until a certain condition is met. Python has two types of loops, for loops and while loops.

For loops

•	The for loop iterates over a sequence (such as a list, tuple, or string) or an iterable object (such as a range) and executes a block of code for each item in the sequence or iterable.

While loops

•	The while loop continues to execute a block of code as long as a certain condition is true. 
•	It repeatedly checks the condition before each iteration.

Data Structures and Functions

Data structures are essential components of any programming language as they allow the storage and organization of data.

Types of data structures

Lists

•	Lists can hold multiple elements of different data types.
•	It is an ordered collection that allows for dynamic resizing, insertion, and deletion of elements. 
•	Lists are created using square brackets [] and elements are separated by commas. 
•	Indexing and slicing operations can be performed on lists to access or modify specific elements.

Tuples

•	Tuples are also used to store multiple elements like lists.
•	However, tuples are immutable, meaning their values cannot be modified once assigned. 
•	Tuples are created using parentheses () and elements are separated by commas.
•	Tuples are often used to group related data together or when there is a need for an unchangeable collection of values.

Dictionaries

•	Dictionaries are unordered collections of key-value pairs. 
•	Each element in a dictionary is identified by its unique key, which is used to access the corresponding value.
•	 Dictionaries are created using curly braces {} and key value pairs are separated by colons (:). 
•	Dictionaries are useful when storing and retrieving data in a more descriptive and meaningful way.

Sets

•	A set in Python is an unordered collection of unique elements.
•	 It does not allow duplicate values. Sets are created using curly braces {} or the set () function. 
•	Sets provide operations such as union, intersection, and difference, making them useful for mathematical operations and eliminating duplicate elements from other collections.

Functions

Functions in Python are blocks of reusable code that perform specific tasks. They are essential for modular programming, code reusability, and organizing complex programs. 

Python offers both built-in functions and user-defined functions.

User-defined functions

•	User-defined functions are defined using the def keyword followed by a function name, parentheses (), and a colon (:). 
•	The body of the function is indented and contains the code to be executed when the function is called. 
•	Functions can have parameters, which act as placeholders for values, and can return values using the return statement.

Built-in Functions

•	Python comes with a vast set of built-in functions that perform a variety of operations. 
•	These functions cover a wide range of tasks, including mathematical calculations, string manipulations, input/output operations, type conversions, and more. 
•	Some commonly used built-in functions are print(), len(), type(), range(), and input().



