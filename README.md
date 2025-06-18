
# 📇 Contact Management System

A **simple Contact Management System** built using Python's **Tkinter** library for the GUI and **SQLite** for data storage. This desktop application allows users to seamlessly **add, update, delete**, and **view contact information**.

---

## ✨ Features

- ➕ **Add** new contacts with:
  - First Name, Middle Name, Last Name
  - Gender, Age
  - Home Address, Phone Number  
- ♻️ **Update** existing contact details  
- ❌ **Delete** contacts from the database  
- 📋 **View** all contacts in a structured, scrollable table format  

---

## 📦 Requirements

- Python **3.x**  
- Tkinter (usually comes **pre-installed** with Python)  
- SQLite (part of the Python **standard library**)

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/contact-management-system.git
cd contact-management-system
python contact_manager.py
```


## 🧠 Functionality Overview

### 🗃️ Database Functionality

- The `Database()` function initializes the SQLite database and **creates a table** to store contact information if it doesn't exist.

### 🎨 GUI Components

- Built using **Tkinter**, the GUI consists of:
  - Frames and Labels for layout
  - Entry widgets for user input
  - Buttons for CRUD operations

### 🛠️ CRUD Operations

- `submit()`: **Inserts** a new contact into the database  
- `update()`: **Updates** information of a selected contact  
- `delete()`: **Deletes** a selected contact from the database  
- `reset()`: **Clears** all input fields for fresh entry  

---

## 🧑‍💻 Author

**Amritanshu**  

