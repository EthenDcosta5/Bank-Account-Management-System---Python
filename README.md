
# Bank Account Management System

## Overview

The **Bank Account Management System** is a Python-based application that allows users to create and manage bank accounts, perform transactions, and view transaction history. This project demonstrates key Python concepts, including file handling, data structures, functions, and error handling.

## Features

### Account Management
- Create new accounts with attributes:
  - Account Holder's Name
  - Account Number (auto-generated)
  - Account Type (Savings/Current)
  - Initial Balance
- View account details.

### Transactions
- **Deposit:** Add funds to an account.
- **Withdraw:** Withdraw funds, ensuring sufficient balance.
- **Transfer:** Transfer funds between two accounts.
- Transaction updates are reflected in real-time.

### Transaction History
- View transaction history with details:
  - Date & Time
  - Type of Transaction
  - Amount
  - Updated Balance
- Generate summary statistics:
  - Total deposits and withdrawals.
  - Average transaction amounts.

### File Handling
- Persistent storage of account data and transactions using the `pickle` library.
- Data is loaded at the start and saved upon program exit.

### User Interaction
- Interactive menu for navigation:
  1. Open a new account
  2. View account details
  3. Perform transactions
  4. View transaction history
  5. Exit

### Error Handling
- Input validation for account creation and transactions.
- Handling invalid login attempts or non-existent accounts.

### Bonus Features (Optional)
- Auto-generated usernames and passwords.
- Use of `lambda` functions for quick input validations.

## Technologies Used
- Python
- Libraries: `numpy`, `pickle`, `datetime`

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd Bank-Account-Management-System
   ```
3. Run the Python script:
   ```bash
   python Bank-Account-Management-System.py
   ```

## File Structure
- **`user_details.pkl`**: Stores account holder details.
- **`account_details.pkl`**: Maps account numbers to user data.
- **`credentials.pkl`**: Stores usernames and passwords.
- **`transactions.pkl`**: Logs all transactions.

## Contributions
Contributions are welcome! Feel free to fork the repository and submit a pull request.
