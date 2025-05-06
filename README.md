# Bank-Management-System
This C-based Bank Management System simulates a banking environment, allowing users to manage accounts and perform various banking operations. The system features an ATM section where users can check balances, deposit, and withdraw money. It also includes functionality for creating, editing, deleting, and viewing customer accounts.

Features
User Login:

The system begins with a user login prompt where users must enter a password to gain access to the main menu.

The password is validated against a predefined password ("admin").

Main Menu:

The main menu provides various options for the user, such as:

Creating a new account

Editing an existing account

Performing transactions (deposit/withdraw)

Checking account details

Removing an existing account

Viewing the customer list

Accessing the ATM feature

Exiting the system

ATM Feature:

Login: Users can log in to the ATM system by entering a PIN (default PIN is 1234).

ATM Menu: Once logged in, users can choose between the following options:

Check Balance: Displays the user's current balance.

Deposit: Users can deposit money into their account.

Withdraw: Users can withdraw money from their account, with checks to ensure they have sufficient funds.

Exit: Ends the ATM session with a thank-you message.

Input Validation: Ensures that the user inputs valid amounts for deposits and withdrawals. Invalid inputs are handled gracefully.

Account Management:

Create New Account: Allows users to create a new account with personal details such as name, age, address, account type, etc.

Edit Existing Account: Users can modify details of an existing account, such as their name or address.

Transaction: Users can perform transactions, like deposit or withdrawal.

Delete Account: Allows users to delete an existing account by entering the account number.

View Account Details: Users can check details of an existing account by account number or name.

Code Overview
The ATM functions (checkBalance, moneyDeposit, moneyWithdraw, menuExit) allow the user to interact with their account balance and perform operations like depositing and withdrawing money.

The mainMenu function displays the ATM menu and calls the relevant function based on user input.

Input validation is implemented to ensure that the user only enters valid amounts (positive floating-point numbers) for deposits and withdrawals.

The ATM PIN is validated against a hardcoded value (1234), ensuring only authorized access.

The error handling mechanisms display user-friendly messages if an invalid input is entered or insufficient funds are available for withdrawal.

Technologies Used
C Programming Language: The entire system is written in C for simplicity and to provide a hands-on understanding of low-level operations like file handling and input/output.
