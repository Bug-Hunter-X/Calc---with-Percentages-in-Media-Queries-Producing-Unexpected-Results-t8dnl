# CSS `calc()` Issue in Media Queries

This repository demonstrates a bug encountered when using the `calc()` function with percentages within CSS media queries.  The expected behavior is not occurring, leading to layout inconsistencies.  The `bug.css` file showcases the problem, while `bugSolution.css` provides a potential workaround.

## Problem

The `calc()` function appears to misinterpret or fail to correctly compute the percentage values when nested inside a media query. This results in unexpected rendering across different screen sizes.

## Solution

The provided solution in `bugSolution.css` explores potential alternative approaches to achieve the desired responsive layout.  It might involve avoiding the problematic usage of `calc()` with percentages in media queries or employing different CSS techniques.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` (you'll need to create a simple HTML file to test the CSS) in a web browser.
3. Observe the rendered layout and compare it with the expected outcome.  Resize your browser window to trigger the media query.
4. Compare the results to the corrected layout in `bugSolution.css`.
