# Unexpected Div Rendering with Float and Percentage Width

This repository demonstrates a common issue with CSS floats and percentage widths.  The issue occurs when using percentages for width with floating elements and the parent container's width is not cleanly divisible by the float width.

## Problem

The `bug.css` file contains CSS that attempts to make two divs occupy 50% of the parent container's width each.  In some browsers, this results in inaccurate rendering; you might see extra space, or the divs may overlap.  This is inconsistent across browsers and can be difficult to debug.

## Solution

The `bugSolution.css` file offers a solution to this problem using flexbox, providing consistent layout across browsers.

This demonstrates a practical example of why flexbox is often preferred over floats for modern layouts.