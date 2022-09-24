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














