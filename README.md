# Uncommon HTML Bug: Accessing innerHTML of Non-Existent Element

This repository demonstrates a less common HTML bug that can be tricky to identify and fix. The bug involves trying to access and modify the `innerHTML` property of an element that does not exist in the DOM. This typically results in a runtime error, halting script execution.

## Bug Description:

The `bug.html` file contains a script that attempts to modify the `innerHTML` of an element with the ID "nonExistentElement". Since this element is not defined in the HTML, the script throws an error.

## Solution:

The solution, shown in `bugSolution.html`, involves checking for the existence of the element before attempting to access its `innerHTML`.  This prevents the runtime error by ensuring the script only attempts to modify existing elements.