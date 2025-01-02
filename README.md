# Dart Reduce Method Error: Empty List

This repository demonstrates a common error encountered when using the `reduce` method in Dart with an empty list.  The `reduce` method requires at least one element in the list to function correctly. Attempting to use it with an empty list results in an `UnsupportedError: Empty list` exception.

The provided code examples illustrate the problem and its solution. The `bug.dart` file showcases the error, while `bugSolution.dart` provides a corrected version.

## How to Reproduce the Error

1. Clone this repository.
2. Open `bug.dart`.
3. Run the file using a Dart compiler or IDE.
4. Observe the `UnsupportedError: Empty list` exception.

## Solution

The solution involves adding a simple check to ensure that the list is not empty before applying the `reduce` method. This is demonstrated in the `bugSolution.dart` file.

## Lessons Learned

Always check for edge cases when using list manipulation methods in Dart, especially when the list might potentially be empty.