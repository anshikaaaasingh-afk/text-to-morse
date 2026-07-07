# Text to Morse Code Converter

A simple terminal-based Python program that converts plain English text into Morse code.

## Features

- 🔤 Converts letters, numbers, and common punctuation into Morse code
- ⌨️ Simple terminal input/output
- 🔠 Case-insensitive (handles both uppercase and lowercase input)
- ␣ Preserves word spacing using `/` or extra space between Morse letter groups

## Demo

```
Enter text to convert to Morse code: hey i amd anshika
.... . -.-- .. .- -- -.. .- -. ... .... .. -.- .-
```

## Getting Started

### Prerequisites

- Python 3 installed on your system

### Installation

```bash
git clone https://github.com/anshikaaaasingh-afk/text-to-morse.git
cd text-to-morse
```

### Run

```bash
python3 text_to_morse.py
```

## Usage

1. Run the program.
2. Enter any text (letters, numbers, spaces) when prompted.
3. The program prints the corresponding Morse code translation to the terminal.

## How It Works

- Each character in the input is looked up in a Morse code dictionary (e.g., `A` → `.-`, `B` → `-...`).
- Letters within a word are separated by a single space.
- Words are separated by a `/` or a longer space, depending on implementation.
- Unsupported characters are skipped or flagged, depending on implementation.

## Project Structure

```
text-to-morse/
├── text_to_morse.py   # Main source file
└── README.md           # Project documentation
```

## Possible Improvements

- Add Morse-to-text (reverse) conversion
- Add support for playing Morse code as audio beeps
- Add a GUI or web interface
- Handle invalid/unsupported characters more gracefully with error messages
- Add unit tests for the encoding logic

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

Made by [Anshika](https://github.com/anshikaaaasingh-afk) as part of a growing Python/C/JavaScript portfolio.
