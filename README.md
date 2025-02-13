# Uncommon CSS `calc()` Errors
This repository demonstrates some uncommon errors that can occur when using the `calc()` function in CSS. These include:

* **Order of Operations:** Incorrect order of operations within the calculation can lead to unexpected results.
* **Unit Mismatches:** Mixing different units (e.g., pixels and percentages) can produce unintended outcomes.
* **Parent Container Issues:** The calculation depends on the parent container's dimensions, and unexpected behavior can happen if the parent container has unexpected dimensions or no defined width.

The `bug.css` file demonstrates these errors, while `bugSolution.css` provides corrected versions.

## How to Reproduce
Clone this repository and open `bug.html` in your browser. Compare the results with the corrected version in `bugSolution.html`.