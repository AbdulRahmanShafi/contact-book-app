# Contact Book App

A simple command-line contact book built with Python. It lets you create, view, update, delete, search, and count contacts from an interactive menu.

## Features

- Create new contacts with name, age, email, and mobile number.
- View saved contact details by name.
- Update an existing contact.
- Delete a contact.
- Search contacts by partial name match.
- Display the total number of saved contacts.

## Requirements

- Python 3.10 or later

## How To Run

From the project folder, run:

```bash
python contact.py
```

If your system uses multiple Python versions, you may need to use `python3` instead.

## Usage

After starting the program, choose an option from the menu:

1. Create Contact
2. View Contacts
3. Update Contact
4. Delete Contact
5. Search Contact
6. Count Contacts
7. Exit

Follow the prompts to enter the requested information.

## Project Structure

```text
Contact Book App/
├── contact.py
└── README.md
```

## Notes

- Contacts are stored in memory only, so all data is lost when the program exits.
- Search is case-insensitive and matches partial names.
- Age is stored as a number.

## Example

```text
Contact Book App
1: Create Contact
2: View Contacts
3: Update Contact
4: Delete Contact
5: Search Contact
6: Count Contacts
7: Exit
```
