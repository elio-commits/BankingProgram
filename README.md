# BankingApp
## A simple CLI banking simulator built in Java

## About

A command-line program that simulates basic banking operations — checking a balance, depositing money, and withdrawing funds. Built as a first Java project while following a tutorial to practice core language fundamentals like methods, control flow, and input handling.

## Demo

```
----------------------
   BANKING PROGRAM
----------------------
1) Show Balance
2) Deposit
3) Withdraw
4) Exit
----------------------
Enter your choice (1-4): 2
Enter an amount to be deposited: 500.00

Enter your choice (1-4): 1
----------------------
Your balance is: $500.00

Enter your choice (1-4): 3
Enter withdrawn amount: 200.00

Enter your choice (1-4): 1
----------------------
Your balance is: $300.00
```

## How to Run

### Prerequisites
- Java JDK 17+

```bash
git clone https://github.com/yourusername/banking-app.git
cd banking-app
javac Main.java
java Main
```

## Concepts Practiced

- Methods with return types (`deposit()`, `withdraw()`, `showBalance()`)
- `while` loop for a persistent menu
- Enhanced `switch` expressions
- Input validation for negative values and overdrafts
- Formatted output with `printf`

## Known Issues

- Entering a letter instead of a number will crash the program
- Balance resets when the program is closed (no persistent storage)
