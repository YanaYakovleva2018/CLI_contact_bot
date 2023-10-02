# CLI_contact_bot

This Python code is an implementation of an address book that allows you to store and manage contacts' information, such as names, phone numbers, and birthdays. It provides a command-line interface for interacting with the address book.

## Features

- Add new contacts with names, phone numbers, and optional birthdays.
- Change, delete, and view phone numbers associated with a contact.
- Calculate and display the days until a contact's next birthday.
- Search for contacts based on specific keywords
- Save and load address book data to/from files.

## Usage

To use the address book, follow these steps:
1. Clone or download the repository to your local machine.
2. Run the helper_console_bot_v3.py script in your terminal or command prompt:
```bash
python helper_console_bot_v3
```
3. You will be prompted to enter commands. Use the predefined commands
4. To exit the address book, use the `exit`, `bye`, or other exit-related commands.
   
## Commands

The address book supports the following commands:

- **add** or **new**: Add a new contact to the address book. Provide the contact's name, phone number, and an optional birthday in the format "DD.MM.YYYY" if desired.
  
  Example:
```bash
add John Doe 1234567890 01.01.1990
```
- **change**: Change an existing phone number for a contact. Provide the contact's name, the current phone number, and the new phone number.

Example:
```bash
change John Doe 1234567890 9876543210
```
- **phone** or **number**: Display the phone numbers associated with a contact. Provide the contact's name.
- **show** or **show all**: Display all contacts in the address book.
- **del** or **delete**: Delete a phone number from a contact's record. Provide the contact's name and the phone number to delete.
- **days** or **birthday**: Calculate and display the days until a contact's next birthday. Provide the contact's name.
- **search** or **find**: Search for contacts based on specific keywords. Provide one or more keywords to search for in contact records.exit, bye, close, good bye: Exit the address book and save changes.
