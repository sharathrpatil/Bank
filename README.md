# Bank Management System

A simple bank management system built with Streamlit and SQLite.

## Features

- Create new bank accounts
- View account details and balance
- Transfer money between accounts
- View transaction history

## Requirements

- Python 3.7+
- Streamlit
- Pandas
- SQLite3

## Installation

1. Install the required packages:
```bash
pip install -r requirements.txt
```

2. Run the application:
```bash
streamlit run bank_app.py
```

## Usage

1. Create Account:
   - Enter your full name
   - Specify initial deposit amount (minimum ₹500)
   - System will generate a unique account number

2. View Account:
   - Enter your account number to view details
   - See account balance and creation date

3. Transfer Money:
   - Enter sender's account number
   - Enter recipient's account number
   - Specify transfer amount

4. Transaction History:
   - Enter account number to view all transactions
   - See detailed history of deposits, withdrawals, and transfers
