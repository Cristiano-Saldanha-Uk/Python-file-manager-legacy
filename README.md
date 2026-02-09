# 📁 Python File Manager (Legacy Project)

This repository contains a **menu-driven file management program** written in Python during my **high school years**.  
It is preserved here to showcase my **early learning journey** and foundational understanding of programming concepts.

> ⚠️ This project is **not representative of my current coding standards**.  
> It exists to demonstrate growth and long-term interest in software development.

---

## 🧠 Project Overview

The program allows users to:
- Create files dynamically
- Store file references using CSV
- Write and read binary data using `pickle`
- View existing files
- Delete files via a command-line interface

It uses a simple text-based menu system and demonstrates early exposure to:
- File I/O
- Binary serialization
- Modular programming with functions
- Basic data persistence

---

## 🛠️ Technologies Used

- Python
- `os`
- `csv`
- `pickle`

---

## ▶️ How It Works

When run, the program displays a menu:
- 1: Create File
- 2: Delete File
- 3: Display Files
- 4: Use File
- 5: Close


Each option performs file operations on locally stored `.dat` files, with references tracked in a CSV file.

---

## ⚠️ Important Notes

- The use of `pickle` is **not recommended** for modern applications due to security risks.
- The code lacks modern best practices such as:
  - Context managers (`with open`)
  - Input validation
  - Separation of concerns
  - Error handling
- These limitations are intentional to preserve the original learning artifact.


## 📜 License

This repository is provided for **portfolio and educational viewing only**.  
Please do **not copy, modify, or redistribute** any part of the code without permission.

