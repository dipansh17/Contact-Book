# Contact Book Program

This is a simple Java console-based application to manage contacts. You can add, view, edit, and delete contacts using this program.

## Features

- **Add a contact**: Add a new contact with name, phone number, and email.
- **View all contacts**: View the list of all saved contacts.
- **Edit a contact**: Modify an existing contact's details.
- **Delete a contact**: Remove a contact from the list.

## How It Works

- The contacts are stored in a list (`ArrayList`), and each contact contains a name, phone number, and email.
- The program offers a menu-driven interface, allowing you to interact with it by choosing options (like adding, viewing, editing, or deleting a contact).

## Getting Started

### Prerequisites

You need to have Java installed on your machine to run this program. You can download it [here](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).

### Running the Program

1. Clone or download this repository to your local machine.
2. Compile and run the `ContactBookProgram.java` file using a terminal or your favorite Java IDE.
#### Menu Options:
Add a contact: Input name, phone number, and email to create a new contact.
View contacts: Displays a list of all contacts with their index, name, phone number, and email.
Edit a contact: Enter the index of the contact you want to modify, followed by the new details.
Delete a contact: Enter the index of the contact you wish to delete.
###### Example:
Exit the program: Choose 0 to close the application.
----- Contact Book -----
1. Add a contact
2. View contacts
3. Edit a contact
4. Delete a contact
0. Exit
Enter your choice: 1

Enter the name: John Doe
Enter the phone number: 123-456-7890
Enter the email: johndoe@example.com
Contact added successfully.

Enter your choice: 2
Contact List:
1. Name: John Doe, Phone: 123-456-7890, Email: johndoe@example.com

#### Compile using terminal:
```bash
javac ContactBookProgram.java


 
