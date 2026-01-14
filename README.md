# Fibonacci with Memoization in Go
Implementation of Fibonacci number calculation using a cache system (memoization) to optimize performance.

## Features
- Reusable implementation of the memoization pattern
- Reduces complexity from O(2^n) to O(n)
- Includes time metrics to compare executions

## Execution Flow
1. A cache is created with the Fibonacci function
2. When requesting a number, the cache checks if it was already calculated
3. If it exists, returns the value immediately
4. If it doesn't exist, calculates, stores, and returns the result

## Limitations
- The cache grows indefinitely
- The cache is not thread-safe
