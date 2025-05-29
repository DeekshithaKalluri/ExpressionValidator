# Expression Validator: Sequence and Order Checker in C

## Overview

This C program reads a list of character expressions from a file and validates each one to determine if it maintains correct sequence and structural order. It is designed to identify mismatched or unbalanced expressions (e.g., incorrect use of parentheses, brackets, etc.).

## Features

- Reads input from `expressions.txt`
- Validates each expression line-by-line
- Uses a stack to track opening and closing characters
- Provides user feedback for incorrect sequences

## Files

- `main.c`: Source code containing the implementation.
- `expressions.txt`: Input file with expressions to be validated.

## How It Works

1. The program opens `expressions.txt`.
2. It reads each line as a separate expression.
3. Each expression is passed to a validation function.
4. The function uses a stack to ensure matching and correctly ordered symbols.
5. The result (valid/invalid) is printed for each expression.
