# Addressbook
📘 Address Book Management System (C)

A command-line based Address Book application written in C that allows users to store, manage, and persist contact information using file handling.

📌 Overview

This project implements a simple yet functional address book system where users can perform operations such as adding, searching, editing, deleting, and viewing contacts. Each contact consists of a name, mobile number, and email ID. The application ensures data validation and prevents duplicate entries, while also maintaining persistence by saving data to a file.

🚀 Features
Add new contacts with validation
Search contacts by:
Name (handles duplicate names)
Mobile number
Email ID
Edit existing contact details
Delete contacts with confirmation
Display all contacts in a formatted table
Save and load contacts using file handling
Duplicate detection for mobile number and email ID
🧠 Concepts Used
Structures and arrays
File handling in C
String manipulation functions
Input validation using ctype.h
Modular programming
⚙️ How It Works
Contacts are stored in a structure and maintained in an array (maximum 100 contacts).
On program start, existing contacts are loaded from a file.
Users interact through a menu-driven interface.
All operations update the in-memory data, which can be saved to a file.
📂 File Structure
.
├── main.c
├── contact.h
├── contact.c
├── contacts.txt
💾 Data Storage Format

Contacts are stored in a file (contacts.txt) as:

#<number_of_contacts>
Name,Mobile,Email
Name,Mobile,Email
🛠️ Compilation & Execution

Compile the program:

gcc main.c contact.c -o addressbook

Run the program:

./addressbook
⚠️ Limitations
Maximum of 100 contacts (fixed-size array)
No dynamic memory allocation
Basic email validation (not fully standard-compliant)
Case-sensitive search
No graphical user interface
🔧 Future Improvements
Implement dynamic memory allocation
Add case-insensitive and partial search
Improve email validation logic
Add sorting functionality
Use advanced file formats like CSV or JSON
Build a graphical interface
📖 Sample Usage
Enter the Name: Aarav Menon
Enter the Mobile number: 9098760032
Enter the Mail_ID: aaravmenon24@gmail.com

Contact Added Successfully
Total Contacts: 1
👤 Author
Chaithra P
