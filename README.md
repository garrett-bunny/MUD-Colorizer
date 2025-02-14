# MUD Colorizer

## Overview
MUD Colorizer is a simple web-based tool that allows you to apply and visualize MUD color codes in various formats. It provides support for multiple color schemes and allows users to format their text with gradients and predefined color patterns.

## Features
- Supports multiple color code formats: `@xNNN`, `{xNNN`, `$xNNN`, `@[FNNN]`, `\t[FNNN]`, and `&NNN`.
- Provides a text input area for pasting and formatting text.
- Allows selection of different font styles for previewing text.
- Includes gradient presets for applying colorful patterns.
- Offers three pattern styles: **Original**, **Distributed**, and **Symmetrical**.
- Supports viewer mode and edit mode.

## Installation
No installation is required. Simply download the HTML file and open it in a web browser, or visit the website here
https://coffee-nerd.github.io/MUD-Colorizer/

Alternatively, clone this repository:
```bash
git clone https://github.com/coffee-nerd/MUD-Colorizer.git
cd MUD-Colorizer
```

## Usage
1. Open `index.html` in a modern web browser.
2. Select a mode:
   - **Edit Mode**: Allows you to modify text and apply gradients.
   - **Viewer Mode**: Displays formatted text without allowing editing.
3. Paste your text into the **Text Input** field.
4. Choose a color code format from the **Color Codes** dropdown.
5. (Optional) Select a **Gradient** and **Pattern** to apply color transitions.
6. View the formatted output in the preview area.

## Configuration
### Fonts
You can select a font from the dropdown to preview the output in different styles. Available fonts include:
- Courier New
- Fira Code
- Hack
- JetBrains Mono
- Roboto Mono
- Source Code Pro
- Ubuntu Mono
- Monaco
- Consolas
- Anonymous Pro

### Color Formats
MUD Colorizer supports multiple color encoding schemes:
- `@xNNN` (Xterm colors)
- `{xNNN` (Alternative Xterm format)
- `$xNNN` (Another variation of Xterm colors)
- `@[FNNN]` (F-colors)
- `\t[FNNN]` (Xterm Builder F-colors)
- `&NNN` (Xterm format using `&` prefix)

### Gradients
A variety of preset color gradients are available for quick formatting. These can be applied to text dynamically.

### Patterns
Three pattern options allow customization of how colors are distributed across text:
- **Original**: Applies colors sequentially.
- **Distributed**: Spreads colors evenly across the text.
- **Symmetrical**: Reflects colors symmetrically.

## Contributing
Contributions are welcome! If you find a bug or have an idea for improvement, feel free to fork the repository and submit a pull request.

## Credits
Developed by **Demon, Despair, Asmodeus, or Jeff**. Find me on GitHub: [coffee-nerd](https://www.github.com/coffee-nerd/)

## License
This project is open-source. If you use this tool, it would be nice if you credit the original author.

Also, if you want to add some gradients of your own (I'd love for you to), please make a pull request!
