# RecursionError in Factorial Function

This repository demonstrates a common error in recursive functions: the lack of a proper base case for negative input, leading to infinite recursion and a `RecursionError`. The `bug.py` file contains the buggy code, while `bugSolution.py` provides a corrected version.

The issue is that the recursive call `factorial(n-1)` continues indefinitely when `n` is negative, as it never reaches a stopping condition.  This results in Python exceeding the maximum recursion depth. The solution introduces a check to handle negative input gracefully.