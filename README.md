# Null Value Handling in JavaScript Function
This repository demonstrates a common error in JavaScript where null values are not handled properly, leading to unexpected behavior or errors.

The `foo` function is designed to perform operations on inputs `a` and `b`. However, it did not initially handle the case where one or both of these inputs might be `null`. This could result in errors or unexpected outputs if `null` is passed as an argument.

The solution demonstrates how to explicitly handle `null` values by checking for them before attempting any operations.

## How to reproduce
1. Clone the repository.
2. Open `bug.js` and run the code. Observe the unexpected behavior.
3. Open `bugSolution.js` to see the corrected version of the function.
4. Run the corrected version and observe the expected behavior.

## Bug and Solution
The bug lies in the initial version's lack of explicit `null` value checks. The solution addresses this by adding an `if` condition to return `null` if either `a` or `b` is `null`, ensuring the function handles these cases gracefully.

This example highlights the importance of comprehensive input validation in JavaScript functions to prevent unexpected errors and improve code robustness.