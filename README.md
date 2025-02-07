# CSS Specificity Issue: Unexpected Color Inheritance

This repository demonstrates a subtle bug in CSS related to specificity and inheritance. The problem arises when trying to style a paragraph within a div, where the div's color unexpectedly overrides the paragraph's explicit style due to specificity rules.

## The Bug
The `bug.css` file contains CSS code where the paragraph inherits the div's color even though it has its own explicit style. This is counter-intuitive for many CSS beginners.

## The Solution
The `bugSolution.css` demonstrates how to correctly address this problem by either using more specific selectors or by using `!important` (though it is generally discouraged).