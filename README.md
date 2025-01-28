# CSS Specificity and !important; Unexpected override.

This repository demonstrates a scenario where CSS specificity overrides the `!important` declaration, which might be an unexpected behavior for some developers.

The `bug.css` file contains the erroneous CSS, while the `bugSolution.css` file provides solutions.

## Bug Description
The bug lies in the unexpected behavior of CSS specificity in the presence of the `!important` declaration.  A more specific selector can still override a style declared with `!important`.

## Solution
The solution involves understanding and managing CSS specificity correctly.  One approach is to refactor the CSS to avoid such conflicts, by removing the unnecessary `!important` or changing the selectors, which is implemented in `bugSolution.css`.