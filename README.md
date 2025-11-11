# Keybindings Reference

A simple tool to format and display keybindings for various applications using walker.

## Overview

This project provides a convenient way to view and reference keybindings for different applications. It includes:
- **Keybinding files** for any applications (Vim, Yazi, etc)
- **Main script** (`keybindings`) to easily access and display keybindings


## Usage

### Viewing Keybindings

```bash
./keybindings [app-name]
```

## Keybinding File Format

Keybinding files use a simple format:

```
# Comments start with #
<action description> - <keybinding>
```

Example:
```
# Navigation
move left - h
move right - l
```

## Adding New Keybindings

1. Create a new `.bind` file in the `keybinds/` directory
2. Follow the format: `action - keybinding`
3. Use `#` for comments and section headers
4. The script will automatically detect and list your new file

## Requirements

- Bash shell
- AWK (standard on most Unix-like systems)


## Contributing

To add keybindings for a new application:

1. Create a new file in `keybinds/` with the `.bind` extension
2. Follow the existing format
3. Test with the formatter to ensure proper alignment

## License

This is a personal reference tool. Feel free to use and modify as needed.
