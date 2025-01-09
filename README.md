# CSS Specificity Bug

This repository demonstrates an uncommon CSS bug related to selector specificity.  The bug involves unexpected style overriding in nested elements due to the complex interaction of various CSS selectors. The main bug file (`bug.css`) contains the problematic CSS code, while the solution file (`bugSolution.css`) provides a corrected version.

## Bug Description

The bug arises from the unexpected behavior of CSS specificity. Highly specific selectors can unintentionally override styles set by less specific selectors, even when the more specific selectors might seem logically secondary.