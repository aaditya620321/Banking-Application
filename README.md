# Banking Application

This is a simple console-based banking application written in Python. It simulates basic banking operations such as viewing account balances, withdrawing and depositing cash, changing PINs, and returning cards.

## Features

- View account balance
- Withdraw cash
- Deposit cash
- Change account PIN
- Return card and exit the system

## How It Works

1. **Welcome Message**: Upon running the program, the user is greeted and given a menu of options to choose from.
2. **PIN Authentication**: Every time the user attempts to perform an action, they must authenticate using their 4-digit PIN.
3. **Operations**: Depending on the user's selection, they can view their account balance, withdraw or deposit cash, or change their PIN.
4. **Exit**: The user can return their card and safely log out by selecting the exit option.

## Usage

1. **Run the script**: 
   ```bash
   python Banking_application.py
Choose an option from the menu:

- Logout and Exit
- View Account Balance
- Withdraw Cash
- Deposit Cash
- Change PIN
- Return Card
  
Authentication: Enter the 4-digit PIN when prompted. The default PIN is 9876.

Requirements
- Python 3.x
Future Enhancements
Support for multiple users with unique account details.
Secure PIN storage with encryption.
Enhanced transaction logging.
License

- This project is licensed under the MIT License. See the LICENSE file for details.
