# C++ Array Min-Max Swap Utility

A clean, efficient, and optimized C++ console application that finds the minimum and maximum elements in an integer array in a single pass and swaps their positions.

---

## Repository Details
* **Suggested Repository Title:** `cpp-array-min-max-swap`
* **Suggested Description:** A C++ utility program that efficiently swaps the minimum and maximum values in an array using an optimized single-pass algorithm.

---

## Project Overview
This C++ program takes a predefined integer array, traverses it using an optimized single-pass approach to locate both the minimum and maximum elements along with their indices, and then swaps them using `std::swap`. 

## Key Features
* **Single-Pass Optimization ($O(n)$ Complexity):** Finds both the minimum and maximum elements in a single traversal loop, making it faster and more efficient than double-loop implementations.
* **Modern C++ Standards:** Uses `<climits>` for safe integer limit constants instead of legacy headers.
* **Safety Guards:** Includes a built-in validation check to handle empty or invalid array sizes gracefully and prevent runtime crashes.
* **Standard Library Utilities:** Utilizes built-in `std::swap` for clean and readable element swapping.

## Prerequisites
Ensure you have a C++ compiler (like GCC, MinGW, or Clang) installed on your system. You can compile and run your code using:
```bash
g++ main.cpp -o main
./main
