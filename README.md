# CSS Selector Typo Bug

This repository demonstrates a common yet easily missed bug in CSS: a typo in a class selector that prevents the intended styling from applying.

The `bug.css` file contains the incorrect CSS rule, while `bugSolution.css` provides the corrected version.

The issue lies in how CSS selectors handle concatenated class names versus descendant selectors.  The incorrect selector treats the concatenated string as a single class, whereas the correct selector uses a space to indicate a parent-child relationship.

This example highlights the importance of careful attention to detail when writing CSS selectors.