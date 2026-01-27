# Go Bill Generator 🧾

This is a CLI (Command Line Interface) application built with **Go** that allows users to create, manage, and save bills/receipts to local text files.

## Features
- **Dynamic Bill Creation**: Name your bill and add items interactively.
- **Pointer-based Logic**: Uses pointer receivers to efficiently update bill data.
- **File System Integration**: Automatically saves formatted bills into a `/bills` directory.
- **Interactive UI**: Clean terminal prompts for adding items, tips, and saving.

## Technical Highlights
This project was built on **Day 4** of my Go journey. Key concepts practiced:
- Structs and Custom Types
- Map data structures for item storage
- **Pointers vs. Value Semantics**
- Input handling using `bufio` and `os` packages

## How to Run
1. Clone this repository.
2. Ensure you have Go installed.
3. Run the following command in your terminal:
   ```bash
   go run main.go bill.go
