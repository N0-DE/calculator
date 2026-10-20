# Tkinter GUI Calculator

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![GUI](https://img.shields.io/badge/GUI-Tkinter-brightgreen?style=flat)](https://docs.python.org/3/library/tkinter.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A lightweight desktop calculator built in Python using the standard `tkinter` GUI framework. Features both interactive on-screen keypad controls and physical keyboard event bindings.

## Features
- **Interactive Graphical Interface**: Clean grid layout for digits and standard arithmetic operators (`+`, `-`, `*`, `/`).
- **Physical Keyboard Event Handling**: Full keybinding integration for numeric keys `0`–`9`, operators, `Return` / `Enter` for calculation, `BackSpace` for single-digit deletion, and `Delete` for clear.
- **Robust Error Handling**: Exception trapping to catch malformed syntax without crashing the application.
- **Zero External Dependencies**: Runs out-of-the-box using Python's standard library.

## Getting Started

### Prerequisites
- Python 3.8 or higher (Tkinter is included in official Python installers on Windows and macOS).

### Running the Application
```bash
python "tk calculator.py"
```

## Keyboard Shortcuts
| Key | Action |
|---|---|
| `0` - `9` | Input number |
| `+`, `-`, `*`, `/` | Arithmetic operations |
| `Enter` / `Return` | Calculate result |
| `Backspace` | Undo / delete last character |
| `Delete` | Clear all input |

## License
Distributed under the [MIT License](LICENSE).
