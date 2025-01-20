# Uncaught TypeError: Cannot read properties of null (reading 'style')

This repository demonstrates a common JavaScript error and its solution.  The error occurs when attempting to access the `style` property of a DOM element that doesn't exist, resulting in a `null` value.  The solution involves checking for `null` before accessing the element's properties.

## Bug

The `bug.html` file contains an error where JavaScript tries to access the `style` property of a non-existent element.

## Solution

The `solution.js` file provides a corrected version that checks if the element exists before manipulating its style.

This example is useful for understanding common JavaScript errors and best practices for handling DOM manipulation.