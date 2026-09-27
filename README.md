# 📱 Mobile Shop Management System

A simple **Mobile Shop Management System** built using **Python**.  
This project allows users to manage mobile phone records through a simple command-line menu.

The project is designed to demonstrate basic Python programming concepts such as **functions, lists, loops, conditional statements, input handling, and CRUD operations**.

---

## 🚀 Features

The application provides the following options:

- ➕ **Add Mobile** – Add a new mobile phone record.
- 📋 **Display All Mobiles** – View all available mobile records.
- 🔍 **Search Mobile** – Search for a mobile using its ID.
- ✏️ **Update Mobile** – Update the details of an existing mobile.
- 🗑️ **Delete Mobile** – Delete a mobile record after confirmation.
- 🚪 **Exit** – Close the application.

The dashboard displays these options through a simple menu.

---

## 🛠️ Technologies Used

- **Python**
- Lists
- Functions
- Loops
- Conditional Statements
- `match-case`
- User Input
- Basic CRUD Operations

---

## 📂 Project Structure

```text
Mobile-Shop-Management/
│
├── app.py
├── config.py
├── Dashboard.py
└── README.md
```

### `app.py`

This is the main file used to start the application. It calls the `dashboard()` function when the program is executed.

### `config.py`

This file contains the main mobile management functions:

- `add_mobile()`
- `display_mobiles()`
- `search_mobile()`
- `update_mobile()`
- `delete_mobile()`

Mobile records are stored in a Python list.

### `Dashboard.py`

This file provides the main menu and connects the different functions with the user's selected option.

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Mobile-Shop-Management.git
```

### 2. Open the Project Folder

```bash
cd Mobile-Shop-Management
```

### 3. Run the Application

```bash
python app.py
```

---

## 💻 Application Menu

When the application starts, you will see:

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

---

## 📱 Mobile Information

Each mobile record contains:

| Field | Description |
|---|---|
| ID | Unique mobile ID |
| Brand | Mobile brand |
| Model | Mobile model |
| Price | Mobile price |
| Quantity | Available quantity |

For example:

```text
ID       Brand          Model              Price          Quantity
1        Samsung        Galaxy A55         35000.00       10
2        Apple          iPhone 15          65000.00       5
```

---

## 🔄 CRUD Operations

This project demonstrates the basic **CRUD** concept:

| Operation | Function |
|---|---|
| Create | `add_mobile()` |
| Read | `display_mobiles()` / `search_mobile()` |
| Update | `update_mobile()` |
| Delete | `delete_mobile()` |

The `add_mobile()` function creates a mobile record and adds it to the `mobiles` list. It also checks whether the entered mobile ID already exists.

---

## 🎯 Learning Objectives

This project helped me practice:

- Writing Python functions
- Working with lists
- Using `for` and `while` loops
- Using `if-else` conditions
- Taking input from users
- Searching data in a list
- Updating list elements
- Removing data from a list
- Using `match-case`
- Creating a simple menu-driven application
- Understanding basic CRUD operations

---

## 🔮 Future Improvements

Some possible improvements for this project are:

- Add a database such as **MySQL**
- Add login and authentication
- Add stock management
- Add billing functionality
- Add sales records
- Add exception handling for invalid inputs
- Add a graphical user interface
- Store data permanently instead of using an in-memory list

---

## 👩‍💻 Author

**Ipsita Saha**

Computer Science Graduate  
Interested in **Python, Software Development, AI/ML and Data Analytics**.

---

## ⭐ Project Status

**Completed – Basic Version**

This project was created for learning and practicing Python programming and CRUD concepts.
