# 🏦 Banking Management System

A desktop-based Banking Management System developed using **Java**, **Swing**, **JDBC**, and **MySQL**. The application simulates core banking operations through an interactive graphical user interface, allowing users to securely manage their accounts and perform various banking transactions.

---

## 📌 Features

- 🔐 User Registration & Login
- 💳 Account Creation
- 💰 Cash Deposit
- 💸 Cash Withdrawal
- ⚡ Fast Cash Withdrawal
- 📊 Balance Enquiry
- 📄 Mini Statement Generation
- 🔑 PIN Change
- 🗄️ MySQL Database Integration
- 🖥️ Interactive Java Swing GUI

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| Java | Core Application Development |
| Java Swing | Desktop GUI |
| JDBC | Database Connectivity |
| MySQL | Database Management |
| SQL | Data Storage & Retrieval |

---

## 📂 Project Structure

```
Bank-Management-System
│
├── Login.java
├── Signup.java
├── Signup2.java
├── Signup3.java
├── Deposit.java
├── Withdrawl.java
├── FastCash.java
├── BalanceEnquiry.java
├── MiniStatement.java
├── Pin.java
├── Main_Class.java
├── Connn.java
├── icons/
└── database/
```

---

## ⚙️ Functional Modules

### 🔹 Authentication
- Secure login using Card Number and PIN.
- New user registration through a multi-step signup process.

### 🔹 Banking Transactions
- Deposit money into an account.
- Withdraw available balance.
- Fast Cash for predefined withdrawal amounts.
- Balance enquiry with real-time calculation.
- Generate mini statement showing transaction history.

### 🔹 Account Management
- Change ATM PIN.
- View account details.
- Maintain transaction records in MySQL.

---

## 🗄️ Database

The project uses **MySQL** as the backend database.

Tables include:

- Login
- Signup
- Signuptwo
- Signupthree
- Bank

The application performs CRUD operations using **JDBC**.

---

## 🚀 Getting Started

### Prerequisites

- Java JDK 8 or above
- MySQL Server
- MySQL Workbench (Optional)
- Eclipse / IntelliJ IDEA / VS Code

---

### Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/Bank-Management-System.git
```

2. Open the project in your IDE.

3. Create a MySQL database.

```sql
CREATE DATABASE bankSystem;
```

4. Import the SQL file into MySQL.

5. Update the database credentials inside:

```java
Connn.java
```

```java
DriverManager.getConnection(
    "jdbc:mysql://localhost:3306/bankSystem",
    "your_username",
    "your_password"
);
```

6. Run

```
Login.java
```

---

## 📸 Application Workflow

```
Login
      │
      ▼
 Main Dashboard
      │
 ┌────┼──────────────┐
 │    │              │
 ▼    ▼              ▼
Deposit Withdraw   Fast Cash
 │      │              │
 └──────┼──────────────┘
        ▼
 Balance Enquiry
        │
        ▼
 Mini Statement
        │
        ▼
    PIN Change
```

---

## 🎯 Java Concepts Demonstrated

- Object-Oriented Programming (OOP)
- Classes & Objects
- Constructors
- Event Handling
- Exception Handling
- JDBC Connectivity
- SQL CRUD Operations
- Java Swing GUI Development
- MySQL Database Integration

---

## 📈 Future Enhancements

- PreparedStatement for secure SQL queries
- Password Encryption
- Transaction Logging
- Funds Transfer
- Interest Calculation
- Account Lock after Multiple Failed Login Attempts
- Spring Boot REST API Version
- Role-Based Access Control
- Email/SMS Notifications

---

## 👨‍💻 Author

**Ashish Mohanty**

- GitHub: https://github.com/AshishMohanty04
- LinkedIn: https://linkedin.com/in/AshishMohanty

---

