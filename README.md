 # Introduction to Python
Python is a widely used general-purpose, high level programming language. 
Python is a programming language that lets you work quickly and integrate systems more efficiently. 
its syntax allows programmers to express their concepts in fewer lines of code. 

## Comments 

Comments in Python are used to provide explanations or annotations within your code. 
They are not executed by the Python interpreter and are meant to be human-readable.

##Single-Line Comments: Single-line comments are used for short comments and are preceded by the # symbol.
Everything on the same line after # is considered a comment and is ignored by the Python interpreter. 

This is a single-line comment 
```
 print("Hello, World")  This comment is at the end of a line of code
 
```
 
## Multi-Line Comments or Docstrings: 
Multi-line comments are typically used for longer explanations and documentation.
In Python, these are often represented as docstrings (used for documentation of functions, classes, and modules).
A docstring is enclosed in triple quotes (''' or """) and can span multiple lines

```
This is a multi-line comment or a docstring.
It can span multiple lines and is often used for documenting functions, classes, or modules.

def my_function():
    """
    This is also a docstring.
    It provides documentation for the function.
     """
    pass
```
# Introduction to Variables

Variables are simple containers for storing data values and Python has no commands for declaring a variable. 

1. ## Variable Naming Rules: 

Variable names are case-sensitive, meaning "myVariable" and "myvariable" are treated as different variables. 

Variable names must start with a letter (a-z, A-Z) or an underscore (_) character. 

Subsequent characters in variable names can include letters, digits (0-9), and underscores. 

Variable names cannot contain spaces or special characters like @, $, %, etc. 

2. ## Variable Assignment: 

Assigning a value to a variable is known as variable assignment. In Python, you use the = operator for assignment. 

For example, to assign the integer value 10 to a variable called "x," you would write: x = 10. 

3. ## Data Types: 

Variables have associated data types that define the kind of data they can hold. Common data types include: 

Integers (int): Whole numbers, e.g., 5, -3, 1000. 

Floating-point numbers (float): Decimal numbers, e.g., 3.14, -0.5, 2.0. 

Strings (str): Text, e.g., "Hello, World!". 

Booleans (bool): True or False. 

 

4. ## Variable Usage: 

Once a value is assigned to a variable, you can use that variable in expressions, calculations, or simply to display the value. 

For example, you can perform operations like addition, subtraction, and concatenation on variables. 

5. ## Variable Scope: 

Variables have a scope, which defines where in the code they are accessible.
Variables can be local (only accessible in a specific function or block) or global (accessible throughout the entire program). 

6. ## Reassignment: 

You can change the value of a variable by assigning it a new value. This is called reassignment. 

For example, you can do x = 20 to change the value of "x" to 20. 

Example of a code :
```
# Variable assignment
x = 10
y = "Hello, World"

# Variable usage
result = x + 5
greeting = y + " Welcome!"

# Variable reassignment
x = 20

# Displaying values
print("Result:", result)
print("Greeting:", greeting)
print("Updated x:", x)
```


# Introduction to Data Types

Data types in computer programming refer to the classification or categorization of data based on its type or value. 
Different data types are used to represent various kinds of information, such as numbers, text, and more, in a format that the computer can understand and manipulate. 

 ## Common data type

 Integer (int): This data type is used to represent whole numbers, both positive and negative, without any decimal points. Examples include -1, 0, 42.

Floating-Point (float): Floating-point data types are used to represent numbers with decimal points or fractional parts. Examples include -3.14, 2.71828.

String (str): Strings are used to represent sequences of characters, such as text. "Hello, World!" is an example of a string.

Boolean (bool): Boolean data types have only two possible values: True and False. They are often used for logical operations and conditional statements.

List: Lists are used to store ordered collections of items. Elements in a list can have different data types.
For example, [1,2,3] is a list of integers.

Tuple: Tuples are similar to lists but are immutable, meaning their elements cannot be changed once they are defined.
They are often used to group related values. An example is (1, 'apple', 3.14).

Dictionary (dict): Dictionaries store key-value pairs. Each key is associated with a value, allowing for efficient lookup and storage of data.
For example, {'name': 'John', 'age': 30} is a dictionary.

Set: Sets are used to store collections of unique values. They do not allow duplicate elements. An example is {1, 2, 3}.

None: This data type represents the absence of a value or a null value. It is often used to indicate missing or uninitialized data.

Custom Data Types (Objects, Classes): In many programming languages, you can define your own custom data types using objects or classes. 
These allow you to encapsulate data and functionality into user-defined structures.


# Operators 
 Operators are symbols or special keywords used to perform operations on variables and values. 
 Python provides a variety of operators, which can be categorized into the following groups:


 ## Arithmetic Operators:

+ + (Addition): Adds two numbers.
  

-  (Subtraction) -: Subtracts the right operand from the left operand.
  
- (Multiplication) * : Multiplies two numbers.
 
- (Division): / Divides the left operand by the right operand, yielding a floating-point result.

// (Floor Division): Divides the left operand by the right operand and truncates the decimal part to the nearest integer.

% (Modulus): Returns the remainder of the division.

** (Exponentiation): Raises the left operand to the power of the right operand.
  
## Comparison Operators:

== (Equal): Checks if two values are equal.

!= (Not Equal): Checks if two values are not equal.

< (Less Than): Checks if the left operand is less than the right operand.

> (Greater Than): Checks if the left operand is greater than the right operand.
> 
<= (Less Than or Equal To): Checks if the left operand is less than or equal to the right operand.

>= (Greater Than or Equal To): Checks if the left operand is greater than or equal to the right operand.

## Logical Operators:

and (Logical AND): Returns True if both operands are True.

or (Logical OR): Returns True if at least one of the operands is True.

not (Logical NOT): Inverts the logical value of the operand.

## Assignment Operators:

= (Assignment): Assigns a value to a variable.

+= (Addition Assignment): Adds the right operand to the left operand and assigns the result to the left operand.

-= (Subtraction Assignment): Subtracts the right operand from the left operand and assigns the result to the left operand.

*= (Multiplication Assignment): Multiplies the left operand by the right operand and assigns the result to the left operand.

/= (Division Assignment): Divides the left operand by the right operand and assigns the result to the left operand.

//= (Floor Division Assignment): Performs floor division and assigns the result to the left operand.

%= (Modulus Assignment): Calculates the modulus and assigns the result to the left operand.

**= (Exponentiation Assignment): Raises the left operand to the power of the right operand and assigns the result to the left operand.

## Membership Operators:

in: Returns True if a value is found in a sequence (e.g., a list, tuple, or string).

not in: Returns True if a value is not found in a sequence.

## Identity Operators:

is: Returns True if two variables reference the same object.

is not: Returns True if two variables reference different objects.

Bitwise Operators (for working with binary representations):

& (Bitwise AND)

| (Bitwise OR)

^ (Bitwise XOR)

~ (Bitwise NOT)

<< (Left Shift)

>> (Right Shift)




- ## Casting
In Python, casting refers to the process of converting one data type into another. This is also known as type conversion or typecasting.

Here are some of the most commonly used casting functions in Python:

- int(): This function is used to convert a value to an integer.
x = int(3.14)  # x will be 3
float(): Use this function to convert a value to a floating-point number.
y = float("3.14")  # y will be 3.14
srt(): It comverts a value to a string.
s = str(42)  # s will be the string "42"
bool(): This function converts a value to a boolean.
b = bool(0)  # b will be False
list(): Converts a sequence (e.g., a string or tuple) into a list.
my_list = list("hello")  # my_list will be ['h', 'e', 'l', 'l', 'o']
ord() and chr(): These functions are used to convert characters to their Unicode code points
and vice versa.
code = ord('A')  # code will be 65
char = chr(65)   # char will be 'A'
In Python, some operations might not work as intended if you mix incompatible data types, so typecasting can be a useful tool to manage data effectively.
Datatypes:
Python is a dynamically-typed language, which means that you don't need to declare the data type of a variable explicitly. Python infers the data type based on the value assigned to the variable. Python supports a wide range of data types, including:

Integers These represent numbers in an unlimited range. This is only limited by a machine’s
memory.
Booleans: Evaluate to ‘True or False’, 1 or 0 respectively.
Floating point numbers: Floating-point numbers represent double-precision numbers.
Complex numbers: Complex numbers represent numbers as a pair of double-precision numbers.
Strings: A sequence of Unicode characters e.g. a word or a sentence that can be manipulated.
Manipulating booleans
 Syntax  Description
 a or b  
If either a or b is True, then the result will be True. 

If both a and b are False then the result will be False.
 a and b     If a and b are True, then the result will be True. Otherwise, the result will be False.
 not a   If a is True, False is returned. If a is False, True is returned.

WEEK 3 day 1 - 5
Here are all of the methods of list objects:
list.append(x)
Adds an item x to the end of the list.
list.extend(iterable)
Extends the list by appending all the items from the iterable.
list.insert(i, x)
Inserts an item x at the given position i. The first argument is the index of the element before which to insert.
list.remove(x)
Removes the first item in the list whose value is equal to x. Raises a ValueError if there is no such item.
list.pop([i])
Removes and returns the item at the given position i in the list. If no index is specified, a.pop() removes and returns the last item.
list.clear()
Removes all items from the list.
list.index(x[, start[, end]])
Returns the zero-based index of the first item in the list whose value is equal to x. Optional start and end arguments limit the search to a specific subsequence.
list.count(x)
Returns the number of times x appears in the list.
list.sort(key=None, reverse=False)
Sorts the items of the list in place. Optional arguments key and reverse can be used for sort customization.
list.reverse()
Reverses the elements of the list in place.
list.copy()
Returns a shallow copy of the list, equivalent to a[:].
## Here are code examples for each of the listed list methods in Python:

``` # Initialize a sample list for demonstration my_list = [1, 2, 3, 4]

list.append(x): Adds an item to the end of the list.
my_list.append(5)

list.extend(iterable): Extends the list by appending all items from the iterable.
my_list.extend([6, 7])

list.insert(i, x): Inserts an item x at a given position.
my_list.insert(1, 10)

list.remove(x): Removes the first item equal to x.
my_list.remove(3)

list.pop([i]): Removes and returns an item at the given position.
popped_item = my_list.pop(2)

list.clear(): Removes all items from the list.
my_list.clear()

Reinitialize the list for further examples
my_list = [3, 1, 4, 1, 5, 9, 2, 6, 5, 3, 5]

list.index(x[, start[, end]]): Find the first index of an item x.
index = my_list.index(5)

list.count(x): Count the number of occurrences of x in the list.
count = my_list.count(5)

list.sort(key=None, reverse=False): Sort the list.
my_list.sort()

list.reverse(): Reverse the list in place.
my_list.reverse()

list.copy(): Create a shallow copy of the list.
copy_of_list = my_list.copy()

Print the results
print("After append:", my_list) print("After extend:", my_list) print("After insert:", my_list) print("After remove:", my_list) print("Popped item:", popped_item) print("After clear:", my_list) print("Index of 5:", index) print("Count of 5:", count) print("Sorted list:", my_list) print("Reversed list:", my_list) print("Shallow copy:", copy_of_list)

```

Using Lists as a Stack (Last-In, First-Out):
Lists can work like a stack, where the last item added is the first one retrieved (Last-In, First-Out or LIFO). To add an item to the top of the stack, use the append() method. To retrieve an item from the top of the stack, use pop() without specifying an index.

Example
stack = [3, 4, 5]
stack.append(6)
stack.append(7)
stack.pop()  # Retrieves and removes the top item.

Using Lists as a Queue (First-In, First-Out):
Lists can also mimic a queue, where the first item added is the first to be retrieved (First-In, First-Out or FIFO). However, lists are not efficient for this because adding or removing items from the beginning requires shifting other elements. For efficient queue operations, use collections.deque which allows fast appends and pops from both ends.

Example using collections.deque:
from collections import deque
queue = deque(["Eric", "John", "Michael"])
queue.append("Terry")  # Adding an item to the end.
queue.popleft()  # Removing the first item efficiently.

In summary, lists can serve as both stacks and queues, but for efficient queue operations, it's recommended to use collections.deque. Stacks follow Last-In, First-Out (LIFO) while queues follow First-In, First-Out (FIFO).

LIST COMPREHENSIONS
List comprehensions are a concise way to create lists in Python. They are often used to generate new lists by applying operations to each element of an existing sequence or iterable. List comprehensions can also be used to filter elements based on certain conditions. Here's an informative breakdown of how list comprehensions work:

Creatin a list of squares:
You can creat a list of square using a 'for' loop:

    squares = []
    for x in range(10):
    squares.append(x**2)

Alternatively, use a list comprehension for a more concise and readable approach:

squares = [x**2 for x in range(10)]
List Comprehension Structure:
A list comprehension consists of square brackets [...] containing an expression followed by one or more for or if clauses. The result is a new list generated by evaluating the expression in the context of the following for and if clauses.

Combining Elements from Two Lists: You can use list comprehensions to combine elements from two lists based on certain conditions:
[(x, y) for x in [1, 2, 3] for y in [3, 1, 4] if x != y]

Order of for and if Statements:
Note that the order of for and if statements in a list comprehension matches the structure of equivalent for loops. 5. Handling Tuples in Expressions:

If the expression is a tuple (e.g., (x, y)), it must be parenthesized.

Examples of List Comprehensions:

Creating a new list with doubled values, filtering out negative numbers, applying a function to elements, and stripping whitespace from strings.

Creating a list of 2-tuples (number, square) and flattening a nested list.
Complex expressions and nested functions can be used in list comprehensions.

Error Handling:

If the tuple is not parenthesized, it can result in a syntax error.

Advanced Example:
Using the math module to round the value of pi to different decimal places for a list. In

summary, list comprehensions provide a concise and expressive way to create lists, apply operations, and filter elements from existing sequences or iterables. They are a powerful feature for Python programmers and can simplify code while making it more readable.

                        # NESTED LIST COMPREHENSIONS
Nested List Comprehensions:
List comprehensions can be nested, allowing for more complex transformations and operations.
Example: Transposing a Matrix:
Consider a 3x4 matrix represented as a list of lists.
The goal is to transpose the matrix, switching rows and columns.
List Comprehension Approach:
A nested list comprehension can achieve matrix transposition elegantly:
[[row[i] for row in matrix] for i in range(4)]

Equivalent for Loop Approach:
The nested list comprehension is equivalent to a series of for loops:
``` transposed = [] for i in range(4): transposed.append([row[i] for row in matrix])

## Further Expanded Approach:

-    The equivalent for loop approach can be broken down into more detail:

transposed = [] for i in range(4): transposed_row = [] for row in matrix: transposed_row.append(row[i]) transposed.append(transposed_row)


## Using Built-In Function zip():

-    In real-world scenarios, built-in functions are preferred for readability and efficiency.
-    The zip() function transposes the matrix efficiently:

list(zip(*matrix)) ```

In summary, the provided examples demonstrate how to transpose a matrix using both nested list comprehensions and the 'zip()' function. While list comprehensions are a powerful tool, built-in functions like 'zip()' are often preferred for more complex operations due to their readability and efficiency.






