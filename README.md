# Apex Bank Account Handler

This project contains a simple Apex class and test class to simulate basic bank account operations such as depositing and withdrawing funds. It is designed to demonstrate core Apex concepts including class creation, instance methods, validation, and test class coverage.

## Project Structure

- `BankAccountHandler.cls`  
  Contains the Apex logic for managing a bank account including deposit and withdraw operations.

- `TestBankAccountHandler.cls`  
  Contains the unit tests to verify functionality of the `BankAccountHandler` class. Achieves 100% code coverage.

## Features

- Initialize an account with a starting balance
- Deposit money (validates positive amount)
- Withdraw money (validates positive amount and sufficient balance)
- Error prevention for invalid transactions
- Clean and readable object-oriented design

## Use Case

Ideal for beginners learning:
- Apex class structure
- Object-oriented programming in Salesforce
- Writing test methods and assertions
- Handling user-defined logic and validations

## Test Coverage

This project includes a complete test class:
- Tests valid deposit and withdraw
- Prevents negative deposit
- Prevents withdrawing more than the available balance
- Uses `System.assertEquals()` for validations
