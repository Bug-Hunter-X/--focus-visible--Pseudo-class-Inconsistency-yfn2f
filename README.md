# :focus-visible Pseudo-class Inconsistency

This repository demonstrates an issue with the CSS `:focus-visible` pseudo-class.  The expected behavior is that styles applied with `:focus-visible` should only be applied when the focus is visually apparent to the user—typically when the user interacts with an element using keyboard or mouse, but not when programmatically focused via JavaScript.

However, in the provided code, the styles are being applied even when the element is focused programmatically, overriding the intended behavior of `:focus-visible`.

The `bug.css` file contains the problematic CSS, and `bugSolution.css` offers a possible solution to address this inconsistency.

## Setup

1. Clone this repository.
2. Open `index.html` (not included, but implied) in your browser.