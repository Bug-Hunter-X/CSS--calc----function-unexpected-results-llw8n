# CSS `calc()` Function Unexpected Results

This repository demonstrates a common issue encountered when using the CSS `calc()` function: unexpected results and layout inconsistencies.  The `bug.css` file showcases the problematic code, and `bugSolution.css` provides the corrected version.

The problem stems from incorrect usage of the `calc()` function, which can lead to calculations that are different from what is expected. This often involves missing spaces around operators or inconsistent units.

**Key Issues Addressed:**

*   Missing spaces around operators within `calc()`.
*   Unit inconsistencies in calculations (e.g., mixing percentages and pixels without proper conversion).

This example highlights the importance of carefully reviewing `calc()` usage and maintaining consistent units in your CSS for predictable and accurate layout behavior. 