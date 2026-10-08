# Week 7 Assignment: Shopping List Manager

## Files

- `list_warmup.py` - Demonstrates creating a list, accessing items by index, using append(), remove(), and len().
- `shopping_list.py` - A shopping list manager that allows users to add, remove, show, and finish their shopping list.
- `list_report.py` - Prints a numbered shopping list, counts item names with more than four letters, and finds the longest item name.
- `screenshots/` - Contains screenshots showing the programs running.

## Why check before using remove()?

Checking if an item is in the list before calling `.remove()` is safer because `.remove()` causes an error if the item does not exist. Using `in` lets the program handle a missing item without crashing. This makes the shopping list manager more reliable and user-friendly.