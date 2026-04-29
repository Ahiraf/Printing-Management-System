# Printing Management System

This is a Bash-based Operating System lab project for managing a small printing service from the terminal.

## How to run

```bash
chmod +x printing_management_system.sh
./printing_management_system.sh
```

You can also run it with:

```bash
bash printing_management_system.sh
```

## Project files

- `printing_management_system.sh`: main application
- `users.txt`: user accounts
- `admin.txt`: admin accounts
- `in_progress_orders.txt`: pending print requests
- `history.txt`: approved/completed requests
- `prepaid.txt`: approved prepaid package balances
- `prepaid_requests.txt`: pending prepaid package requests

## Main features

- User registration and login
- Admin registration and login
- Submit print requests
- Track pending print status
- Buy prepaid printing packages
- Admin approval or rejection for prepaid requests
- Admin approval or rejection for print requests
- Print request history
- User prepaid package balance checking
- Admin view of all users' prepaid packages
- File-based data storage without database

## User features

- Create a new account
- Log in securely with username and password
- Submit print job details:
  - file name
  - number of copies
  - pages per copy
  - black and white or color
  - one-sided or double-sided
  - payment by bKash transaction or prepaid package
- Buy prepaid page packages
- See purchased package balances
- Check current request status
- View approved print history

## Admin features

- Create admin account
- Log in as admin
- View all pending print requests
- Approve or reject print requests
- View completed requests
- View all pending prepaid requests
- Approve or reject prepaid package requests
- View all approved prepaid balances

## Notes for lab presentation

- The system stores data in text files, so it demonstrates file handling in shell scripting.
- It uses functions, conditionals, loops, `case`, `awk`, and `grep`.
- It separates user-side and admin-side operations.
- It supports both regular transaction-based payment and prepaid balance-based payment.
- Approved prepaid pages are automatically deducted when a prepaid print request is approved.

## Improvements over the original script

- Added missing initialization for `in_progress_orders.txt`
- Fixed prepaid approval logic so approved requests are stored correctly
- Improved user and admin lookup using exact username matching
- Added numeric validation for copies and page counts
- Cleaned up repeated block-processing logic
