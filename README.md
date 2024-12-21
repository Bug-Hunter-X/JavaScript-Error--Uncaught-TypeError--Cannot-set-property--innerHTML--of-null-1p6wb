# Uncommon HTML Bug: Non-Existent Element Modification

This repository demonstrates a common yet easily overlooked error in HTML and JavaScript interaction: attempting to manipulate a DOM element that hasn't been defined in the HTML structure.  The bug arises when the JavaScript code tries to access and modify an element that does not exist in the rendered HTML. This results in a JavaScript error, specifically a 'TypeError: Cannot set property 'innerHTML' of null'.

## Bug Description:
The `bug.html` file contains an example where JavaScript tries to change the `innerHTML` property of a `div` element with the ID "nonExistentDiv".  However, this element is not present in the HTML, leading to the error.

## Solution:
The `bugSolution.html` file demonstrates the corrected version.  It ensures that the JavaScript code only attempts to modify elements that actually exist in the HTML structure before attempting to manipulate them.