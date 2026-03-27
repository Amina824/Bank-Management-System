# 🏦 Bank Management System (C++)

> A structured and console-based banking system built using C++ and Object-Oriented Programming principles, simulating real-world banking operations.

---

## 📌 Overview

This project is a **console-based Bank Management System** developed in C++. It demonstrates the practical implementation of **Object-Oriented Programming (OOP)** concepts along with **file handling for persistent data storage**.

The system is designed to simulate real-world banking operations and supports multiple user roles with different access levels, ensuring modularity and role-based functionality.

---

## 👥 User Roles

### 🔐 Admin

* Full control over the system
* Manage employees, accounts, services, transactions, and bank cards

### 👨‍💼 Employee

* Manage account holders and accounts
* Handle transactions and bank cards

### 👤 Account Holder

* View account details
* View transaction history

---

## 🚀 Features

* Add, update, search, and delete records
* Role-based access control system
* Link accounts with:

  * Transactions
  * Bank Cards
  * Cheque Books
* Persistent data storage using text files
* Menu-driven console interface

---

## 🏦 Functional Modules

* 👨‍💼 Employee Management
* 👤 Account Holder Management
* 💳 Bank Card Management
* 💰 Account Management
* 💸 Transaction Management
* 📄 Cheque Book Management
* 🛠️ Services Management

---

## 🧠 Concepts Used

### Object-Oriented Programming (OOP)

* Classes & Objects
* Inheritance
* Encapsulation
* Polymorphism

### Other Concepts

* File Handling (Data Persistence)
* Dynamic Memory Handling
* STL (Vectors)
* Menu-driven Programming

---

## 📂 File Handling

The system stores and retrieves data using text files:

* `Admin.txt`
* `Employee.txt`
* `AccountHolder.txt`
* `Account.txt`
* `Transaction.txt`
* `BankCard.txt`
* `Chequebook.txt`
* `Services.txt`

All data is automatically loaded at program startup and saved upon exit.

---

## 📁 Project Structure

```
Bank-Management-System/
│
├── bank_management.cpp
├── README.md
├── Admin.txt
├── Employee.txt
├── AccountHolder.txt
├── Account.txt
├── Transaction.txt
├── BankCard.txt
├── Chequebook.txt
└── Services.txt
```

---

## ⚙️ Requirements

* C++ Compiler (G++ recommended)
* Any OS (Windows / Linux / macOS)
* Basic knowledge of terminal/command prompt

---

## 🛠️ How to Run

### Step 1: Compile

```bash
g++ bank_management.cpp -o bank
```

### Step 2: Run

```bash
./bank
```

*(On Windows, run `bank.exe`)*

---

## 📸 Sample Functionalities

* Create and manage employees, accounts, and users
* Perform and track transactions
* Assign bank cards and cheque books to accounts
* Search and filter records
* Navigate system via role-based menus

---

## ⚠️ Notes

* This is a **console-based academic project**
* No graphical interface (GUI) is included
* Data is stored in plain text files (not encrypted)
* Some validations and security features are basic

---

## 🔮 Future Improvements

* Add graphical user interface (GUI)
* Integrate database (MySQL / SQLite)
* Implement secure authentication system
* Improve input validation and error handling
* Encrypt sensitive data (passwords, PINs)

---

## 👨‍💻 Author

* Amina Bibi
* Language: **C++**

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!
