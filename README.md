# C++ Banking System

A simple console-based banking system made using C++.

I built this project to practice C++ concepts like OOP, STL, file handling, exception handling and operator overloading.

## Features

- Create a new account
- Check account balance
- Deposit money
- Withdraw money
- Close an account
- Show all accounts
- Automatic account numbers
- Save account data to a file
- Basic error handling

## Concepts Used

- Classes and Objects
- Constructors and Destructors
- Encapsulation
- Static members
- Friend functions
- Operator overloading
- `map`
- Iterators
- Exception handling
- File handling (`ifstream`, `ofstream`)

## How to Run

Compile the program using C++17:

```bash
g++ -std=c++17 BankingSystem.cpp -o banking
```

Run it:

```bash
./banking
```

On Windows:

```bash
banking.exe
```

## Menu

```text
1. Open an Account
2. Balance Enquiry
3. Deposit
4. Withdrawal
5. Close an Account
6. Show All Accounts
7. Quit
```

## Data Storage

The account information is stored in a file called:

```text
Bank.data
```

The file is created automatically when the program saves account information.

## Note

This is a learning project and is not meant to be used as a real banking application.

## Future Improvements

- Add account login/PIN
- Add transaction history
- Add money transfer between accounts
- Improve input validation
- Move the code into separate `.h` and `.cpp` files
- Add a database instead of a text file
