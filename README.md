# Tailwind CSS @apply Directive Issue with Pseudo-classes and Conditional Classes

This repository demonstrates a bug where Tailwind CSS's `@apply` directive doesn't correctly apply styles to pseudo-classes when the parent class is conditionally applied.  This often happens when using JavaScript to dynamically add or remove classes.  The solution provides a workaround that ensures the styles are applied correctly.

## Bug Reproduction

1. Clone the repository.
2. Open `bug.html` in your browser.
3. Observe that the hover effect is not applied to the element.

## Bug Solution

The solution is to avoid using `@apply` with pseudo-classes when the parent class is conditionally applied. Instead, use direct CSS rules or a different approach to achieve the desired styling.