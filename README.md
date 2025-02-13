# show

A simple and lightweight terminal-based text file viewer.

## Features
- Quickly display the contents of a text file in the terminal
- Supports navigation with arrow keys or `less`-like controls
- Lightweight and fast
- Syntax highlighting for popular programming languages (if applicable)
- Line numbering option

## Installation

```sh
git clone https://github.com/pieandcoffe/show.git
cd show
make install
```

## Usage

```sh
show file.txt
```

### Navigation
- **Arrow Keys / j k** - Scroll line by line
- **Space / f** - Scroll down one page
- **b** - Scroll up one page
- **q** - Quit viewer

## Example

```sh
show README.md
```

## Requirements
- A Unix-based system (Linux, macOS, WSL)
- ncurses library (if applicable)

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
MIT License
