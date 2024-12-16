# Inconsistent Rendering of Nested Inline Elements

This repository demonstrates an uncommon HTML bug related to the rendering of nested inline elements within a block-level element.  The bug manifests as inconsistencies in how different browsers interpret and display the nested structure, leading to unpredictable visual results.

The `bug.html` file contains the problematic HTML code.  The `bugSolution.html` file offers a solution to improve rendering consistency.

## Bug Description

The issue arises from the nested use of `<span>` elements (inline) inside a `<p>` element (block-level), and this further nested within a `<div>` (block-level). While technically valid HTML, this can lead to rendering differences among browsers due to variations in how they handle the implicit line breaks and collapsing of whitespace.

## Solution

The solution involves restructuring the HTML to better reflect the intended layout using more semantically appropriate elements and avoiding excessively nested inline elements.  This reduces ambiguity in how the browser should render the content.