# **Part 2**
Answers:

1. The bug is that it doesn't arithmetically add the two numbers. Instead, it concatenates them as if they were strings. Currently, the program is just reading in the values of the inputs, which are given as strings.
2. To fix this issue, we have to parse the two inputs to become ints. We do this by using `parseInt()`.