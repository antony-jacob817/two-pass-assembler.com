# two-pass-assembler

This project demonstrates how a two-pass assembler works. A two-pass assembler is a type of assembler that processes the source code in two passes to generate machine code or intermediate code. This approach is commonly used to resolve forward references and build symbol tables efficiently.

## Features

- **Educational Purpose:** Clearly illustrates the working of a two-pass assembler.
- **Web-based Interface:** Built using HTML, CSS, and JavaScript for easy accessibility and visualization.
- **Step-by-Step Process:** Shows both Pass 1 (symbol table creation) and Pass 2 (code generation).

## Technologies Used

- HTML
- CSS
- JavaScript

## How It Works

1. **Pass 1:** Scans the assembly code to build a symbol table and detect labels.
2. **Pass 2:** Uses the symbol table to translate assembly instructions into machine code.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/antony-jacob817/two-pass-assembler.com.git
   ```
2. Open `index.html` in your web browser.

No additional dependencies are required.

## Example

- Input your assembly code in the provided interface.
- View the symbol table and generated machine code after both passes.
