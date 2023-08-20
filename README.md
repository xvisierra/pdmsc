# 📔 Personal Diary Management System

This C program implements a simple personal diary management system that allows users to add, view, edit and delete dated diary entries.

## 📸 Screenshots
!Main Menu
!Add Record
!View Record

## 🌟 Features
- User-friendly text menu for navigation
- Add new records with time, name, place, duration and notes
- View all records for a given date or search by time
- Edit existing records by modifying time, name, place, duration or notes
- Delete all records for a date or selective record based on time
- Avoid duplicate entries for the same time
- Structured data storage in binary file for each date

## 🔍 Code Overview
- `main()` displays menu and calls appropriate functions based on user choice
- `addrecord()` allows adding new records with input validation
- `viewrecord()` displays all or selected records for a given date
- `editrecord()` searches record by date and time, allows editing and updates file
- `deleterecord()` deletes all records of a date or selective record
- `struct record` defines data structure for each diary entry
- File handling functions like `fopen()`, `fwrite()`, `fread()` are used
- Modular functions for each feature, using file pointers
- Input validation for dates, menu choices, avoid duplicates

## 💻 Usage
1. Compile with `gcc diary.c`
2. Run `./a.out` to display menu
3. Follow prompts to add, view, edit or delete records

Records are stored in binary files named with date.

This simple program demonstrates core concepts like structures, file handling, modular design and input validation in C. Enjoy! 😊
