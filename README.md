# Python

**What is Python?**
Python is simple & easy
Free & Open Source
High Level Language
Developed by Guido van Rossum
Portable

**First Program**
print("Hello World")

**Python Character Set**
Letters – A to Z, a to z
Digits – 0 to 9
Special Symbols - + - * / etc.
Whitespaces – Blank Space, tab, carriage return, newline, formfeed
Other characters – Python can process all ASCII and Unicode characters as part of data or literals

**Variables**
name = "Shradha"
age = 23
price = 25.99

**Rules for Identifiers**
1. Identifiers can be combination of uppercase and lowercase letters, digits or an underscore(_).
So myVariable, variable_1, variable_for_print all are valid python identifiers.
2. An Identifier can not start with digit. So while variable1 is valid, 1variable is not valid.
3. We can't use special symbols like !,#,@,%,$ etc in our Identifier.
4. Identifier can be of any length.

**Data Types**
Integers
String
Float
Boolean
None

**Data Types**
print(type(age))                      <class 'int'>
print(type(pi))                       <class 'float'>
print(type(complex_num))              <class 'complex'>
print(type (A))                       <class 'bool'>se
print(type(name))                     <class 'str'>

**Keywords**
Keywords are reserved words in python.
*False should be uppercase
and     else     in     return   
as      except   is     True   
assert  finally  lambda break
false   nonlocal with   class
for     None     while  continue 
from    not      yield  def
global  or       del    if
pass    elif     Import raise

**Comments in Python**
# Single Line Comment 
""" Multi Line Comment """

**Types of Operators**
An operator is a symbol that performs a certain operation between operands.
Arithmetic Operators (+,-,*,/,%,**)
Relational / Comparison Operators (==,!=,>,<,>=,<=)
Assignment Operators (=,+=,-=,*=,/=,%=,**=)
Logical Operators ( not , and , or )

**Type Conversion**
a, b = 1, 2.0
sum = a + b

#error
a, b = 1, "2"
sum = a + b

**Type Casting**
a, b = 1, "2"
c = int(b)
sum = a + c

**Type Casting**
**Function**           **Description**
intly (base])          It converts y to an integer, and Base specifies the number base. For example, if you want to convert the string in decimal numbers then 
                       you'll use 10 as base.
float(y)               It converts y to a floating-point number.
complex(real [imag])   It creates a complex number.
str(y)                 It converts y to a string.
tuple(y)               It converts y to a tuple.
list(y)                It converts y to a list.
set(y)                 It converts y to a set.
dict(y)                It creates a dictionary and yshould be a sequence of (key, value) tuples.
ord(y)                 It converts a character into an integer.
hex(y)                 It converts an integer to a hexadecimal string.
oct(y)                 It converts an integer to an octal string

**Input in Python**
input( ) statement is used to accept values (using keyboard) from user
input( ) #result for input( ) is always a str
float ( input( ) ) #float

