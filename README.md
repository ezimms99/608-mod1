# 608-mod1
My notes and practice from module 1

Chapter 1: 
Moore’s Law: Hardware costs have gradually fallen whereas computer capacities have doubled. 
Amount of memory that computers have for programs
Amount of secondary storage 
Processor speeds
Bandwidth: Information carrying capacity 
Computer Units (Most have multicore processors): 
Input: This receiving section obtains information from input devices and places it at the disposal of other units for processing. 
Output: This shipping section takes information the computer has processed and places it on various output devices to make it available for use outside the computer. 
Memory: Retains information that has been entered through the input unit. 
ALU: This manufacturing section performs calculations. 
CPU: This administrative section coordinates and supervises the operation of the other sections.
Secondary Storage: This is the long-term high capacity warehousing section. 
Bit (binary digit): Is the smallest data item in a computer valuing 0 or 1. 
Characters: Digits, letters, and symbols. 
Fields: Composed of characters or bytes, group of characters or bytes that convey meaning. 
Records: Several related fields compose a record. 
Files: A group of related records. 
Databases: Collection of data organized for easy access and manipulation. 
Big data: Massive amounts of data. 
Relational database: Data stored in tables. 
Objects: reusable software components. 
Method: Houses the program statements that perform its tasks. 
Class: houses the set of methods that perform the class’s tasks.
Instantiation: Process of building an object of a class. 
Method call: Tells a method of the object to perform its task. 
Attributes: Are specified by the class’s instance variables
Inheritance: The new class (subclass) starts with the characteristics of an existing class (superclass) possibly customizing them. 
OOAD: Analyzing and designing your system from an object-oriented point of view.  
Operating Systems: software systems that make using computers more convenient for users, application developers and system administrators. 
Kernel: The software that contains the core components of the operating system. 

Windows = Proprietary operating system, controlled by microsoft exclusively 
Linux = Open source software 
Apple = Open source
Android = open source


Python: 
Object oriented scripting language. 
Anaconda python distribution: 
Easy install on Windows, Mac, and Linux. 
Supports latest versions of python.
The Zen of Python summarizes python creator Guido van Rossum’s design principles for python language. 
Python Standard Library: Provides rich capabilities for text/binary data processing, mathematics, functional-style programming, file/directory access, data persistence, data compression/archiving, and more. 
Integrated Development Environments: provide tools that support the entire software-development process. 

Jupyter Notebook: An interactive browser-based environment in which you can write and execute code and intermix the code with text, images, and video. 

CHAPTER 2: 
Python rules
Statement: x=7 
Identifier: x. Cannot begin with a digit and python is case sensitive. 
Type: Each kind of data has a type 
For example: type(10.5) is a float 
Floating point number: Decimals 
Floor division: Uses two // and yields the highest integer not greater than the result. 
Remainder (modulo): Used as % and yields the remainder after division. 
Exponentiation: ** = x^y
Dividing by zero is not allowed
Traceback: Reports the error in python 
Python follows PEMDAS

Print function: Displays its argument. 
String: A string of characters 
Escape Character: used as a \
\n represents a newline character 
\t inserts a tab
\\ insert a backslash character in a string 
\” Insert a double quote character in a string
\’ Insert a single quote character in a string 
Using quotes in quotes: 
- print(‘Display “hi” in quotes’)
- print(‘Display\’hi\’ in quotes’)
Can use triple quotes instead
- print(“””Display “hi” and ‘bye’ in quotes”””)
Input: Allows users to input an answer
- Name = input(“What is your name?”)
- What’s your name? ‘Paul’ 
- Name
- “‘Paul’”
- print(name)
- ‘Paul’
Getting an integer from a user: 
- Value = input(‘Enter an integer: ‘) 
- Enter an integer: 7
- Value = int(value) 
- Value
- 7
Boolean Expressions: Are either true or false. 
Docstring: Each script should start with a docstring that explains the script's purpose. Use triple quotes. 
= means is assigned to 
== means equal to

Min: smallest value in a collection 
Max: Largest value in a collection 
Range: Range of values from min to max
Count: Number of values in a collection
Sum: Total of all values in collection 
Measure of dispersion: Range, variance, standard deviation 
