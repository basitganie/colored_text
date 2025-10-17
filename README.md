<<<<<<< HEAD
# Colored Text 🌈

## Author: Basit Ahmad Ganie
### Email: basitahmed1412@gmail.com

A Python module for printing colored text in the terminal with ANSI escape codes. Supports standard colors, bright colors, 256-color mode, and 24-bit RGB, HSL, hex codes, table formatting, text highlighting, random colors/backgrounds, progress_bar, gradient_text and text animations.

## Features ✨

- **Rich Color Support**: Standard, bright, 256-color, and 24-bit RGB colors
- **Multiple Color Formats**: RGB, HSL, HEX code support
- **Text Formatting**: Tables with various styles ('single', 'double', 'rounded')
- **Animations**: Predefined types like 'fade_in', 'blink', 'rainbow_wave'
- **Highlighting**: Text background highlighting
- **Random Colors**: Generate random colors for text or background

## Installation ⚡

```bash
pip install color_ur_text
```

## usage example
``` python
from color_ur_text import ColoredText

# Basic usage
print(ColoredText.red("Hello World!"))
print(ColoredText.rgb("RGB Color", 24, 64, 84))
print(ColoredText.hex("#FF5733", "Hex Color"))
print(ColoredText.animate("Blinking Text", animation_type="blink"))

# progress bar
print(ColoredText.progress_bar(progress))

# Table formatting
ColoredText.table(data, border_style='rounded')

# Text highlighting
ColoredText.highlight("Important! Text", "Text", bg_color='yellow')

# Random colors
ColoredText.random_color("Surprise!")

# Animations
ColoredText.animate("SYMPHONY", animation_type='rainbow_wave')

```

## Contributing 🤝
We welcome contributions! Here's how you can help:

Fork the repository

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

## License 📜
MIT License

Copyright (c) 2023 Basit Ahmad Ganie
=======
#color_ur_text
## A python library that provides various methods to stylize you terminal based apps or programs, like terminal coloring, GUI features like spinner, progress bar and animations like rainbow wave, typewriter etc anf many more feaures. 
## Note: Some terminal might not support the various color codes

# Installation
## You can install the module via pip using `pip install color_ur_text`

# Usage
```python
from color_ur_text import ColoredText as ct

ct.print_colored("Hello, World", ct.RED) prints Hello, World in RED
print(ct.rgb("Hello, World!", 255, 255, 0)) #prints Hello, World! in Yellow
print(ct.table("Hello")) #prints Hello in a box
#animations
ct.animate_text("WAVE ANIMATION", animation_type='rainbow_wave', speed=0.03, cycles=1)
#spinner
ColoredText.spinner("Loading data", duration=2.0, spinner_style='dots', color=(255, 0, 255))
```
>>>>>>> 7ecba33 (Save local changes before sync)
