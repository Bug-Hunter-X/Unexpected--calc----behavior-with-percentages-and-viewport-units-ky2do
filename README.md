# Unexpected `calc()` Behavior with Percentages and Viewport Units

This repository demonstrates a problem with the CSS `calc()` function when combining percentages and viewport units (like `vw` or `vh`).  The expected calculation does not produce the correct result.

## Bug Description

The `calc()` function is designed to perform calculations within CSS.  However, when percentages and viewport units are mixed, unexpected results can arise, potentially due to the order of operations or how the browser interprets the units. The expected outcome is not achieved, leading to layout discrepancies.

## Solution

The solution involves restructuring the CSS to avoid combining percentages with viewport units within the `calc()` function.  Alternative approaches, such as using absolute values or pre-calculating values, are also explored.