# Fundamentals of programming ✏️

### Basic fundamental 📣

The computer is based on 10 basic fundamentals
1. **input/output**:

   input/output are the most basic fundamentals of a program 
  ```mermaid
     flowchart LR
     A[input] --> B[user or external source]
     C[output] --> D[viewing results] 
  ```
   the input and output are the working fundamentals of a program which is subdivided into other aspects

2. **variables**:

   variables: acts a major role in the program.  Variables are given names that describe the kind of data they hold. Variable names typically consist of letters, numbers, and underscores, but they must follow certain rules (e.g., they cannot start with a number).

3. **data types**:

   Variables can hold different types of data, such as numbers, strings (sequences of characters), boolean values (true/false), and more complex data structures like arrays and objects.

4. **Declaration**:

   Before using a variable in a program, it must be declared, which tells the computer's memory system to allocate space for it. The declaration typically includes the variable's name and data type.

5. **Initialization**:

   Variables can be initialized with an initial value at the time of declaration, or they can be assigned a value later in the program.

6. **Scope**:

   Variables have a scope, which defines where in the program they are accessible. Variables can have local scope (accessible only within a specific block of code) or global scope (accessible throughout the entire program).
   ```
   #include <iostream>
   using namespace std;
   
   int main() {
       // Variable declaration and initialization
       int age = 25;
       string name = "John";
       bool is_student = true;
   
       // Printing variable values
       cout << "Name: " << name << endl;
       cout << "Age: " << age << endl;
       cout << "Is student? " << (is_student ? "Yes" : "No") << endl;
   
       // Variable reassignment
       age = 30;
       cout << "Updated age: " << age << endl;
   
       return 0;
   }
   ```
    * age, name, and is_student are variables.
    * age is an integer variable initialized with the value 25.
    * name is a string variable initialized with the value "John".
    * is_student is a boolean variable initialized with the value true.
    * The cout statement is used to print the values of these variables.
    * age is reassigned a new value of 30.
    * The program outputs the values of the variables and the updated value of age.
    * Remember that in C++, you need to include the appropriate header files (<iostream> in this case) and use the using namespace std; directive to avoid typing std:: before standard library elements like cout and endl


7. **data types**:

   Here are a few examples of data types
   * **Integer**: Used to store whole numbers without any decimal point. Examples include 1, -5, 1000.
   * **Floating-point**: Used to store numbers with decimal points. Examples include 3.14, -0.5, 10.0
   * **Character**: Used to store individual characters. Examples include 'a', 'B', '$'
   * **String**: Used to store sequences of characters. Examples include "hello", "world", "123".
   * **Boolean**: Used to represent true or false values. Examples include true, false.
   * **Array**: Used to store a collection of elements of the same data type. Examples include [1, 2, 3], ['apple', 'banana', 'orange'].

8. **control structures**

   Control structures allow you to control the flow of a program. Common control structures include conditional statements (if-else statements), loops (for loops, while loops), and switch statements

9. **data structures**

    Data structures are ways of organizing and storing data to efficiently perform operations on them. Common data structures include arrays, linked lists, stacks, queues, trees, and hash tables.

10. **Algorithms**

    Algorithms are step-by-step procedures for solving problems. Understanding basic algorithms and their analysis (e.g., searching, sorting, recursion) is essential for writing efficient code

11. **debugging/testing**

    debugging and testing is used to see if the program is running properly and is bug-free

### class tasks no: 01
* make an algorithm flowchart
* solve a problem using algorithm seqeuance
#### given problems 
1. calculate the area of room
2. make an auto-system for grading
### algorithm model 
```mermaid
flowchart TD
A([start]) --> B[/instruction/input/]
A--> C[/output/]
B & C --> D[processing]
D -->|arrows show the flow| E{decision making b/w two possibilties}
E --> F([end]) 
 
```
### make an auto-grading system 
```mermaid
flowchart TD
A([start]) --> B[/pass/fail/]
B --> C{ x pass > y fail}
C -->|40| D[/fail/]
C -->|50| E[/pass/]
D --> F([end])
E --> F([end])
```



