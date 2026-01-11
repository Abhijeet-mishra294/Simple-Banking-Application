# 🏦 Simple Banking System
A basic console-based application that simulates essential banking operations. This project demonstrates the fundamentals of Object-Oriented Programming (OOP), state management, and user input validation.


## 🌟 Features

   - 💰 Deposit Funds: Add money to the user's account balance.

   - 💸 Withdraw Funds: Remove money from the account with validation checks (ensures sufficient funds and valid input).

   - 📊 Check Balance: View the current available balance instantly.

   - 🛡️ Input Validation: Prevents negative inputs and invalid transactions.

   - User Menu: A simple, looping menu interface for easy navigation.


  ##  🛠️ Technologies Used
     
- Language: Java (or replace with Python/C++)

- Concept: Object-Oriented Programming (Classes, Methods, Encapsulation)

- Interface: Command Line Interface (CLI)

##  How to Run

1. Clone the Repository
   
    `Bash`
   
       git clone https://github.com/your-username/simple-banking-system.gitcd simple-banking-system.

2. Compile the source code:

    `Bash`

       javac BankingApp.java

3. Run the application:

    `Bash`

       java BankingApp

## 💻 Usage Example

Here is how the application works in the terminal: `Plaintext`

 `Plaintext`
 
       ==================================
       WELCOME TO THE BANKING SYSTEM
       ==================================
       1. Check Balance
       2. Deposit
       3. Withdraw
       4. Exit
       ==================================
       Enter an option: 2

      Enter amount to deposit: 500
      > Success: $500.0 deposited. New Balance: $500.0

      ==================================
      Enter an option: 3

      Enter amount to withdraw: 200
      > Success: $200.0 withdrawn. Remaining Balance: $300.0

## 📂 Project Structure

- `(BankingApp.java)` (Main Class): Handles the program execution and the menu loop.

- `BankAccount.java` (Class): Defines the blueprint for an account, containing the `balance` variable and methods for `deposit()`, `withdraw()`, and `getBalance()`.

 ## 🔮 Future Improvements
  
Here are some features I plan to add in the future:

 - [ ]Multiple Users: Allow creation of multiple distinct accounts.

 - [ ]PIN Authentication: Add security before accessing account details.

 - [ ]Transaction History: Record and display the last 5 transactions.

 - [ ]File Handling: Save account data to a text file so it persists after closing the program.

 ##  🤝 Contributing
   
Contributions are welcome! If you have ideas for improving the interface or adding new banking features, feel free to fork the repo and submit a pull request.
