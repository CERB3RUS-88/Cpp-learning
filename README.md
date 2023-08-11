---
description: 1st Hello World Program
---

# Minimal c++ program

{% code fullWidth="true" %}
```cpp
#include <iostream>  //header file

int main()  //program starts here
//Curly braces, { }, express grouping in C++. Here, they indicate the start and end of the function
//body
{
//using namespace std;  make names from std visible without std::
        std::cout << "Hello World!\n";//cout = character, output, << also output, semicolon is used at the end of statements
        std::cout << "Yoww!";
    
}



```
{% endcode %}

Every C++ program must have exactly one global function named main(). The program starts by executing that function. The int value returned by main(), if any, is the program’s return value to ‘‘the system.’’ If no value is returned, the system will receive a value indicating successful completion. A nonzero value from main() indicates failure



The line #include instructs the compiler to include the declarations of the standard stream I/O facilities as found in iostream. Without these declarations, the expression std::cout << "Hello, World!\n" would make no sense.



