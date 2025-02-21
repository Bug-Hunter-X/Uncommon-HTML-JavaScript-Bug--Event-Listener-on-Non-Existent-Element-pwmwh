# Uncommon HTML/JavaScript Bug: Event Listener on Non-Existent Element

This repository demonstrates a subtle bug in HTML and JavaScript.  The code attempts to attach an event listener to an element that doesn't exist in the DOM, leading to a silent failure. The solution shows how to correctly handle this scenario to prevent unexpected behavior.

## Bug

The `bug.html` file contains the faulty code.  It tries to attach a click event listener to an element with the ID 'nonExistentElement', but this element is not present in the HTML structure. This will cause a runtime error in the browser console and no event handling occurs.

## Solution

The `bugSolution.html` file demonstrates the corrected version. It includes error handling that checks for the existence of the element before attempting to attach the event listener. This avoids the error and improves the robustness of the code.
