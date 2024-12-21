# CSS Specificity Bug: Unexpected Float Clearing

This repository demonstrates a subtle CSS specificity issue that can lead to unexpected float clearing failures.

The `bug.css` file contains the problematic code.  The `bugSolution.css` file provides a corrected version.

The core issue is a specificity conflict between a generic selector and a more specific selector, resulting in the more specific selector failing to clear floats as intended.

This bug highlights the importance of understanding CSS specificity when working with complex layouts.