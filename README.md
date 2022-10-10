# Transform Operation

## String Transformation
- <b>upper()</b> <br>
The upper() method converts all lowercase characters in a string into uppercase characters and returns it.

- <b>lower()</b> <br>
The lower() method converts all uppercase characters in a string into lowercase characters and returns it.

- <b>rstrip()</b> <br>
The rstrip() method returns a copy of the string with trailing characters removed (based on the string argument passed).

- <b>lstrip()</b> <br>
The lstrip() method returns a copy of the string with leading characters removed (based on the string argument passed). The lstrip() removes characters from the left based on the argument (a string specifying the set of characters to be removed).

- <b>strip()</b> <br>
The strip() method returns a copy of the string by removing both the leading and the trailing characters (based on the string argument passed).

- <b>startswith()</b> <br>
The startswith() method returns True if a string starts with the specified prefix(string). If not, it returns False.

- <b>endswith()</b> <br>
The endswith() method returns True if a string ends with the specified suffix. If not, it returns False.

## Data type conversion
The process of converting the value of one data type (integer, string, float, etc.) to another data type is called type conversion.

## Input and Output
### Variable
Think of a variable as a name attached to a particular object. In Python, variables need not be declared or defined in advance, as is the case in many other programming languages. To create a variable, you just assign it a value and then start using it. Assignment is done with a single equals sign (=).

### Python Argument Specifiers
The "%" operator is used to format a set of variables enclosed in a "tuple" (a fixed size list), together with a format string, which contains normal text together with "argument specifiers", special symbols like "%s" and "%d". <br>
Here are some basic argument specifiers you should know:<br>
- %s - String (or any object with a string representation, like numbers)
- %d - Integers
- %f - Floating point numbers
- %.f - Floating point numbers with a fixed amount of digits to the right of the dot (.)
- %x - Integers in hex representation in lowercase
- %X - Integers in hex representation in uppercase
### input()
The input() function takes input from the user and returns it. The input() function reads a line from the input (usually from the user), converts the line into a string by removing the trailing newline, and returns it.

## Replace String Element
- <b>replace()</b> <br>
The replace() method replaces each matching occurrence of the old character/text in the string with the new character/text.

## String Checking
While working with different datatypes, we might come across a time, where we need to test the datatype for its nature. These functions give ways to test a variable against the data type it is.
- <b>isupper()</b> <br>
The string isupper() method returns whether or not all characters in a string are uppercased or not.
- <b>islower()</b> <br>
The islower() method returns True if all alphabets in a string are lowercase alphabets. If the string contains at least one uppercase alphabet, it returns False.
- <b>isalpha()</b> <br>
The isalpha() method returns True if all characters in the string are alphabets. If not, it returns False.
- <b>isalnum()</b> <br>
The isalnum() method returns True if all characters in the string are alphanumeric (either alphabets or numbers). If not, it returns False.
- <b>isdecimal()</b> <br>
The isdecimal() method returns True if all characters in a string are decimal characters. If not, it returns False.
- <b>isspace()</b> <br>
The isspace() method returns True if there are only whitespace characters in the string. If not, it return False. Characters that are used for spacing are called whitespace characters. For example: tabs, spaces, newline, etc.
- <b>istitle()</b> <br>
The istitle() returns True if the string is a titlecased string. If not, it returns False.

## String Formatting
- <b>zfill()</b> <br>
The zfill() method returns a copy of the string with '0' characters padded to the left.
- <b>rjust()</b> <br>
The string rjust() method returns a right-justified string of a given minimum width.
- <b>ljust()</b> <br>
The string ljust() method returns a left-justified string of a given minimum width.
- <b>center()</b> <br>
The center() method returns a new centered string after padding it with the specified character.

String Literals<br>
A string literal is where you specify the contents of a string in a program.<br>
If you need an actual single quote character inside a literal string delimited by single quotes, you can use the backslash character before the single quote, to tell Python not to terminate the string.

## Operations on List, Set and String
- <b>len()</b> <br>
The len() function returns the number of items in an object.
- <b>min()</b> <br>
The min() function return item with the lowest value.
- <b>max()</b> <br>
The max() function return item with the highest value.
- <b>merge</b> <br>
Merge used to combine two values together.
- <b>replication</b> <br>
Replication used to repeat value in object by amount of times equivalent to the integer value.
- <b>range()</b> <br>
The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.
- <b>in</b> <br>
The in function to check whether an element is present in the passed list or not. Returns true if the element is present in the list otherwise returns false.
- <b>not in</b> <br>
The not in function to check whether an element is not present in the passed list or not. Returns true if the element is not present in the list otherwise returns false.
- <b>Assign value in multiple variable</b> <br>
- <b>sort()</b> <br>
The sorted() function returns a sorted list ascending by default.

## Operators, Operands and Expression
<b>Operators</b> are special symbols in Python that carry out arithmetic or logical computation. The value that the operator operates on is called the <b>operand</b>. And a combination of operators and operands that interpreted to produce some other value is called <b>expression</b>.<br>
Python divides the operators in the following groups:
- Arithmetic operators <br> <img src="https://github.com/virarkh/Python-Part-2_Transform-Operation/blob/master/image/arithmetic.png"/>
- Comparison operators <br> <img src="https://github.com/virarkh/Python-Part-2_Transform-Operation/blob/master/image/comparison.png"/>
- Logical operators <br> <img src="https://github.com/virarkh/Python-Part-2_Transform-Operation/blob/master/image/logical.png"/>
- Assignment operator <br> <img src="https://github.com/virarkh/Python-Part-2_Transform-Operation/blob/master/image/assignment.png"/>

### Order of Operations in Arithmetic
The order of operations is a rule that tells the correct sequence of steps for evaluating a math expression. We can remember the order using <b>PEMDAS</b>. <br>
- P – Parentheses</br>
- E – Exponentiation</br>
- M – Multiplication (Multiplication and division have the same precedence)</br>
- D – Division</br>
- A – Addition (Addition and subtraction have the same precedence)</br>
- S – Subtraction</br>

## Syntax Error and Exception
### Syntax Errors <br>
 Syntax errors are mistakes in the use of python language and analogous to spelling or grammer mistakes. Usually, the errors are self-explanatory and docent needs any special attention to fix them. 
 ```
 prin("Hello World")
 
 ---------------------------------------------------------------------------
NameError                                 Traceback (most recent call last)
Input In [15], in <cell line: 1>()
----> 1 prin("Hello World")

NameError: name 'prin' is not defined
 ```
 ### Exception
Exception error is type of error occurs whenever syntactically correct Python code results in an error.
```
10 * (1 / 0)

---------------------------------------------------------------------------
ZeroDivisionError                         Traceback (most recent call last)
Input In [9], in <cell line: 1>()
----> 1 10 * (1 / 0)

ZeroDivisionError: division by zero
```
## Handling Exception
In Python, exceptions can be handled using a try statement.
There are some error that often occur:
- The Python "ZeroDivisionError: float division by zero" occurs when we try to divide a floating-point number by 0.
- TypeError is an exception in Python programming language that occurs when the data type of objects in an operation is inappropriate.
- The Python FileNotFoundError : No such file or directory error is often raised by the os library. This error tells you that you are trying to access a file or folder that does not exist. To fix this error, check that you are referring to the right file or folder in your program.
A try clause can have any number of except clauses to handle different exceptions, however, only one will be executed in case an exception occurs.
We can use a tuple of values to specify multiple exceptions in an except clause. Here is an example pseudo code.
### Many Exception
You can define as many exception blocks as you want, e.g. if you want to execute a special block of code for a special kind of error.
### Else
In some situations, you might want to run a certain block of code if the code block inside try ran without any errors. For these cases, you can use the optional else keyword with the try statement.
### Finally
The try statement in Python can have an optional finally clause. The finally block, if specified, will be executed regardless if the try block raises an error or not.

## Input ad Output Operations
<img src="https://github.com/virarkh/Python-Part-2_Transform-Operation/blob/master/image/File%20Handling.png"/>
