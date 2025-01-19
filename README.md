# Dart Reduce Method Error on Empty List

This repository demonstrates an uncommon error that can occur when using the `reduce` method in Dart with an empty list.  The `reduce` method requires at least one element in the list to function correctly; otherwise, it throws a `Bad state: No element` exception.

The `bug.dart` file shows the problematic code, which attempts to reduce an empty list. The `bugSolution.dart` file provides a solution that handles empty lists gracefully.