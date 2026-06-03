Personal Expense Tracker

A simple console-based Personal Expense Tracker built using C++. This application allows users to record expenses, view all saved expenses, calculate total spending, and store data in a file for future use.

Features
Add new expenses with category and amount
View all recorded expenses
Calculate total expenses
Save expenses to a file
Automatically load saved expenses on startup
Simple menu-driven interface
Technologies Used
C++
File Handling
Object-Oriented Programming (OOP)
Standard Template Library (STL)
Project Structure
Personal-Expense-Tracker/
│
├── main.cpp
├── expenses.txt
└── README.md
How It Works
Launch the application.
Select an option from the menu:
Add Expense
View Expenses
Show Total Expenses
Exit
Expenses are stored in expenses.txt.
Previously saved expenses are loaded automatically when the program starts.
Compilation

Using g++:

g++ main.cpp -o ExpenseTracker
Run
./ExpenseTracker

On Windows:

ExpenseTracker.exe
Sample Input
Enter category: Food
Enter amount: 250
Sample Output
Expense List

Category            Amount
Food                250.00
Transport           100.00

Total Expenses: 350.00
Future Enhancements
Monthly expense reports
Expense categories with statistics
Budget tracking
Search and filter expenses
Delete or edit expenses
Graphical User Interface (GUI)
Database integration
Learning Outcomes

This project helps practice:

Classes and Objects
File Input/Output
Vectors and STL
Functions
Menu-driven programming
Data persistence
