# What is C?
C is a general-purpose programming language created by Dennis Ritchie at the Bell Laboratories in 1972.

It is a very popular language, despite being old. The main reason for its popularity is because it is a fundamental language in the field of computer science.

C is strongly associated with UNIX, as it was developed to write the UNIX operating system.

# C Syntax
*The syntax of the C programming language is the set of rules governing writing of software in C.Syntax is Structure of program*

```c
#include <stdio.h>
#include <conio.h>

void main() {
  printf("Hello World!");
  getch();
}

```
Line 1: ```#include <stdio.h>``` is a header file library that lets us work with input and output functions, such as printf() (used in line 4). Header files add functionality to C programs.

Line 2: ```#include <conio.h>``` header file is a compiler-specific file that provides functions for console input and output, screen handling, and text-based interface development.

Line 3: ```main()``` This is called a function. Any code inside its curly brackets {} will be executed.

Line 4: ```printf()``` is a function used to output/print text to the screen. In our example, it will output "Hello World!".

Line 5: ```getch();``` is a function that reads a single character from the keyboard input. It is part of the **conio.h** library, which is used for console input and output operations. The getch(); function:
Waits for the user to press a key on the keyboard.
Does not echo the pressed key to the screen, meaning the input is not displayed.

# Statements 
A computer program is a list of "instructions" to be "executed" by a computer.

In a programming language, these programming instructions are called statements.

The following statement "instructs" the compiler to print the text "Hello World" to the screen.
```c
printf("Hello World!");
```
It is important to end the statement with a semicolon ; , **;** is also called as Statement Terminator.

# printf Function ~ Output (Print Text)
printf is the function used to print text or output values.
If we want to print text it must he wrapped inside double quotation marks 
`""`.
We can you as many print function as we want.
```c
printf("Hello World 🌎");
```
# New Lines 
\n is an escape sequence that represents a newline character. When used in a string, it causes the output to move to the next line. 

Example Code:

```c
#include <stdio.h>
#include <conio.h>

void main() {
    printf("Hello, World!\n");
    printf("This is on a new line.");
    getch();
}
```
Output:

```c
Hello, World!
This is on a new line.
```

# C Comments 
Comments can be used to explain code, and to make it more readable. It can also be used to prevent execution when testing alternative code.

Comments can be singled-lined or multi-lined.
Single-line comments start with two forward slashes (//).

Any text between // and the end of the line is ignored by the compiler (will not be executed).

This example uses a single-line comment before a line of code:

```c
// This is a comment
printf("Hello World!");
```
# C Multi-line Comments

Multi-line comments start with /* and ends with */.
Any text between /* and */ will be ignored by the compiler:

Example
```c
/* The code below will print the words Hello World!
to the screen, and it is amazing */
printf("Hello World!");
```

