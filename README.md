# Uncommon CSS Selector Errors
This repository demonstrates a couple of uncommon CSS errors related to invalid or unexpected selectors.  These errors can be tricky to debug because they might not always produce obvious errors in the browser's developer console.  The `bug.css` file contains the erroneous code, while `bugSolution.css` provides the corrected versions.

## Bug Description
The `bug.css` file includes CSS selectors that are either invalid (won't parse correctly) or highly unlikely to match any elements in a typical HTML structure. This leads to styles not being applied as expected, making debugging more challenging than typical syntax errors.

## Solution
The `bugSolution.css` file shows how to correct these errors and ensure the styles are applied correctly. This involves using proper attribute selectors and verifying that the selectors actually target existing HTML elements.
