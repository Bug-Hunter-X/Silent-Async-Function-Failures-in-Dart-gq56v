# Silent Async Function Failures in Dart

This repository demonstrates a common issue in Dart asynchronous programming: unhandled exceptions within `async` functions.  The `bug.dart` file showcases code that catches an exception but fails to rethrow it, leading to a silent failure.

The solution, provided in `bugSolution.dart`, correctly rethrows the exception to allow for proper error handling at a higher level in the call stack.