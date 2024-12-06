# CSS Bug Report

This repository demonstrates two uncommon CSS bugs:

1. **`:has()` pseudo-class selector incompatibility:** The `:has()` pseudo-class is not supported in older browsers. This can lead to unexpected styling behavior or rendering issues in these browsers.
2. **Incorrect class selector:** A common issue in CSS is an incorrectly specified class selector. This could result in an unexpected lack of styling on elements. 

The `bug.css` file contains the buggy code, while `bugSolution.css` provides solutions and workarounds.

## Solutions

The solutions are provided in `bugSolution.css`.  The primary issue is addressed by using feature detection to conditionally apply styles, ensuring that the code functions consistently across different browsers.  The class selector issue is resolved by correcting the selector.