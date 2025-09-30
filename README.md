# Exp16_Exception-Handling-in-C-Plus-Plus
### Aim  
To study and implement exception handling in C++.

### Software Required  
Visual Studio (or any C++ IDE).

### Theory  
Errors—also called exceptions—are common in programming and can be categorized into three types:  
- **Syntax Errors**: Violations of programming language rules, detected at compile time.
- **Logical Errors**: The program runs, but produces incorrect results due to errors in logic.
- **Runtime Errors**: Unpredictable errors that occur while the program is running, such as division by zero or invalid memory access.

C++ provides an exception handling mechanism to detect and handle runtime errors gracefully, rather than terminating the program abruptly. This is achieved using **try**, **catch**, and **throw** keywords:  
- The **try** block contains code that might generate an exception.  
- If an error occurs, the **throw** statement signals an exception.  
- The program then transfers control to the appropriate **catch** block, allowing for custom error handling or recovery measures.[2][3][4][5]

Some common scenarios where exception handling is essential include:
- Division by zero errors.
- Accessing invalid memory locations.
- File input/output failures.

### Exception Handling in C++
- The **try-catch block** is used to separate code that might throw an exception (in the try block) from code that handles the error (in the catch block).
- Multiple catch blocks can be written to handle different types of exceptions.[5]
- The **throw** keyword is used to raise exceptions by sending an error value or object from the try block to the catch block.

### Implementation  
The concept of exception handling in C++ was demonstrated through the following practical examples:  
- Handling division by zero errors using try-catch blocks.
- Implementing an age checker that throws exceptions for invalid age inputs.

### Conclusion  
The above code examples demonstrate how exceptions can be used in C++ programs to effectively manage runtime errors, ensuring the program handles abnormal conditions gracefully.[3][6][5]

[6](https://www.tutorialspoint.com/cplusplus/cpp_exceptions_handling.htm)
[7](https://www.wscubetech.com/resources/cpp/exception-handling)
[8](https://www.pvpsiddhartha.ac.in/dep_it/lecture%20notes/OOPS/unit5.pdf)
