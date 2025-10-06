
# Bank Management System

A simple **Java-based banking application** using **Swing** for the GUI and **JDBC** for database connectivity.

## 🏦 Overview

This project lets users manage their bank accounts with features like:

* Account creation and login
* Deposit and withdrawal
* Fast cash option
* Balance enquiry
* Mini statement
* PIN change

## ⚙️ Tech Stack

* **Frontend:** Java Swing
* **Backend:** Java
* **Database:** MySQL (via JDBC)

## 📁 Project Structure

```
src/bms/
├── Conn.java            # Database connection file
├── Login.java           # User login
├── SignUpOne/Two/Three  # Registration steps
├── Deposit.java         # Deposit money
├── Withdrawal.java      # Withdraw money
├── FastCash.java        # Quick withdrawal
├── BalanceEnquiry.java  # Check balance
├── MiniStatement.java   # View transactions
└── PinChange.java       # Change account PIN
```

## 🧰 Setup

1. **Clone the repo**

   ```bash
   git clone https://github.com/czarzival/bank_management_sys.git
   ```
2. **Create a MySQL database** (e.g. `bank_db`)
3. **Update `Conn.java`** with your DB credentials:

   ```java
   String url = "jdbc:mysql://localhost:3306/bank_db";
   String user = "root";
   String pass = "your_password";
   ```
4. **Run the project** from your IDE or using:

   ```bash
   javac src/bms/*.java
   java src/bms/Login
   ```

## 🧾 Features

* Create and manage accounts
* Deposit / withdraw money
* Quick “fast cash” option
* Check balance and view mini statements
* Secure PIN change system
