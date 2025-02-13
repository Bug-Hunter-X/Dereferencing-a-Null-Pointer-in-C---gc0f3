# Dereferencing a Null Pointer in C++

This repository demonstrates a common C++ error: dereferencing a null pointer.  The `bug.cpp` file contains the erroneous code, while `bugSolution.cpp` provides a corrected version.

**Problem:**
Attempting to access memory pointed to by a null pointer results in undefined behavior, often causing a program crash.

**Solution:**
Always check if a pointer is null before dereferencing it using an `if` statement to avoid this type of error.