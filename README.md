# ATM Interface

This project is a Java-based ATM interface application that allows users to perform basic banking operations such as login, withdrawal, deposit, and transfer. The application connects to a MySQL database using JDBC for handling all transactions.

## Features

- User Authentication
- Withdrawal
- Deposit
- Transfer
- Transaction History

## Technologies Used

- Java
- JDBC (Java Database Connectivity)
- MySQL
- SQL

## Database Schema
The application uses a MySQL database with the following schema:

Account Number	PIN	Amount
123451234512	1212	1000
123456789012	1234	800


## Setup Instructions

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- MySQL Server
- JDBC Driver for MySQL

### Steps
1. **Clone the repository**
   git clone <repository-url>
   cd <repository-directory>

2. **Set up the MySQL database**
Create a database named ATMInterface.
Create a table userDetails with columns accountNumber, pinNumber, and amount.

3. **Update the database connection details**
Modify the url, username, and password variables in the Main class to match your MySQL setup.

4. **Compile and run the application**
javac SamplePackage/Main.java
java SamplePackage.Main


### How to use

- Run the application

- Log in by entering your account number and PIN.

- Choose an operation:
  - 0: Exit  
  - 1: Withdraw
  - 2: Deposit
  - 3: Transfer
- Follow the prompts to complete your transaction.
