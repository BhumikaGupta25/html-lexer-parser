# HTML Lexer and Parser using PLY
This project is a **Python-based lexer and parser for simplified HTML tags**, built using the [PLY](https://www.dabeaz.com/ply/) (Python Lex-Yacc) library.  
It can tokenize and parse a string containing `<b>`, `<i>`, and plain text into a structured representation of the HTML content.  
This project was created to learn and demonstrate how lexers and parsers work under the hood for markup languages like HTML.

---
## Features
- Lexes HTML strings into tokens:  
   `<b>`  
   `</b>`  
   `<i>`  
   `</i>`  
   plain text  
- Parses nested or flat HTML structures.
- Displays syntax errors if the input is invalid.
- Prints token stream and parsed tree structure.

---

## Technologies Used
- Python 3.x
- PLY (`ply.lex` and `ply.yacc`)
---

## Setup

Clone this repository:
```bash
git clone https://github.com/BhumikaGupta/html-lexer-parser.git
cd html-lexer-parser
```
---

## Requirements:
pip install ply
