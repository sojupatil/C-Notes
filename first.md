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

# Compiler 
A compiler is a program that translates high-level programming code into a machine-readable format (binary or assembly code) that a computer's processor can execute. It serves as a bridge between human-readable code and machine code.

# Pseudocode 
Pseudocode is a way of describing the logic and steps of an algorithm or program in plain language that is easy to understand. It is not written in any specific programming language, so it cannot be directly executed by a computer. Instead, it serves as an intermediary step between brainstorming the logic and writing the actual code in a programming language.
```c
Start
Input A, B, C
If A > B and A > C
    Print "A is the largest"
Else If B > A and B > C
    Print "B is the largest"
Else
    Print "C is the largest"
End
```
# Algorithm 
An algorithm is a step-by-step, well-defined procedure or set of rules designed to solve a problem or perform a specific task. It acts as a blueprint for how a problem should be approached, solved, or executed.

```c
Algorithm:

1. Start
2. Input two numbers, A and B
3. Add A and B, store the result in C
4. Print 
5. Stop
```
# Assembly code
Assembly code, also known as assembly language, is a low-level programming language that is closely related to machine code but uses symbolic names instead of binary instructions. It serves as an intermediary between high-level programming languages (like C or Python) and the raw machine code that the CPU executes.

```c
section .data
    num1 db 5       ; Declare number 1
    num2 db 3       ; Declare number 2
    result db 0     ; Declare space for the result

section .text
    global _start

_start:
    mov al, [num1]  ; Load num1 into register AL
    add al, [num2]  ; Add num2 to AL
    mov [result], al ; Store the result
    ; Exit the program (Linux syscall)
    mov eax, 60     ; syscall: exit
    xor edi, edi    ; status: 0
    syscall
```
# Flowchart 
A flowchart is a graphical representation of an algorithm, process, or system, using symbols to represent the steps and their flow in a logical sequence.

## 1.Flowchart Symbols:

Oval (Terminal): Represents the start or end of a process.

Rectangle (Process): Represents a task, action, or operation.

Diamond (Decision): Represents a decision-making step (e.g., Yes/No or True/False).

Arrow: Indicates the flow of the process.

Parallelogram (Input/Output): Represents input to or output from a process.


### 2. Flow Direction: 
The arrows indicate the sequence in which steps are performed.

Example: 
![Flowchart](https://images.javatpoint.com/cpages/images/flowchart-in-c21.png)


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

