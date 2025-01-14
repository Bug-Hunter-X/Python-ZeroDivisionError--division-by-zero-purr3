# Python ZeroDivisionError Bug Report

This repository demonstrates a common error in Python: the `ZeroDivisionError`.  The `bug.py` file contains a function that attempts to divide by zero, resulting in an unhandled exception. The `bugSolution.py` file shows how to handle this error gracefully.

## Bug

The `function` in `bug.py` doesn't handle the case where the second argument is zero, leading to a runtime error. 

## Solution

`bugSolution.py` demonstrates a solution using a `try-except` block to catch the `ZeroDivisionError` and provide a more informative message or alternative behavior.