# LLVM C++ Compiler

LLVM C++ Compiler is an example compiler project for the C++ programming language, implemented in C.

## Overview

This project serves as an educational resource for those interested in learning LLVM, a collection of modular and reusable compiler and toolchain technologies. The LLVM C++ Compiler project provides a hands-on experience of building a simple C++ compiler using LLVM, even though the compiler itself is implemented in C.

## Features

- **Lexical Analysis**: Tokenizes the input C++ source code into tokens such as keywords, identifiers, literals, and operators.
- **Parsing**: Parses the token stream to generate an abstract syntax tree (AST) representing the syntactic structure of the source code.
- **Semantic Analysis**: Performs semantic checks to ensure the correctness of the source code, such as type checking and scope resolution.
- **Code Generation**: Translates the AST into LLVM intermediate representation (IR) code.
- **LLVM Integration**: Utilizes LLVM libraries and tools for generating and optimizing machine code.

## Technologies Used

- **C**: Programming language used for implementing the compiler.
- **[LLVM](https://llvm.org/)**: Compiler infrastructure providing libraries and tools for building compilers.
- **Lex & Yacc**: Tools for lexical analysis (Lex) and parsing (Yacc).

## Getting Started

To use the LLVM C++ Compiler project, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine.

2. **Build the Compiler**: Build the compiler using the provided build instructions or scripts.

3. **Compile C Programs**: Use the compiler to compile C source code files by passing them as input.

4. **Run Compiled Programs**: Execute the compiled programs to see the output.

## Discover The Project

To understand the basics of the project review the code in /include/tinylang directory.

