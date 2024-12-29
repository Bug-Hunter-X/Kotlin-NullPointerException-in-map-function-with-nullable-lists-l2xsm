# Kotlin NullPointerException in map function with nullable lists

This example demonstrates a common error when using the `map` function in Kotlin with potentially null lists.  The `map` function will throw a `NullPointerException` if the list is null. The solution shows how to handle this using the safe call operator `?.` and the Elvis operator `?:` for providing a default value.

The `BuggyMap.kt` file shows the error case.  `FixedMap.kt` provides the solution.
