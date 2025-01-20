# Java Off-by-One Error Example

This repository demonstrates a common off-by-one error in Java when iterating over arrays. The `BuggyArrayIteration.java` file contains code with the error, resulting in an `ArrayIndexOutOfBoundsException`. The corrected version, `CorrectedArrayIteration.java`, shows how to fix the issue.

**How to reproduce:**
1. Compile `BuggyArrayIteration.java`.
2. Run the compiled class. You'll see the exception.
3. Compile and run `CorrectedArrayIteration.java` to see the correct output.

**Lesson:** Pay close attention to loop conditions when working with arrays in Java (or any language).  Using `<` instead of `<=` for the upper bound is crucial to avoid index out of bounds exceptions.