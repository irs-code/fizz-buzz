# FizzBuzz (C++)

A simple **FizzBuzz** implementation in **C++**.

## What it does

For each integer from 1 to *N*:

- Prints `Fizz` if the number is divisible by 3
- Prints `Buzz` if the number is divisible by 5
- Prints `FizzBuzz` if the number is divisible by both 3 and 5
- Otherwise prints the number itself

## Requirements

- A C++ compiler with **C++17** support (or newer)
  - GCC 7+, Clang 5+, or MSVC 2019+ should work

## Build

From the repository root:

```bash
# Linux/macOS (GCC/Clang)
g++ -std=c++17 -O2 -Wall -Wextra -pedantic -o fizzbuzz main.cpp

# Windows (MSVC Developer Command Prompt)
cl /std:c++17 /O2 /W4 main.cpp
