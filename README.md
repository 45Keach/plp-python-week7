# Week 7 Assignment: Hands-On Lab — Shopping List Manager

This repository contains the three Python programs for the Week 7 list operations assignment.

- `list_warmup.py` — demonstrates list indexing, `.append()`, `.remove()`, and `len()`.
- `shopping_list.py` — provides an interactive menu to add, remove, and show shopping items, or quit.
- `list_report.py` — prints a numbered list, counts names longer than four characters, and finds the longest item.
- `screenshots/` — contains terminal-style output previews for the three programs.

Checking whether an item is in the list before calling `.remove()` is safer because `.remove()` raises a `ValueError` if the item is missing. Using `in` lets the program handle that situation gracefully and show a helpful message instead of crashing. It also makes the program more reliable when users enter unexpected items.
