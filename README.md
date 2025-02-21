# Unexpected Behavior of calc() with other CSS Units

This repository demonstrates a common issue encountered when using the `calc()` function in CSS with other units like `em`, `rem`, `vw`, `vh`, etc. The issue arises due to inconsistent handling of unit conversions and operator precedence across different browsers and CSS parsers.

## Bug Report
The `calc()` function in the `bug.css` file produces unexpected results when trying to calculate dimensions dynamically based on viewport size or other element dimensions.

## Solution
The `bugSolution.css` file provides a workaround that addresses the issue by ensuring correct unit conversion and operator precedence.  The solution might involve explicit unit conversions or using alternative layout techniques to achieve the desired result.

## Setup and Reproduction
1. Clone the repository.
2. Open `bug.html` in a web browser to observe the unexpected behavior.
3. Open `bugSolution.html` to see the corrected layout using the provided solution.

This example focuses on the common problems related to `calc()` and unit handling in CSS. It highlights the importance of careful unit management and thorough testing for cross-browser compatibility when using this powerful CSS feature.