# phonebook

A simple python CLI app for managing phonebooks for various users.

- Seperate contact list maintained for each user
- Powered by a integer input based command line menu interface.  
- The persistance is handled by an sqlite3 database, material.db.
- User credentials are encrypted.
- High fault tolerance and scalability.

## Features:
#### User Management:
- Add User
- Delete User
- Select user

#### Contact Management:
- Show All Contacts
- Add Contact (name and number mandatory, email optional)
- Delete Contact (Select on basis of name, case insensitive)
- Search Contact (Select on basis of name, case insensitive)
- Modify Contact (Select on basis of name, case insensitive)
- Import CSV (In format: name, contact, email)
- Export CSV (In format: name, contact, email)

---

## Note: Do not delete the database, or you'll lose all your data (duh).

## Special Cases:
- Hit **Ctrl + C** on Windows/Linux to quit the application at any time
- Hit **Ctrl + Z and enter** on Windows (currently not supported on Linux) to go back to the previous menu.
Helpful if you have selected the wrong option.

---

### Authored by (in alphabetical order):
- Anuj Kumar Singh
- Sanskar Agrawal
- Saumy Pandey
- Som Shiv Gupta
- Anshuman Yadav

[Report a new bug/issue](https://github.com/AritificialPhysics/phonebook/issues/new)
