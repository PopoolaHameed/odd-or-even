# Odd or Even Checker

A C++ program that reads an integer from standard input and reports whether it is odd or even.

## Requirements

- A C++ compiler (e.g., g++, clang++, MSVC)

## Build

```bash
g++ -o odd_or_even main.cpp
```

## Run

```bash
./odd_even
```

## Example

```
Enter a number: 7
7 is odd
```

```
Enter a number: -4
-4 is even
```

## How It Works

The program applies the modulo operator (`n % 2`) to the input. A remainder of `0` means the number is even; otherwise it is odd. The input is stored as a `long long`, so large values and negative numbers are supported.

## Limitations

- Input must be an integer within the range of `long long`.
- Non-numeric input is not handled.
