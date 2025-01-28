# Flexbox `margin-left: auto;` Inconsistency

This repository demonstrates an uncommon issue encountered when using `margin-left: auto;` with `justify-content: space-between;` in CSS flexbox.

The problem lies in the order of operations. `justify-content: space-between;` distributes the space between flex items *before* `margin-left: auto;` is applied. This can lead to the second item not aligning to the right as expected in certain browsers.  The `bug.css` file contains the problematic code, while `bugSolution.css` offers a resolution.