# Unit 1 : Problem Solving, Algorithms, and Flowcharts

## About C
C is a high-level, general-purpose programming language that was developed by Dennis Ritchie in the early 1970s at Bell Labs. It is widely known for its efficiency and control over system resources, making it suitable for system programming, embedded systems, and applications requiring high performance.

C provides features like low-level memory manipulation, a rich set of operators, and straightforward syntax, which has influenced many modern programming languages like C++, Java, and Python. It allows direct access to hardware, making it ideal for writing operating systems, compilers, and other system software. C also supports structured programming, using functions and blocks of code to improve readability and maintainability.

## Algorithm 
An algorithm is a step-by-step procedure or a set of rules to solve a specific problem or perform a task. It serves as a blueprint for implementing solutions.

### Example : Algorithm to Find the Largest of Three Numbers

Algorithm:

1. Start.


2. Input three numbers: a, b, c.


3. Compare:

If a > b and a > c, then a is the largest.

Else if b > c, then b is the largest.

Otherwise, c is the largest.



4. Print the largest number.


5. Stop.

```c
#include <stdio.h>
#include <conio.h>

void main() {
    int a, b, c, largest;
    
    // Input three numbers
    printf("Enter three numbers: ");
    scanf("%d %d %d", &a, &b, &c);

    // Compare to find the largest
    if (a > b && a > c) {
        largest = a;
    } else if (b > c) {
        largest = b;
    } else {
        largest = c;
    }

    // Print the largest number
    printf("The largest number is: %d\n", largest);

    getch();
}

```


## Variables 

A variable is a user-defined or a user-readable custom name assigned to a memory location. Variables hold a value that can be modified and reused many times during the program execution.

Name: The label you give the variable (e.g., age, score).

Type: Specifies what kind of data the variable will hold (e.g., int for integers, float for decimal numbers).

Value: The actual data stored in the variable (e.g., 5, 3.14).


Example:

```c
int age = 20;
```

 'int' is the type, 'age' is the name, and 20 is the value

In this example, age is a variable that stores an integer (20).



```c
#include <stdio h>
#include <conio.h>
void main(){
printf("Hello World");
getch();
 }
```
