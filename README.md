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

## Installation (User)

### Prerequisites
- Java JDK 17+

### Run the program
```bash
git clone https://github.com/yourusername/banking-app.git
cd banking-app
javac Main.java
java Main
```

## Installation (Contributor)

Same as above. The project is a single file (`Main.java`), so there's no build tool or dependency setup needed. Just clone, edit, compile, and run.

## Contributor Expectations

This is a learning project so I'm not actively seeking contributions, but if you want to suggest improvements or point out something I could do better, feel free to open an issue.

## Known Issues

- The program doesn't handle non-numeric input (entering a letter instead of a number will crash it)
- Balance resets every time the program is closed (no persistent storage)
