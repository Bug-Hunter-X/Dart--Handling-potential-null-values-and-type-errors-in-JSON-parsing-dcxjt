# Dart JSON Parsing Error Handling

This repository demonstrates a common error in Dart when parsing JSON responses from APIs and provides a solution for robust error handling.

The `bug.dart` file contains code that incorrectly handles JSON parsing without proper null and type checks, leading to potential crashes or unexpected behavior.  The `bugSolution.dart` file shows improved error handling.

## How to Run

1. Clone the repository.
2. Run `dart bug.dart` to see the original error.
3. Run `dart bugSolution.dart` to see the corrected code in action.

## Problem and Solution
The original code directly accesses the `value` key without any null or type checks.  If the API's response changes, or if a network error causes an empty response, this can throw exceptions.  The solution addresses these potential issues by adding appropriate checks and handling.