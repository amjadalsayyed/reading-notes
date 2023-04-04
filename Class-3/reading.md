# Class-3 Reading Notes

## Reading and Writing Files in Python

In Python, you can use built-in functions to read and write files. Here are the main functions you can use:

> - open(): This function opens a file in Python. You need to specify the name of the file and the mode in which you want to open it (read, write, append, etc.).
> - read(): This function reads the contents of a file. You can specify the number of bytes you want to read, or leave it blank to read the entire file.
> - write(): This function writes data to a file. You need to specify the data you want to write to the file.
> - close(): This function closes the file you have opened. It is important to close the file when you are done with it to free up system resources.

In addition to these basic functions, Python provides several other functions and methods for working with files, such as readline() and writelines().

These functions and methods give you more control over how you read and write data to files.

Overall, reading and writing files in Python is a simple and efficient process thanks to the built-in functions provided by the language.

## Exceptions in Python

### Summing Up

After seeing the difference between syntax errors and exceptions, i learned about various ways to raise, catch, and handle exceptions in Python. In this article, i saw the following options:

> - raise allows you to throw an exception at any time.
> - assert enables you to verify if a certain condition is met and throw an exception if it isn’t.
> - In the try clause, all statements are executed until an exception is encountered.
> - except is used to catch and handle the exception(s) that are encountered in the try clause.
> - else lets you code sections that should run only when no exceptions are encountered in the try clause.
> - finally enables you to execute sections of code that should always run, with or without any previously encountered exceptions.
