# Project: Student Saving Management System 
It demonstrates basic C programming concepts, including the use of structures, functions, loops, and user input/output.


# Objective
The Student Saving Management System is designed to provide a simple yet effective platform for students to perform various operations such as adding financial records, viewing transaction history, spending money, and checking their balance.  The system includes a simple login mechanism for user authentication.

# Components/Features 
#Structures
'struct Record'
Represents a financial transaction with fields for date, description, amount, and spent amount.
'struct BankSystem'
Represents the overall bank system with fields for balance, an array of transactions (struct Record), and the count of transactions.

#Pointer 
Functions such as addrecord, viewrecords, spend, and balancestatus take a struct BankSystem *bank pointer as a parameter. This pointer enables the functions to operate on the actual data stored in the bank structure, allowing them to modify the bank's state.

#Functions
addrecord(struct BankSystem *bank): Adds a financial record to the system.
viewrecords(struct BankSystem *bank): Displays existing financial records.
spend(struct BankSystem *bank): Simulates spending money and updates the balance.
balancestatus(struct BankSystem *bank): Displays the current balance.
login(): Implements a basic login system for user authentication.

# Main Components
1. Modularity:
The code is structured using functions and structures to enhance modularity and maintainability.

2. User Interaction:
The main loop provides a user-friendly menu for interacting with the bank system.

3. Transaction Tracking:
The system keeps track of financial transactions, allowing users to view their transaction history and check the balance.

4. Login System:
Implements a basic login system for user authentication, allowing or denying access based on entered credentials.


# Future Improvements
File Handling 

Authentication Mechanism 

Data persistence (saving transaction files to a file)




