# F# Mutable Variable Swap Bug

This example demonstrates a common misunderstanding when working with mutable variables in F#.  Because mutable variables are passed by reference, a seemingly simple swap function can produce unexpected results if the programmer isn't aware of this behavior.

The `bug.fs` file contains the incorrect implementation.  The `bugSolution.fs` file provides a corrected version illustrating the use of tuples to properly swap values without modifying the original variables.