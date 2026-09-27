# Mobile Shop Management – Python CRUD Project

A simple **console-based Mobile Shop Management System** developed in Python using CRUD (Create, Read, Update, Delete) operations.

This project is designed to practice Python fundamentals such as functions, lists, loops, conditional statements, user input, and menu-driven programming.

## 📌 Project Overview

The application allows a shop user to manage mobile phone records through a simple command-line menu.

Each mobile record contains:

- Mobile ID
- Brand
- Model
- Price
- Quantity

The records are stored in a Python list while the program is running.

## ✨ Features

### 1. Add Mobile
Add a new mobile phone record by entering:

- Mobile ID
- Brand
- Model
- Price
- Quantity

The program also checks whether the Mobile ID already exists before adding the record.

### 2. Display All Mobiles
Displays all available mobile records in a formatted table containing the ID, brand, model, price, and quantity.

### 3. Search Mobile
Search for a mobile using its unique Mobile ID and display its complete details.

### 4. Update Mobile
Update the brand, model, price, and quantity of an existing mobile using its Mobile ID.

### 5. Delete Mobile
Delete an existing mobile record after confirming the deletion.

### 6. Exit
Exit the Mobile Shop Management System.

## 🛠️ Technologies Used

- **Python 3**
- Lists
- Functions
- Loops
- Conditional statements
- Pattern matching (`match-case`)
- User input
- Basic data formatting

No external Python libraries are required.

## 📂 Project Structure

```text
crud/
│
├── codes/
│   └── test.py
│
├── Scripts/
│   └── Python virtual environment files
│
├── Lib/
│   └── Python environment files
│
├── .gitignore
├── pyvenv.cfg
└── README.md
```

> The main application code is located in `codes/test.py`.

## 🚀 How to Run

### Step 1: Install Python

Make sure Python 3 is installed on your computer.

Check the installed version using:

```bash
python --version
```

or:

```bash
python3 --version
```

### Step 2: Open the Project

Open the project folder in your terminal or code editor.

Navigate to the folder containing `test.py`:

```bash
cd crud/codes
```

### Step 3: Run the Program

Run:

```bash
python test.py
```

The Mobile Shop Management menu will appear in the terminal.

## 🖥️ Main Menu

When the program starts, it displays:

```text
=============================================
 MOBILE SHOP MANAGEMENT
=============================================
1. Add Mobile
2. Display All Mobiles
3. Search Mobile
4. Update Mobile
5. Delete Mobile
6. Exit
=============================================
Enter your choice:
```

Choose an option by entering its corresponding number.

## 📊 Example Record

A mobile record is stored internally in the following format:

```python
[101, "Samsung", "Galaxy S24", 69999.00, 5]
```

The values represent:

```text
Mobile ID → 101
Brand     → Samsung
Model     → Galaxy S24
Price     → 69999.00
Quantity  → 5
```

## 🔄 CRUD Operations

CRUD stands for:

| Operation | Function | Purpose |
|---|---|---|
| Create | `add_mobile()` | Add a new mobile record |
| Read | `display_mobiles()` / `search_mobile()` | View or search records |
| Update | `update_mobile()` | Modify an existing record |
| Delete | `delete_mobile()` | Remove a record |

## 🧩 Functions Used

The application is divided into separate functions to keep the program organized:

```text
add_mobile()
display_mobiles()
search_mobile()
update_mobile()
delete_mobile()
dashboard()
main()
```

### `add_mobile()`
Creates and stores a new mobile record.

### `display_mobiles()`
Displays all stored mobile records in a formatted table.

### `search_mobile()`
Searches for a mobile using its ID.

### `update_mobile()`
Updates the details of an existing mobile.

### `delete_mobile()`
Removes a mobile record after confirmation.

### `dashboard()`
Displays the main menu and controls the program flow.

### `main()`
Starts the dashboard.

## 🎯 Learning Objectives

This project helps practice:

- Creating and calling Python functions
- Working with lists
- Storing multiple records
- Using `for` loops
- Using `if-else` conditions
- Taking input from users
- Converting input into `int` and `float`
- Searching data
- Updating list elements
- Removing elements from a list
- Building menu-driven applications
- Implementing basic CRUD operations
- Using Python `match-case`

## ⚠️ Current Limitations

The current version stores all mobile records in a Python list.

Therefore:

- Data is stored only while the program is running.
- Closing the program removes all records.
- There is no database connection.
- There is no graphical user interface.
- Input validation for incorrect data types is limited.

## 🔮 Future Improvements

The project can be improved by adding:

- MySQL or SQLite database integration
- Permanent data storage
- Graphical user interface using Tkinter
- Web interface using Flask or Django
- Login and authentication
- Better input validation
- Stock alerts for low quantities
- Sorting and filtering options
- Sales and billing functionality
- Customer management
- Mobile category management
- Reports and sales dashboards

## 📚 Project Purpose

This project was created as a practical Python programming project to understand how CRUD operations work in a simple management system.

It provides a foundation that can later be expanded into a complete **Mobile Shop Inventory and Management System**.

## 👨‍💻 Author

**Sanju Jana**

A Python CRUD project created for learning, practice, and understanding basic management-system development.
