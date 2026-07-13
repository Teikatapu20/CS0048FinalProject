# CS0048FinalProject

# 🛠️ Carpentry Power Tool Rental System

The **Carpentry Power Tool Rental System** is a console-based application developed in **Python** that helps rental businesses efficiently manage their inventory of carpentry power tools. Instead of manually recording rentals, returns, and inventory updates, the system provides a centralized solution for managing rental transactions and tool availability.

The application allows users to add, edit, delete, view, rent, and return power tools while automatically storing all records using **JSON file handling**. This ensures that inventory data is retained even after the program is closed.

---

# 🎯 Purpose

The **Carpentry Power Tool Rental System** aims to simplify the management of carpentry tool rentals by providing a reliable and user-friendly application that allows rental businesses to efficiently monitor tool inventory, process rental transactions, and maintain accurate records using file handling.

---

## 🔨 Power Tool Details

Each tool record contains the following information:

- 🆔 Tool ID
- 🔧 Tool Name
- 📂 Tool Category
- ✅ Tool Condition
- 📦 Available Quantity
- 💲 Rental Price per Day

---

## 🚀 Setup Instructions

### 📋 Prerequisites

- Python **3.10** or higher
- Visual Studio Code, PyCharm, or IDLE
- Basic knowledge of running Python programs

---

### 1️⃣ Clone or Download the Repository

Download the project or clone it using Git.

```bash
git clone https://github.com/yourusername/carpentry-power-tool-rental-system.git
```

or download the ZIP file and extract it.

---

### 2️⃣ Open the Project

Open the project folder using your preferred Python IDE.

Example:

```
Carpentry-Power-Tool-Rental-System/
```

---

### 3️⃣ Run the Program

Open the terminal inside the project folder and run:

```bash
python main.py
```

---

### 4️⃣ Data Storage

The program automatically creates and updates:

```
carpentry_tools.json
```

This file stores all inventory records and rental updates.

---

# 📁 Folder Structure

```
Carpentry-Power-Tool-Rental-System/
│
├── main.py                   # Main program
├── carpentry_tools.json      # Tool inventory database
└── README.md                 # Project documentation
```

---

# ⚙️ System Functions

The application provides the following functions:

| Function | Description |
|----------|-------------|
| ➕ Add Tool | Add a new power tool to the inventory |
| ✏️ Edit Tool | Modify existing tool information |
| ❌ Delete Tool | Remove a tool from the inventory |
| 🔍 View Tool | Display details of a specific tool |
| 📋 View All Tools | Display every available tool |
| 🛒 Rent Tool | Rent an available power tool |
| 🔄 Return Tool | Return a rented power tool |
| 🚪 Exit | Close the application |

---

# ✨ Features

### 👨‍🔧 Inventory Management

- ➕ Add new carpentry power tools
- ✏️ Edit existing tool records
- ❌ Delete tool records
- 📋 View complete inventory
- 🔍 Search tools by Tool ID

### 🛒 Rental Management

- Rent available power tools
- Return rented tools
- Automatically update tool quantity
- Calculate rental cost based on rental days

### 💾 File Handling

- Save records using JSON
- Automatically load saved inventory
- Preserve data after closing the application

---

# 📚 Python Concepts Applied

This project demonstrates the application of the following Python topics:

- 📝 Variables and Data Types
- ⌨️ Input and Output
- 🔀 Conditional Statements
- 🔁 Loops
- 🧩 Functions
- 📋 Lists
- 📖 Dictionaries
- 💾 File Handling (JSON)
- ⚠️ Exception Handling

---

# 🛠️ Built With

- 🐍 Python 3
- 📄 JSON File Handling
- 💻 Visual Studio Code / PyCharm / IDLE

---

# 🎯 Project Goal

To develop a simple yet effective **Carpentry Power Tool Rental System** that enables users to manage carpentry power tool inventory, perform rental and return transactions, and store records using file handling while applying the Python programming concepts learned in Modules 1–6.

---

# 📖 Sample Menu

```
===============================
 CARPENTRY POWER TOOL RENTAL
===============================

1. Add Tool
2. Edit Tool
3. Delete Tool
4. View Tool
5. View All Tools
6. Rent Tool
7. Return Tool
8. Exit

Enter your choice:
```

---

# 📈 Future Improvements

Possible enhancements include:

- 🔐 User login system
- 👨‍💼 Administrator and Customer accounts
- 📅 Rental due dates
- 💵 Late return penalties
- 🧾 Receipt generation
- 📊 Rental reports
- 🔍 Search and filtering
- 🖥️ Graphical User Interface (Tkinter/PyQt)
- 🗄️ MySQL or SQLite database integration

---

# 👥 Developers

**Group Members**

- TEIKATAPU, BAIABE MCANTHONY
- MAMAOU, GLEN

---

# 📄 License

This project was developed for **educational purposes** as a final Python programming project and may be modified or enhanced for academic use.

