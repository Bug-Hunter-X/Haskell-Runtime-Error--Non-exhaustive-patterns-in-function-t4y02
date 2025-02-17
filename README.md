# Haskell Undefined Value Bug

This repository demonstrates a common error in Haskell programming: using `undefined` without proper handling. The `undefined` value signifies an incomplete or missing computation. Attempting to use it in an expression will result in a runtime exception.

The `bug.hs` file contains the problematic code. The `bugSolution.hs` file provides a corrected version.  The core issue is the lack of pattern matching or a default case to handle the undefined variable, leading to the runtime error.  Learning to avoid and properly handle `undefined` values is crucial for robust Haskell development. 