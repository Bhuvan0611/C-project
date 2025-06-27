# 🛒 General Store Management System (C Language)

A **terminal-based store management system** built entirely in **C**, designed to simulate real-world inventory and customer management operations. This project handles new/existing customer shopping, inventory updates, and transaction tracking — all via a clean and interactive CLI.

---

## 🚀 Features

### 🧑‍💼 Customer Module
- ✅ **New Customer Registration** (with PIN authentication)
- 🔐 **Existing Customer Login**
- 🎯 **Shopping Cart System** with section-wise browsing
- 🏷️ **Discounts** applied for returning customers
- 💳 **Checkout with Transaction Logging**

### 🧾 Admin Module
- 📦 Add / Remove / Modify items in the inventory
- 📂 View full inventory list
- 📈 Display all past customer transactions

---

## 📁 File Structure

| File Name            | Description                                 |
|---------------------|---------------------------------------------|
| `main.c`             | Main source code (all logic integrated)     |
| `customers_data.txt` | Stores customer records with discounts      |
| `inventory_data.txt` | Inventory database (ID, name, price, stock)|
| `Records.txt`        | Transaction log with date-time entries      |
| `output/`            | (Optional) Folder for compiled executable   |

---

## 🔐 Customer Data Format (`customers_data.txt`)

<ID>,<Name>,<PhoneNumber>,<PIN>,<Discount>

📌 Example:

1,Vishnu,9876543210,1234,10.0

2,Meghana,8123456789,4321,0.0

## 📦 Inventory Format (`inventory_data.txt`)

<ID> <Name> <Price> <Quantity>

📌 Example:

DD_123 Almonds 760.00 20

DD_101 Milk 60.00 30

- Prefixes like `D`, `S`, `B`, etc., are used to categorize sections:
  - `D`: Dairy
  - `G/C`: Grains & Cooking
  - `S`: Snacks
  - `B`: Beverages
  - `O`: Others

---

🧠 Concepts Covered :-

📌 File Handling (Read/Write Text Files)

📌 Structs and Arrays

📌 Pointer Manipulation

📌 Conditional Logic and Loops

📌 String Parsing

📌 Console Cursor Movement (cursor(x, y) logic)

📌 Modular Code with Custom Functions

---

👨‍💻 Developed By :-

Venkata Bhuvan Kosuru

🏫 IIT Patna


## 🛠️ How to Run

### 💻 Compile
```bash
gcc main.c -o store
./store

💡 Make sure customers_data.txt and inventory_data.txt are in the same directory as your executable.

