# CSS calc() function syntax error

This repository demonstrates a subtle syntax error in CSS's `calc()` function.  The error involves an unexpected space between a numeric value and its unit, which can lead to unexpected rendering behavior.

## Bug
The file `bug.css` contains the erroneous code.  The space between `10` and `px` in `calc(100% - 10 px)` causes the calculation to fail.

## Solution
The corrected code is in `bugSolution.css`. The space has been removed, resulting in a valid `calc()` expression: `calc(100% - 10px)`.

## Reproduction
1. Create two files: `bug.css` and `bugSolution.css`.
2. Paste the respective CSS code into each file.
3. Include these CSS files in an HTML file and observe the different rendering behaviors.