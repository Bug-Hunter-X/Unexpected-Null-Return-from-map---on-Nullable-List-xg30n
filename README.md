# Kotlin map() and Nullable Lists

This example demonstrates how Kotlin's `map()` function interacts with nullable lists.  Unlike some languages that might throw a NullPointerException, Kotlin's `map()` returns `null` when applied to a nullable list that is null.  This can lead to unexpected behavior if not handled correctly.

The `Bug.kt` file shows the issue, and `BugSolution.kt` shows a safe way to handle potential null values.

## How to Run

1. Save the code snippets as `Bug.kt` and `BugSolution.kt`.
2. Compile and run using a Kotlin compiler (e.g., Kotlin/JVM).

## Related Issues

* Safe handling of nullable values is a key aspect of Kotlin's null safety features.
* Understanding how collection operations handle nulls can prevent unexpected runtime errors.