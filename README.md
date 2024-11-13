# Children's Learning App

## Overview
This project is a **Children's Learning App** developed in Assembly language. It provides a simple, interactive way for young users to learn letters and numbers by recognizing input characters and displaying appropriate responses. The program's goal is to offer a foundational learning experience by helping children identify alphabet characters and numbers and receive feedback based on their inputs.

## Features
- **Alphabet Recognition**: Identifies both uppercase and lowercase letters.
- **Number Recognition**: Recognizes numerical characters from 0 to 9.
- **Interactive Responses**: Provides custom messages for each recognized character, making learning engaging for young users.
- **Exit Condition**: The app concludes with a "Thank you" message when a specific character (e.g., `'*'`) is entered, allowing for a natural stopping point.

## Technical Requirements
- **Assembler**: The program can be assembled using TASM, MASM, or any compatible assembler.
- **Environment**: A DOS-compatible environment, such as DOSBox, is recommended to run the compiled `.exe` file.

## Setup Instructions
1. Download or clone this repository to access the `.asm` file.
2. Make sure you have an assembler installed (e.g., MASM or TASM).

### Assembly and Linking
To build the program:
1. Assemble the program using either TASM or MASM:
   ```bash
   tasm main.asm
   tlink main.obj
