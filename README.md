# Unhandled JSON Key Access in Dart

This repository demonstrates a common error in Dart when handling JSON responses: attempting to access a key that may not exist.  The `bug.dart` file shows the problematic code, while `bugSolution.dart` provides a corrected version.

The issue arises from directly accessing a key in a JSON map without prior verification. If the key is absent, a runtime error occurs, potentially crashing the application.

The solution involves checking for the key's presence before accessing its value, ensuring robust error handling.