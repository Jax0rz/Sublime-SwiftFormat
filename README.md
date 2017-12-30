# SublimeSwiftFormat

A simple plugin to format swift code in Sublime Text.

## Prerequisites

- macOS
- Xcode
- SwiftFormat

> This package relies on the amazing [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) to format Swift source code files.

> The simplest way to install the `swiftformat` command-line tool is via [Homebrew](http://brew.sh/). If you already have Homebrew installed, just type
>
> ```
> brew update
> brew install swiftformat
> ```

## Installation

#### Package Control

1. Install [Package Control](https://packagecontrol.io/)
2. Run `Package Control: Install Package` in the Command Palette (Super+Shift+P)
3. Install `SwiftFormat`

#### Manual

1. Navigate to the Sublime Text package directory

2. Clone the repository

   ```bash
   git clone https://github.com/Jax0rz/SublimeSwiftFormat.git
   ```

## Commands

- `SwiftFormat: Format Selection`
  - Format the current selection
- `SwiftFormat: Format File` (<kbd>Ctrl+k</kbd>, <kbd>Ctrl+f</kbd>)
  - Format the current file
- `SwiftFormat: Enable Format on Save`
  - Enable automatic formatting of swift source files on save
- `SwiftFormat: Disable Format on Save`
  - Disable automatic formatting of swift source files on save

## Configuration

- `swift_format_on_save`
  - Automatically format files on save
- `swift_format_binary`
  - Full path to `swiftformat` binary (if not on `PATH`)

## Thanks

This Plugin is heavily inspired by [RustFormat](https://packagecontrol.io/packages/RustFormat)

## License

MIT License