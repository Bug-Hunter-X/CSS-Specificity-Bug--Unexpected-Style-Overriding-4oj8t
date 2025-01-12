# CSS Specificity Bug

This repository demonstrates a common CSS bug related to specificity conflicts.  In this scenario, we have conflicting styles applied to the same HTML element, and the outcome might not be intuitive due to how CSS specificity is resolved. The `bug.css` file shows the conflicting styles, while `solution.css` provides a solution.

## Reproducing the Bug

1. Open `index.html` in your browser.
2. Observe the unexpected styling of the paragraph element.

## Understanding the Solution

The solution in `solution.css` prioritizes the intended style by using more specific selectors or overriding the cascading styles appropriately.