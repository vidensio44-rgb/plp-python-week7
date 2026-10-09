# Week 7 Assignment: Shopping List Manager

This project demonstrates Python list operations, interactive shopping list management, and list analysis using loops and conditions.

## Project Files

* **`list_warmup.py`** — Demonstrates list indexing, adding items with `append()`, removing items with `remove()`, and counting items with `len()`.
* **`shopping_list.py`** — Provides an interactive shopping list manager that allows users to add, remove, and display items, with a check for missing items.
* **`list_report.py`** — Prints a numbered shopping list, counts item names longer than four characters, and finds the longest item name using a loop.
* **`screenshots/`** — Contains screenshots showing the output of each program.

## Why is checking `in` before calling `.remove()` safer?

Checking whether an item exists in a list before calling `remove()` helps prevent a `ValueError`. If the item is missing, the program can display a helpful message instead of stopping unexpectedly. This makes the shopping list manager more reliable and user-friendly.

## Technologies Used

* Python
* Git and GitHub
