# Unexpected Rendering Issues with Padding-Bottom Trick in CSS

This repository demonstrates an uncommon bug in CSS related to the use of `padding-bottom: 100%;` for creating square divs. This technique, while common, can lead to unexpected rendering issues in certain browsers when combined with other CSS properties like `box-sizing`, `margin`, or `float`.

## Bug Description

The `bug.css` file contains CSS code that uses the `padding-bottom: 100%;` trick.  Under certain conditions, the div's dimensions are not rendered as expected in some browsers. The `bugSolution.css` file provides a solution.

## Solution

The `bugSolution.css` file offers a more reliable solution for creating squares using techniques that avoid the unexpected behavior observed in the original code.