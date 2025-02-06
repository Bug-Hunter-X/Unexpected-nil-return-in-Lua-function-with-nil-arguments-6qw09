# Lua Function Unexpected Nil Return

This repository demonstrates an unexpected behavior in a Lua function when both arguments are nil.  The function `foo` is designed to return either `a`, `b`, or their sum. However, it returns `nil` when both `a` and `b` are nil, instead of handling this case gracefully (e.g., returning 0 or another default value).

The `bug.lua` file shows the problematic code and its unexpected output. The `bugSolution.lua` file provides a corrected version of the function.