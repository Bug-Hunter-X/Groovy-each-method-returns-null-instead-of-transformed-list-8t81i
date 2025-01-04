# Groovy each method returns null

This example demonstrates a common issue with Groovy's `each` method.  The `each` method iterates over a collection and applies a closure to each element. However, it doesn't return a new collection containing the transformed elements; instead, it returns `null`. This can be unexpected for developers coming from other languages.

The provided `bug.groovy` file shows the problem.  The solution, `bugSolution.groovy`, offers alternative approaches to achieve the desired result.