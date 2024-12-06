# Unintended Styling Due to Overly General Class Selector

This repository demonstrates a common yet subtle CSS bug: using class selectors that are too general. This leads to unintended styling applied to elements that are not supposed to be styled that way.

## The Bug

The `bug.css` file contains a CSS rule that styles elements with the class `button`. This class is too general and might inadvertently apply styles to elements that should not be visually represented as buttons.

## The Solution

The `bugSolution.css` file provides a solution that uses more specific selectors to avoid unintended styling. It uses more descriptive class names and potentially more specialized selectors (id selectors or even more nested class selectors) to ensure that the styles are only applied to the intended elements.