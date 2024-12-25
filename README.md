# Incompatible Units in CSS `calc()` Function

This repository demonstrates a common yet easily overlooked issue in CSS: using incompatible units within the `calc()` function.  Mixing units like pixels and percentages directly without proper conversion can lead to unexpected behavior or parse errors.

The `bug.css` file contains the problematic code, while `bugSolution.css` provides the corrected version.

**Key takeaway:** Always ensure that units within your `calc()` expressions are compatible and follow correct mathematical operations.