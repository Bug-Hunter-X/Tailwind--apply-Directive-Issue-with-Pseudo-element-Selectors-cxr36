# Tailwind CSS @apply Directive Issue with Pseudo-element Selectors

This repository demonstrates a bug where Tailwind's `@apply` directive fails to apply styles when using pseudo-element selectors (like `::before` and `::after`).

## Problem

The `@apply` directive is unable to correctly process and apply CSS rules containing pseudo-element selectors.  This results in the styles not being applied to the pseudo-elements as expected.

## Solution

Instead of using `@apply` with pseudo-element selectors, directly apply the CSS classes or use a utility-first approach within the pseudo-element selectors themselves.

## Steps to Reproduce

1. Clone this repository.
2. Open `bug.html` in your browser. Observe the missing styles on the pseudo-element.
3. Open `bugSolution.html` to see how to solve the problem.