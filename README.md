# StudyFinder & Banking System - C++ CLI Application

## Overview

This project is a **C++ Command-Line Interface (CLI) application** that integrates two core subsystems:

- **Banking System:** Enables users to create bank accounts, log in, deposit, withdraw, transfer funds, and manage PIN codes.
- **StudyFinder System:** Helps students search and apply for university programs based on their qualifications, including GPA and English proficiency.

The application utilizes **object-oriented programming (OOP)** principles and incorporates structured data handling with vectors and classes, making it a strong example of **C++ software development** for practical use cases.

---

## Features

### **General Features**

- Intuitive CLI with a user-friendly menu-driven interface.
- **ANSI Colorized Output** for improved readability.
- Robust **input validation** to prevent errors and invalid entries.

### **Banking System**

✅ **User Authentication:** Secure login and account registration.

✅ **Financial Transactions:**
- Deposit and withdraw funds (with validation limits).
- Transfer funds between accounts.

✅ **Account Management:**
- View account details.
- Change PIN code securely.

✅ **Transaction Receipt:** Displays confirmation messages for financial actions.

### **StudyFinder System**

✅ **User Profile Management:**
- Create and update student profiles (GPA, English level, etc.).

✅ **University Search & Sorting:**
- Filter universities based on **tuition fees** and **acceptance chances**.

✅ **Qualification Checking:**
- Automatically assesses eligibility for a selected university program.

✅ **Application Process:**
- Guides users to pay application fees through the Banking System.

---

## System Architecture

### **Class Overview**

| Class Name           | Description                                                   |
| -------------------- | ------------------------------------------------------------- |
| `person`             | Base class representing a user with personal details.         |
| `account`            | Handles username, password, and authentication.               |
| `bankAccount`        | Inherits from `account` and provides banking features.        |
| `studyFinderAccount` | Inherits from `person` & `account`, represents student users. |
| `university`         | Stores university data, requirements, and fees.               |
| `receipt`            | Generates transaction receipts for banking operations.        |

### **Data Handling**

- Universities are stored as objects in a **vector**.
- Student and banking accounts are dynamically managed.
- Sorting is applied to **filter universities** by tuition and eligibility.

---

## Installation & Execution

### **Requirements**

- A **C++ compiler** (e.g., g++, MSVC, Clang)
- Terminal or Command Prompt

### **Compilation**

```sh
# Compile the program using g++
g++ -std=c++11 -o studyfinder main.cpp
```

### **Run the Application**

```sh
# Execute the program
./studyfinder
```

---

## Sample Usage

### **1️⃣ Main Menu**

```
=-=-=-=-=-=-=- OOP Project -=-=-=-=-=-=-=-

|[1]| Open StudyFinder
|[2]| Open BankingSystem
|[0]| Exit
```

### **2️⃣ Banking System**

```
=-=-=-=-=-=-=- Banking System -=-=-=-=-=-=-=-

|[1]| Log in to your bank account
|[2]| Create a new bank account
|[0]| Back
```

### **3️⃣ StudyFinder System**

```
=-=-=-=-=-=-=- StudyFinder -=-=-=-=-=-=-=-

|[1]| Log in
|[2]| Create a new account
|[0]| Back
```

---

## Future Enhancements

🚀 **Database Integration** - Store and retrieve user data persistently.\
🚀 **Graphical User Interface (GUI)** - Upgrade from CLI to a web interface.\
🚀 **Advanced Filtering** - Add more parameters for university searches.\
🚀 **Scholarship Recommendations** - Suggest financial aid options based on user profiles.

---

## Contributors

👨‍💻 **Ahmed Yasser Eissa**\
📍 **Artificial Intelligence Science Student @ Galala University**\
🔗 [LinkedIn Profile](https://www.linkedin.com/in/ahmed-yasser)

---

## License

🛡️ **MIT License** - Free to use and modify for educational & professional purposes.
