# Expense-Tracker

#Expense Tracker
A simple web application for tracking income and expenses.

#Overview
Expense Tracker allows users to manage their finances by tracking transactions. It provides a clear summary of balances, income, and expenses, along with a history of transactions.

#Features
Balance Display: Shows the current balance prominently at the top.
Income and Expense Tracking: Clearly distinguishes between income (green) and expenses (red).
Transaction History: Lists all transactions with options to delete individual transactions.
Add New Transactions: Allows users to input new transactions (income or expense).
Persistent Storage: Transactions are stored locally using browser's localStorage, ensuring data persistence between sessions.

#Usage

Viewing Balance:

The main balance is displayed at the top.
Income is displayed in green.
Expenses are displayed in red.

Adding Transactions:

Use the form under "Add New Transaction" section.
Enter a text description for the transaction.
Enter the transaction amount:
Use positive amounts for income.
Use negative amounts for expenses.

Transaction History:

Each transaction is listed with its description and amount.
Transactions are color-coded based on income or expense.
Each transaction item has a delete button (x) to remove the transaction.

Persistent Storage:

Transactions are saved locally using localStorage.
When you revisit the page, your previous transactions are loaded automatically.


#Technologies Used
HTML: Structure of the web page.
CSS: Styling for layout and visual representation.
JavaScript: Logic for handling transactions, updating the UI, and local storage interactions.
