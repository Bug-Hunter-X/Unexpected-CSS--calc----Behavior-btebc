# Unexpected CSS `calc()` Behavior
This repository demonstrates some uncommon errors that can arise when using the `calc()` function in CSS.  Specifically, it covers issues related to missing units and incorrect operator precedence.

The `bug.css` file contains examples of problematic `calc()` usage, and `bugSolution.css` shows the corrected versions.

## Common Mistakes

* **Missing Units:** Always include units (e.g., `px`, `%`, `em`) for all values in `calc()`.  Forgetting units will likely cause the calculation to fail.
* **Operator Precedence:** Use parentheses `()` to explicitly control the order of operations in complex `calc()` expressions.  Don't rely on implicit precedence rules that might differ across browsers.

This example highlights the importance of careful attention to detail when working with CSS's `calc()` function to avoid unexpected layout problems.