# Printf

## Synopsis
A simple printf function built by Mohammed Tegegne for Alx software Engineering School.

## Description
Rebuild of the standard printf function in C. Our project required a function capable of printing with the %d, %c, %s, and %% specifiers to standard output. printf returns the number of characters printed (excluding the null byte at the end of strings). We were not asked to handle flag characters, field width, precision, or length.
The available convertion specifiers are:

+ %c:  Single character.
+ %s:  String of characters.
+ %d:  Decimal Integers.
+ %i:  Integers.
+ %b:  binary of an unsigned decimal.
+ %u:  unsigned integers
+ %x:  hexadecial of an unsigned decimal in lowercase letters
+ %X: hexadecial of an unsigned decimal in uppercase letters
+ %r:  a reversed string
+ %R:  Rot13 of a string

## Usage
+ All the files are to be compiled on Ubuntu 14.04 LTS
+ Compile your code with `gcc -Wall -Werror -Wextra -pedantic *.c`
+ Include the "main.h" header file on the functions using the _printf()

## Example

```

Character: printf("%c", A); Output:: A

String: printf("%s", This is a string.); Output: This is a string.

Integer: printf("%i", 5); Output: 5

Expletive: printf("%F", anything); Output: Something

```
