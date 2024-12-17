# CSS Float Issue: Parent Collapsing with Unspecified Width

This repository demonstrates a common issue that arises when using the `float` property in CSS without properly setting the width of the parent container.

## The Problem

The `bug.css` file contains a CSS rule that sets a `div` element to have a width of 50% and floats to the left.  If the parent container doesn't have its width explicitly defined, it may collapse, resulting in unexpected layout behavior.

## The Solution

The `solution.css` file demonstrates how to fix this problem by explicitly setting the width of the parent container.  By specifying a width for the parent, the floated children properly contribute to the parent's dimensions and prevent the parent from collapsing.

## How to Reproduce

1. Clone the repository.
2. Open `index.html` in your browser (you may need to create a simple HTML file with the relevant `div` structure).
3. Observe the layout differences between the bug and solution CSS.