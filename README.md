# Bank Management System - C++

A console-based bank management system built with C++ and Object-Oriented Programming principles.

The application provides client management, banking transactions, user management with permissions, login auditing, transfer history, and currency exchange functionality. Data is stored locally using text files.

## Features

### Client Management

- List all clients
- Add new clients
- Delete clients
- Update client information
- Find clients by account number

### Banking Transactions

- Deposit money
- Withdraw money
- Display total balances
- Transfer money between accounts
- View transfer history

### User Management

- User login
- Maximum of three failed login attempts
- List users
- Add new users
- Delete users
- Update users
- Find users
- Permission-based access control

### Permissions

The system supports permissions for:

- Listing clients
- Adding clients
- Deleting clients
- Updating clients
- Finding clients
- Banking transactions
- User management
- Viewing the login register

Users can also be granted full access.

### Login Register

Successful logins are recorded in a local log file with information such as:

- Date and time
- Username
- Permissions

### Currency Exchange

- List available currencies
- Find a currency
- Update currency exchange rates
- Convert amounts between currencies

## Technologies

- C++
- Object-Oriented Programming (OOP)
- Standard Template Library (STL)
- File handling
- Visual Studio
- Windows Console Application

## Project Structure

```text
BankManagementSystem/
├── BankManagementSystem.cpp
├── clsBankClient.h
├── clsUser.h
├── clsPerson.h
├── clsCurrency.h
├── clsScreen.h
├── clsInputValidate.h
├── clsString.h
├── clsDate.h
├── clsUtil.h
├── Clients.txt
├── Users.txt
├── Currencies.txt
├── LoginRegister.txt
├── TransfersLog.txt
└── ...
```

The project separates the main entities and console screens into dedicated classes.

## Data Storage

The application uses local text files instead of a database.

```text
Clients.txt
Users.txt
Currencies.txt
LoginRegister.txt
TransfersLog.txt
```

The files use the following separator between fields:

```text
#//#
```

`LoginRegister.txt` and `TransfersLog.txt` are runtime log files and are initially empty in the repository.

## Demo Login

You can use the following account to explore the application:

```text
Username: User2
Password: 1234
```

This user has full permissions.

## Running the Project

### Requirements

- Windows
- Visual Studio with Desktop development with C++
- MSVC v143 toolset
- Windows SDK

### Steps

1. Clone the repository.
2. Open:

```text
BankManagementSystem.sln
```

3. Build the solution in Visual Studio.
4. Run the application.
5. Log in using the demo credentials.

## Notes

This project is intended for learning and practicing C++ application design, Object-Oriented Programming, file handling, validation, permissions, and console application development.

The application uses text files for persistence and is not intended to represent a production banking system.

User passwords are stored using a simple reversible encoding mechanism for educational purposes. It should not be considered secure password storage for a production application.

## Screenshots

Screenshots of the main application workflows will be added later.
