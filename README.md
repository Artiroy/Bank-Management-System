# Bank Management System

A simple console-based Bank Management System developed in C# that allows both admins and customers to interact with the system. The system supports functionalities such as account creation, searching accounts, depositing and withdrawing money, account activation/deactivation, and displaying account details.

## Features

### Admin Features:
- **Add Account**: Admin can add a new account with an account number, account holder name, and initial balance.
- **Display Accounts**: View all accounts with details such as account number, holder name, balance, and status (active/inactive).
- **Deactivate Account**: Admin can deactivate an account, making it inactive.
- **Activate Account**: Admin can reactivate a previously deactivated account.
- **Count Accounts in Bank**: Display the total number of accounts in the bank.

### Customer Features:
- **Search Account**: Customers can search for an account by account number.
- **Deposit Money**: Customers can deposit money into their account.
- **Withdraw Money**: Customers can withdraw money from their account (provided sufficient balance is available).
- **View Total Balance**: Customers can check the current balance of their account.

## Technologies Used
- **C#**: The main programming language used for developing the system.
- **Console Application**: The system runs as a console-based application.

## Requirements
- .NET Core or .NET Framework to run the C# program.
- A terminal or command prompt to execute the program.

## How to Run

1. Clone the repository or download the files.
2. Open the project in Visual Studio or any other C# IDE.
3. Build and run the program.
4. Select the user type (Admin or Customer) and start interacting with the system.

## Code Explanation

- **Account Class**: Represents a bank account with properties like account number, account holder name, balance, and account status (active/inactive).
- **Bank Class**: Handles bank operations like adding accounts, displaying account details, searching accounts, deposits, withdrawals, and account activation/deactivation.
- **Program Class**: The entry point of the program where the main menu logic is handled for both Admin and Customer.
