# 🧾 Golang CLI Billing System

A beginner-friendly, file-based billing system built in **Go**. This project was developed as part of my Golang learning journey to understand how to structure Go applications, work with files, use custom types, and interact with users via the command line.

---

## 💡 Description

This CLI application allows a user to generate a bill by:

1. Entering their name (used as the bill filename)
2. Choosing from three options:
   - `a` — Add an item (with name and price)
   - `t` — Add a tip
   - `s` — Save the bill to a file

Once saved, a `.txt` file is created inside the `bills/` folder using the customer name (e.g., `john.txt`) and contains all items, tip, and the total.

---

## 🗂️ Project Structure

├── main.go # Handles program flow and user input
├── bill.go # Contains the Bill struct and related methods
└── bills/ # Stores generated bill text files

---

## ✨ Features

- CLI-based interaction
- Create itemized bills with prices
- Add optional tips
- Save bill to a text file
- Use of Go structs, receiver methods, and file I/O

---

## 🚀 Getting Started

### Prerequisites

- [Go](https://go.dev/doc/install) installed on your machine

### Run the program

```bash
go run main.go
