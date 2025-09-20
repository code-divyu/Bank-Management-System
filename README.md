# Bank Management System

A comprehensive Java-based Bank Management System designed for learning core banking operations and file handling concepts. This beginner-friendly project demonstrates object-oriented programming principles and command-line interface development.

## Overview

This project simulates a basic banking environment that enables users to create and manage bank accounts through an intuitive command-line interface. The system is ideal for students and developers learning Java programming, object-oriented design patterns, file I/O operations, and user interaction implementation.

## Features

- **Account Creation**: Set up new bank accounts with essential customer information
- **Account Management**: View detailed information for individual accounts
- **Financial Operations**:
  - **Deposit Funds**: Add money to any active account
  - **Withdraw Funds**: Remove money with built-in balance validation to prevent overdrafts
  - **Balance Inquiry**: Instantly check current account balances
- **Account Modifications**: Update customer details for existing accounts
- **Account Deletion**: Remove bank accounts from the system
- **Data Persistence**: All account information is stored in text files for persistence across application restarts

## Project Structure

```
Bank-Management-System/
├── src/
│   ├── Account.java          # Account class with customer data and operations
│   ├── Bank.java            # Main banking operations and business logic
│   ├── Main.java            # Application entry point and user interface
│   └── ... (other supporting files)
├── data/
│   └── accounts.txt         # Persistent storage for account data
├── build.xml                # Build configuration
├── manifest.mf              # Application manifest
└── README.md               # Project documentation
```

### Directory Descriptions

- **`src/`**: Contains Java source files implementing account logic and application flow
- **`data/`**: Directory for persistent account data files
- **`build/`**: Compiled class files and build artifacts

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Java IDE (Eclipse, IntelliJ IDEA, VS Code) or command-line tools
- Basic understanding of Java programming

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/code-divyu/Bank-Management-System.git
   cd Bank-Management-System
   ```

2. **Set Up Your Development Environment**
   - Import the project into your preferred Java IDE
   - Ensure all source files are in the classpath
   - Verify the `data/` directory exists for file storage

3. **Compile and Run**
   ```bash
   # Compile all Java files
   javac -d build/classes src/*.java
   
   # Run the application
   java -cp build/classes Main
   ```

### Usage

When you launch the application, you'll see a menu-driven interface with the following options:

1. **Create Account** - Register a new customer account
2. **View Account Details** - Display account information
3. **Deposit Money** - Add funds to an account
4. **Withdraw Money** - Remove funds (with balance validation)
5. **Check Balance** - View current account balance
6. **Edit Account** - Modify customer information
7. **Delete Account** - Remove an account from the system
8. **Exit** - Save changes and close the application

> **Note**: All data is automatically persisted to `accounts.txt` in the `data/` directory.

## Technologies & Concepts

### Core Technologies
- **Java**: Object-oriented programming, Collections Framework
- **File I/O**: Text-based data persistence
- **Console Application**: Command-line user interface

### Programming Concepts Demonstrated
- Object-Oriented Programming (OOP)
- Exception Handling
- File Operations and Data Persistence
- Input Validation
- Menu-Driven Programming
- Basic Banking Logic Implementation

## Example Workflow

1. **Launch the Application**
   ```
   java -cp build/classes Main
   ```

2. **Create a New Account**
   - Select option 1 from the main menu
   - Enter customer details (name, initial deposit, etc.)

3. **Perform Banking Operations**
   - Deposit funds using option 3
   - Withdraw money using option 4
   - Check balance with option 5

4. **View and Manage Accounts**
   - Review account details with option 2
   - Edit customer information with option 6
   - Delete accounts if needed with option 7

5. **Data Persistence**
   - All changes are automatically saved to `data/accounts.txt`
   - Data persists across application sessions

## Contributing

We welcome contributions to improve this project! Here's how you can help:

### How to Contribute

1. **Fork the Repository**
2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make Your Changes**
4. **Test Thoroughly**
5. **Submit a Pull Request**

### Areas for Improvement

- Enhanced error handling and validation
- Database integration (replacing file-based storage)
- GUI implementation using Swing or JavaFX
- Unit tests and automated testing
- Additional banking features (transaction history, interest calculation)
- Security improvements (password protection, encryption)

### Reporting Issues

- Use the [Issues](https://github.com/code-divyu/Bank-Management-System/issues) tab to report bugs
- Include detailed description of the problem
- Provide steps to reproduce the issue
- Suggest potential solutions if possible

## License

This project is open source and available under the MIT License. Feel free to use it for educational purposes and personal projects.

## Acknowledgments

- Built as a learning project for Java programming fundamentals
- Inspired by real-world banking system requirements
- Designed to help beginners understand OOP concepts and file handling

---

**Happy Coding!** 🚀

For questions or support, please open an issue or submit a pull request.
