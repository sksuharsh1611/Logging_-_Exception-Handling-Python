# Logging_And_Exception-Handling-Python

# Logging in Python

The logging module in Python provides a powerful and flexible way to record events and messages from a running application. It allows developers to fine-tune the amount of detail recorded by the logging system by defining different levels of severity or importance.

The levels of logging in Python, in increasing order of severity, are:

> NOTSET: The lowest possible level, used to indicate that no logging is done.

> DEBUG: Detailed information, typically of interest only when diagnosing problems.

> INFO: General information about the application's operation, such as startup messages and status updates.

> WARNING: An indication that something unexpected happened or indicative of some problem in the near future (e.g., 'disk space low').

> ERROR: An error occurred that should be investigated, such as an unhandled exception.

> CRITICAL: A very serious error occurred, indicating that the program itself may be unable to continue running.

By default, the logging module sets the level to WARNING, which means that only events with a severity level of WARNING or higher will be logged. However, developers can easily adjust the level to suit their needs by modifying the logger's level attribute or using the basicConfig() function.

Selecting the appropriate level of logging for each message in your Python code can make it easier to troubleshoot issues and optimize performance. By recording only relevant information at the appropriate severity level, developers can quickly identify the root cause of problems and reduce noise in the logs.

Proper logging is an essential component of software development and can help improve the maintainability and reliability of your code. By understanding the different levels of logging available in Python and how to use them effectively, developers can ensure that their code is well-documented and easy to debug.

# Exception Handling in Python

Exception handling is a way to handle runtime errors that occur during program execution in a graceful and controlled manner. In Python, exceptions are objects that represent errors, such as division by zero, type errors, or file not found errors. When an exception occurs, the Python interpreter looks for a corresponding exception handler to handle the error.

Exception handling in Python involves the use of three keywords: try, except, and finally. Here's how they work:

> try: The try block contains the code that might raise an exception. If an exception is raised in the try block, the code in the except block is executed. If no exception is raised, the except block is skipped.

> except: The except block contains the code that handles the exception. It specifies the type of exception that it can handle. If the exception matches the type specified in the except block, the code in the except block is executed. If the exception doesn't match, it is propagated to the next level of exception handling.

> finally: The finally block contains the code that is always executed, whether or not an exception is raised. It is often used for cleanup tasks, such as closing files or releasing resources.

In addition to handling built-in exceptions, developers can also create their own custom exceptions by defining a new class that inherits from the built-in Exception class.

- Proper use of exception handling can help make Python code more robust and reliable. By anticipating and handling potential errors in a controlled way, developers can prevent unexpected behavior and make their code more predictable.
