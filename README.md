# Exception-Handling-in-C-

To study and implement Exception Handling

# Aim 

To study and implement exception handling in C++ using try, catch, and throw statements to detect and handle runtime errors effectively, ensuring robust and error-free program execution.

# Theory 

Exception handling in C++ is a mechanism to handle runtime errors or abnormal situations without terminating the program abruptly. It separates error-handling code from regular logic, making programs more reliable and easier to maintain.

Key keywords in C++ exception handling:

1 .try block – Defines a section of code where exceptions might occur.

2. throw statement – Used to signal (raise) an exception when an error occurs.

3. catch block – Handles the exception thrown by the throw statement.

Flow:

  * Code that might cause an error is placed inside a try block.

  * When an error occurs, it is thrown using throw.

  * The catch block receives the thrown exception and handles it accordingly.

Advantages of exception handling:

  * Provides a structured way to manage runtime errors.

  * Improves program stability and robustness.

  * Makes error-handling code separate from normal logic, improving readability.

Common exceptions include divide-by-zero errors, file handling errors, invalid inputs, and memory allocation failures.

# Procedure

1/ Identify possible runtime errors (divide by zero, invalid age).

2/ Enclose risky code in try block.

3/ Use throw to raise an error.

4/ Catch the error using catch block.

5/ Display user-friendly message instead of abnormal termination.

# Conclusion 

We implemented exception handling in C++ successfully. It allows programs to handle errors gracefully and improves reliability and robustness.
