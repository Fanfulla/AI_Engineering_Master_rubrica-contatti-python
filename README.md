# 📱 Python Contact Book

> **First complete Python project** - Contact management system developed as final project for the AI Engineering Master's program.

---

## 📖 Description

This is my **first complete Python project**, created as the final exercise for the Python programming course in the AI Engineering Master's program with [Profession AI](https://profession.ai/).

The project implements a terminal-based contact management system with full CRUD functionality (Create, Read, Update, Delete) and JSON data persistence.

**Important note:** This project represents my learning journey. It's not perfect, but I'm proud of the result because it allowed me to consolidate all the fundamental concepts of object-oriented programming in Python! 🎯

---

## ✨ Implemented Features

- ➕ **Add contacts** - Name, surname, phone number (required) + email and notes (optional)
- 📋 **Complete view** - List all saved contacts
- 🔍 **Smart search** - Search contacts by name, surname, or phone number
- ✏️ **Edit contacts** - Update any field of an existing contact
- 🗑️ **Delete with confirmation** - Safely remove contacts from the address book
- 💾 **Automatic persistence** - Save to JSON file after every operation

---

## 🛠️ Technologies and Applied Concepts

- **Python 3** - Programming language
- **Object-Oriented Programming (OOP)**
  - Classes: `Contatto` (Contact) and `Rubrica` (Address Book)
  - Special methods: `__init__`, `__str__`
  - Encapsulation and modularity
- **JSON file management** - For data persistence
- **Error handling** - Try/except for user input validation
- **User Experience** - Interactive menu, confirmation messages, user feedback
- **Google Colab** - Development environment

---

## 📂 Code Structure

The project is organized into two main classes:

### `Contatto` Class (Contact)
Represents a single contact with its attributes (name, surname, phone, email, notes) and methods for management and display.

### `Rubrica` Class (Address Book)
Manages the collection of contacts and implements all operations:
- `aggiungi_contatto()` - Add new contacts
- `visualizza_tutti()` - Display all contacts
- `visualizza_contatto()` - Search contacts
- `modifica_contatto()` - Modify contact data
- `elimina_contatto()` - Delete contacts
- `salva_file()` - Save to JSON
- `carica_rubrica()` - Auto-load on startup

### Main Menu
Interactive user interface with error handling and input validation.

---

## 🚀 How to Use

### Option 1: Google Colab (recommended)
Click the "Open in Colab" badge above and run all notebook cells.

### Option 2: Local
1. Download the `.ipynb` file
2. Open in Jupyter Notebook or Google Colab
3. Run all cells
4. Interact with the menu to manage your contacts!

---

## 🎓 Academic Context

**Program:** AI Engineering Master's  
**Institution:** Profession AI  
**Project:** Final Python Exercise - Object-Oriented Programming  
**Completion Date:** December 2025  
**Status:** ✅ Passed

---


## 👨‍💻 Author

**Salvatore (SA)**  
GitHub: [@Fanfulla](https://github.com/Fanfulla)

*AI Engineering Master's Student - Profession AI*

---

## 📄 License

MIT License - Feel free to use this code for learning!

⭐ **If this project helped you learn Python, leave a star!**
