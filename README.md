
# PLP Week 6 Assignment - Safe Functions

## Files

- `safe_tools.py`: Contains three safe functions for division, number conversion, and dictionary field lookup.
- `README.md`: Describes the assignment and explains why error handling is important.

## Why can the `if` check not catch `abc` on its own?

An `if` statement cannot automatically catch an error raised when converting invalid text into an integer. The `int()` function raises a `ValueError` for input such as `"abc"`, so we use `try` and `except ValueError` to handle the error safely and keep the program running.
