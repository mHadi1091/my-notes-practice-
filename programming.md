# fundamentals of programming
## basic fundamental

### the computer is based on 10 basic fundamentals
## input/output
#### input/output are the most basic fundamentals of a program 
```mermaid
flowchart LR
 [input]--> [user or external source]
 [output]--> [shows results]
```
#### the input and output wre the wroking fundamental of a program which is subdivided into other aspects
# variables
### variables: acts a major role in program.  Variables are given names that describe the kind of data they hold. Variable names typically consist of letters, numbers, and underscores, but they must follow certain rules (e.g., they cannot start with a number).
### data types:  Variables can hold different types of data, such as numbers, strings (sequences of characters), boolean values (true/false), and more complex data structures like arrays and objects.
### Declaration: Before using a variable in a program, it must be declared, which tells the computer's memory system to allocate space for it. The declaration typically includes the variable's name and data type.
### Initialization: Variables can be initialized with an initial value at the time of declaration, or they can be assigned a value later in the program.
### Scope: Variables have a scope, which defines where in the program they are accessible. Variables can have local scope (accessible only within a specific block of code) or global scope (accessible throughout the entire program).
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
