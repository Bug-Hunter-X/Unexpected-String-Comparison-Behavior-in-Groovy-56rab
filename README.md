# Unexpected String Comparison Behavior in Groovy

This example demonstrates a potential pitfall in Groovy related to comparing Strings using the `==` operator.  Groovy's dynamic typing and implicit type coercion can lead to unexpected results when dealing with null values and empty Strings.

The `bug.groovy` file shows a method that seemingly handles null input correctly, but might produce unexpected output when given an empty string because an empty string in Groovy is treated as a falsy value.

The solution, `bugSolution.groovy`, addresses this issue.