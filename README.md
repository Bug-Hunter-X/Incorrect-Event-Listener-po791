# Uncommon HTML Bug: Incorrect Event Listener
This example demonstrates a subtle error in how event listeners are added to HTML elements using Javascript.  The code uses the `onclick` property directly, which can be problematic in some cases and can be hard to maintain.

## Bug
The event listener in `bug.html` is added directly using the `onclick` property of the element. This can lead to problems if multiple event listeners need to be attached to the same element. It is also prone to errors and less organized.  

## Solution
The `bugSolution.html` file shows how to correct this by using the standard `addEventListener` method.  This method is preferred, as it allows for multiple listeners to be attached to the same element and provides more flexibility. 

This is an uncommon error but can be a source of confusion for less experienced developers.