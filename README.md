# Unexpected Behavior with CSS calc() Function

This repository demonstrates some uncommon errors that can occur when using the CSS `calc()` function.  The `bug.css` file contains examples of code that exhibit these problems. The `bugSolution.css` file offers solutions and workarounds.

**Issues Addressed:**

* **Unit Compatibility:**  Mixing percentages with incompatible units (e.g., `em`, `rem`, `px`).
* **Cascading Percentages:**  Issues arising from nested percentage calculations within `calc()` expressions.
* **Browser Compatibility:**  Variations in `calc()` support across different browsers.

**Solutions:**

The `bugSolution.css` file provides improved code demonstrating how to resolve these issues, often by using more compatible units, restructuring the calculations, and utilizing vendor prefixes where necessary for broader browser support.