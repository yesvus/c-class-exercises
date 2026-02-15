# MAT115E C Class Exercises

This repository contains C code snippets I wrote during my **MAT115E** class at **Istanbul Technical University**.

All code in this repository uploaded to GitHub to help new students.

## Notes

- These files are class exercises and practice snippets.
- The repository is intended as a learning reference for beginners.

## How to Compile and Run

Compile and run one C file (for example, `w3_lab1.c`) with `gcc`.

### macOS

- Compile: `gcc "file.c" -o program`
- Run: `./program`

### Windows (MinGW / MSYS2)

- Compile: `gcc "file.c" -o program.exe`
- Run: `program.exe`

## If `gcc` Is Not Found

### macOS

- Install Xcode Command Line Tools: `xcode-select --install`
- Check installation: `gcc --version`

### Windows

- Install **MSYS2** (recommended) or **MinGW-w64**.
- If needed, add the `bin` folder (where `gcc.exe` is) to your **PATH**.
- Reopen terminal and check: `gcc --version`