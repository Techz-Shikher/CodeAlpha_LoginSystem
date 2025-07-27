# Login and Registration System

This is a basic user login and registration system written in C++. It demonstrates file handling and user authentication through username and password validation.

## 📌 Features

- User registration with username and password
- Duplicate username detection
- User login with password verification
- Credentials stored in a local file (`users.txt`)
- Simple menu interface for operation

## 🔐 File Storage Format

The file `users.txt` stores user credentials in the format:
**username password**
Each line corresponds to one user.

## 🛠 How to Compile and Run

1. **Compile the program** using a C++ compiler like `g++`:
   ```bash
   g++ main.cpp -o login_system
Run the executable:

./login_system   # For Linux/Mac

login_system.exe # For Windows
## **📋 Sample Usage**

1. Register
2. Login
Enter choice: 1
Enter username: alice
Enter password: pass123
Registration successful.

## **📋 Sample Output**
1. Register
2. Login
Enter choice: 2
Enter username: alice
Enter password: pass123
Login successful. Welcome, alice!

