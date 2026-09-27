# Mobile Store Inventory System – Python CRUD Application

A beginner-friendly **command-line Mobile Store Inventory System** built with Python. The project demonstrates the basic CRUD model: Create, Read, Update, and Delete.

The application is mainly intended to practice Python concepts including functions, lists, loops, conditions, user input, and menu-based program flow. fileciteturn1file0L3-L5

##  Project Description

This application provides a small inventory-management system for a mobile phone shop. Users can add, view, find, edit, and remove mobile phone records from a terminal-based menu.

Each record stores the following information:

- Mobile ID
- Brand
- Model
- Price
- Quantity

The records are maintained inside a Python list during program execution. fileciteturn1file0L7-L19

##  Available Operations

### 1. Add a Mobile

Users can enter the details of a new phone:

- Mobile ID
- Brand
- Model
- Price
- Quantity

Before saving the entry, the program checks whether the supplied Mobile ID is already present.

### 2. View Mobile Records

Shows all currently stored phones in a readable table containing their ID, brand, model, price, and available quantity.

### 3. Find a Mobile

A phone can be searched using its unique Mobile ID, after which its complete record is displayed.

### 4. Modify a Mobile

Existing information such as the brand, model, price, and quantity can be changed by entering the relevant Mobile ID.

### 5. Remove a Mobile

An existing record can be deleted after the user confirms the action.

### 6. Close the Application

The Exit option terminates the Mobile Store Management program.

These operations correspond to the CRUD functionality described in the original project. fileciteturn1file0L21-L47

##  Tools and Concepts

The project uses:

- **Python 3**
- Lists
- Functions
- `for` and `while` loops
- Conditional statements
- `match-case`
- User input
- Basic output formatting

No external Python packages are needed. fileciteturn1file0L49-L60

##  Project Layout

```text
mobile-store-crud/
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

The primary application file is `codes/test.py`. fileciteturn1file0L62-L81

##  Running the Application

### Step 1 – Verify Python

Make sure Python 3 is available on your computer.

Check the version with:

```bash
python --version
```

If required, you can also try:

```bash
python3 --version
```

### Step 2 – Open the Project

Open the project directory in a terminal or Python-compatible editor.

Move into the folder containing the application:

```bash
cd crud/codes
```

### Step 3 – Start the Program

Run:

```bash
python test.py
```

The management menu will then appear in the terminal. fileciteturn1file0L83-L119

##  Application Menu

When the application starts, the user is presented with options similar to:

```text
=============================================
 MOBILE STORE MANAGEMENT
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

Enter the number associated with the operation you want to perform. fileciteturn1file0L121-L139

##  Sample Mobile Record

A mobile phone can be represented internally as:

```python
[101, "Samsung", "Galaxy S24", 69999.00, 5]
```

Here, the values mean:

```text
Mobile ID → 101
Brand     → Samsung
Model     → Galaxy S24
Price     → 69999.00
Quantity  → 5
```

This follows the five fields used by the original application. fileciteturn1file0L141-L159

##  Understanding CRUD

CRUD is an abbreviation for four common data-management operations:

| CRUD Type | Function | Description |
|---|---|---|
| Create | `add_mobile()` | Inserts a new phone record |
| Read | `display_mobiles()` / `search_mobile()` | Displays or searches stored records |
| Update | `update_mobile()` | Changes an existing record |
| Delete | `delete_mobile()` | Removes a record |

The project implements these four operations through separate functions. fileciteturn1file0L159-L169

##  Main Functions

The application separates its tasks into functions:

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
Creates a new phone entry and stores it in the list.

### `display_mobiles()`
Shows the currently available mobile records.

### `search_mobile()`
Looks up a phone by its Mobile ID.

### `update_mobile()`
Changes information belonging to an existing phone.

### `delete_mobile()`
Removes a selected record after confirmation.

### `dashboard()`
Controls the menu and guides the user through the available operations.

### `main()`
Starts the application by calling the dashboard.

The original project uses these functions to divide the application into manageable sections. fileciteturn1file0L170-L203

##  Learning Outcomes

Working on this project provides practice with:

- Defining and calling functions
- Creating and managing lists
- Handling multiple records
- Using loops
- Applying `if-else` conditions
- Accepting user input
- Converting values to `int` and `float`
- Searching through stored data
- Editing list elements
- Removing list elements
- Creating menu-driven applications
- Applying CRUD concepts
- Using Python `match-case`

These learning areas are based on the objectives listed in the source README. fileciteturn1file0L205-L221

##  Known Limitations

The current version keeps all records in memory using a Python list.

As a result:

- Records are available only while the program is running.
- Closing the application clears the stored records.
- No database is connected.
- There is no graphical user interface.
- Validation for incorrect input types is limited.

These limitations are part of the current project design. fileciteturn1file0L223-L233

## 🔮 Future Development

The system could later be extended with:

- SQLite or MySQL support
- Permanent database storage
- A Tkinter desktop interface
- A Flask or Django web version
- User login and authentication
- Stronger input validation
- Low-stock notifications
- Sorting and filtering
- Billing and sales features
- Customer records
- Mobile categories
- Sales and inventory reports

These improvements would turn the basic CRUD application into a more complete shop-management solution. fileciteturn1file0L235-L250

##  Project Goal

The purpose of this project is to provide practical experience with Python CRUD programming through a small mobile-store example.

It can serve as a starting point for developing a larger **Mobile Inventory and Shop Management System**. fileciteturn1file0L252-L257

##  Author

**Farhana Sultana**

A Python practice project focused on CRUD operations, inventory management, and fundamental programming concepts.
