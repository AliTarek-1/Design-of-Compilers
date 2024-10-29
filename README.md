Here is a `README.md` for your project:

---

# Design of Compilers - C Lexical and Syntax Analyzer

This project, developed as part of a compiler design course under Dr. Wafaa Samy, implements the lexical and syntax analysis phases of a compiler for the C programming language. It utilizes C++ and the wxWidgets library for a graphical user interface (GUI).

## Project Overview

The purpose of this project is to create a compiler component that reads and analyzes C source code, breaking it into tokens and verifying its syntactic structure. Our application processes input C code to deliver structured outputs, including tokens, a symbol table, and a parse tree, and identifies syntax errors when present.

### Project Team
- **Team Size**: 5 students
- **Supervising Professor**: Dr. Wafaa Samy

### Project Phases

1. **Lexical Analysis (Lexer)**: 
   - Identifies tokens based on the C language's specifications, such as keywords, identifiers, data types, and statements.
2. **Syntax Analysis (Parser)**:
   - Analyzes the sequence of tokens to ensure it adheres to the grammatical rules of the C language.
   - Constructs a parse tree and builds a symbol table.

### GUI Features
- **Input**: A C source code file.
- **Outputs**:
  - Token List
  - Symbol Table
  - Parse Tree
  - Error Messages for Syntax Errors

## Language Specifications

The project focuses on fundamental C programming constructs, including:
- Keywords, Identifiers, Data Types, and Functions
- Statements:
  - Assignment, Declaration, Return, Iterative, Conditional, and Function Call Statements
- Expressions:
  - Arithmetic and Boolean expressions

## Implementation Details

1. **Lexer**: Tokenizes the input source code by recognizing patterns in the C language.
2. **Parser**: Constructs a parse tree based on grammar rules, generates a symbol table, and validates syntactic correctness.

## Project Requirements

### Task Breakdown and Submission Timeline

| Task                          | Details                                                         | Due Date (Week) |
|-------------------------------|-----------------------------------------------------------------|-----------------|
| **Team Formation**            | Submit names of team members.                                  | 3               |
| **Language Specifications**    | Define and submit C language specs document.                  | 4               |
| **Lexical Analyzer**           | Submit lexer code, demo video, and documentation.             | 6               |
| **Syntax Analyzer**            | Submit parser code, grammar rules, symbol table, parse tree.  | 11              |
| **Final Submission**           | Submit final project code, documentation, and demo video.     | 13              |
| **Project Discussion**         | Presentation and individual Q&A with team members.            | 13              |

## Final Submission

- **Code**: Complete lexer and parser source code.
- **Documentation**: Comprehensive project documentation covering implementation, screenshots, and test cases.
- **Demo Video**: Demonstrates key functionalities of the lexer and parser.
- **Presentation**: Overview of the project with demonstration and test cases.

## Installation and Usage

1. **Requirements**: Install C++ and wxWidgets library.
2. **Running the Application**:
   - Load the C source code file.
   - View the token list, symbol table, parse tree, and any syntax error messages.

---

