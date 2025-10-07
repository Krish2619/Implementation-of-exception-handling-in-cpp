Aim:
To demonstrate exception handling in C++ using `try`, `catch`, and `throw` for runtime error management.

Apparatus:
- C++ Compiler
- Code Editor (e.g., VS Code)
  
Program Explanation:

Program 1: Division Exception
Performs division of two numbers. If the divisor is zero, an exception is thrown to handle the error.

Program 2: Age Validation
Checks if a person is 18 or older. If underage, an exception is thrown to deny access.

Algorithm:

Program 1: Division
1. Input two float numbers.
2. If the second number is 0, throw an exception.
3. Otherwise, perform division and print result.
4. Catch block handles division by zero.

Program 2: Age Check
1. Input an integer age.
2. If age < 18, throw exception.
3. Else, approve.
4. Catch block prints underage error.

Key Concepts:
- Exception handling (`try`, `throw`, `catch`)
- Runtime error prevention
- Input validation
- Clean program flow using structured error control

Conclusion:
The programs effectively demonstrate the use of exception handling in C++ to manage and handle runtime errors like division by zero and invalid age input, ensuring more stable and user-friendly applications.
