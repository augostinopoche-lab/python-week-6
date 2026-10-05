# Python Week 6 - Error Handling

This assignment practices using try/except to handle errors safely.

## Files

- `safe_tools.py` - Contains three safe functions for division, number conversion, and dictionary field lookup.
- `unbreakable.py` - Demonstrates how to handle invalid number input without crashing the program.
- `README.md` - Describes the assignment and explains why an if check cannot catch invalid text such as `abc`.

## Why can the if check not catch `abc` on its own?

An if check can test a condition, but `int("abc")` causes a ValueError while Python is trying to convert the text into a number. The conversion must be protected with try/except so the error can be caught and the program can continue running.