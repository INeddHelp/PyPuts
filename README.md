

# PyPuts: A Python Library for Colorful and Readable Console Output

PyPuts is a simple and lightweight Python library that provides an easy way to print colorful and readable messages on the console.
It is designed to replace the built-in print() function with a more powerful and customizable puts() function that allows you to easily add color and formatting to your messages.

With PyPuts, you can quickly add colors, bold, underline, and other effects to your messages. You can also customize the color and formatting of each message to make it stand out or to match your brand style.

![Screenshot1](https://i.ibb.co/9GjN834/Screenshot-from-2023-04-01-09-01-27.png)   ![Screenshot2](https://i.ibb.co/VJQTNWk/Screenshot-from-2023-04-01-09-07-14.png)
# Features:

- Easy to use: Simply replace print() with puts() to start using PyPuts.
- Customizable: PyPuts allows you to customize the color and formatting of your messages.
- Lightweight: PyPuts is a lightweight library with no external dependencies.
- Cross-platform: PyPuts works on all major platforms, including Windows, macOS, and Linux.

# Installation:

You can install PyPuts using pip:
```
pip install pyputs
```

# Usage
```
from pyputs import puts

puts('red', 'Hello, world!')
puts('green', 'Hello world!')
puts('blue', 'Hello world')
```

## List of colors:

Escape code:
```
escape_codes = {
    "reset": "\033[0m",
    "bold": "\033[1m",
    "dim": "\033[2m",
    "underline": "\033[4m",
    "blink": "\033[5m",
    "reverse": "\033[7m",
    "hidden": "\033[8m",
    "black": "\033[30m",
    "red": "\033[31m",
    "green": "\033[32m",
    "yellow": "\033[33m",
    "blue": "\033[34m",
    "magenta": "\033[35m",
    "cyan": "\033[36m",
    "white": "\033[37m",
    "bg_black": "\033[40m",
    "bg_red": "\033[41m",
    "bg_green": "\033[42m",
    "bg_yellow": "\033[43m",
    "bg_blue": "\033[44m",
    "bg_magenta": "\033[45m",
    "bg_cyan": "\033[46m",
    "bg_white": "\033[47m",
}
```

# Contributing:

PyPuts is an open-source library, and contributions are welcome. If you find a bug or have an idea for a new feature, please open an issue or submit a pull request on GitHub.

# License:

PyPuts is released under the MIT License. See the LICENSE file for details.
