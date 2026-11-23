# Week 6 Assignment — Safe Functions & Error Handling

- `safe_tools.py`: Contains `safe_divide`, `safe_number`, and `get_field` with `try / except` blocks to prevent crashes on zero division, invalid integer text, and missing dictionary keys.
- `README.md`: Provides an overview of the repository files and explains how `try / except` handles invalid conversions.

An `if` check alone cannot reliably catch `"abc"` without handling the `ValueError` raised by `int()` because checking every possible invalid string format is brittle, whereas `try / except ValueError` safely catches any non-numeric input when conversion fails.