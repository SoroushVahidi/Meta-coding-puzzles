## Cursor Cloud specific instructions

This repository is a collection of standalone algorithmic puzzle solutions for Meta career profile coding challenges. There is **no build system, no package manager, no test framework, and no external dependencies**.

### Languages and runtime requirements

- **Python 3** solutions: files without extensions (e.g., `ABCs`, `Cafeteria`). Each file defines one or more functions using only the standard library (`typing`, `math`, etc.). Run with `python3 -c "exec(open('<filename>').read()); print(functionName(args))"`.
- **C++ solutions**: files without extensions (e.g., `Hops`, `Kaitenzushi`). Use `#include <bits/stdc++.h>`. Compile with `g++ -std=c++11`. These define functions only (no `main()`), so a wrapper with `main()` is needed to test them.

### How to run solutions

- **Python**: `python3 -c "exec(open('ABCs').read()); print(getSum(1,2,3))"`
- **C++**: Create a wrapper file that includes the solution and adds a `main()`, then `g++ -std=c++11 -o solution wrapper.cpp && ./solution`

### Notes

- File names contain spaces and parentheses (e.g., `Director of Photography (Chapter 1)`). Always quote paths.
- There are no lint, test, or build commands defined in the repo. System Python 3 and g++ are the only requirements.
