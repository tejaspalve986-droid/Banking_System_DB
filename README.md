# Banking System Database

## Project View

This project is a Banking System Database created using MySQL. The main purpose of this project is to manage banking-related information such as customers, accounts, branches, transactions, and loans in one database.

The database stores customer details and connects them with their bank accounts. It also keeps track of account balances, transactions, branches, and loan information.

I created this project to understand how a real banking system can be structured using a relational database and how different banking records are connected with each other.

## What This Project Covers

* Customer details
* Bank accounts
* Account balances
* Bank branches
* Account transactions
* Customer loans
* Customer and account relationships
* Branch and account relationships
* Transaction records
* Loan records
* Banking data analysis

## Database Structure

The main entities used in the project are:

```text
Customers
    |
    +---- Accounts
    |        |
    |        +---- Transactions
    |
    +---- Loans
             
Branches
    |
    +---- Accounts
```

Customers are connected with their accounts and loans. Accounts are connected with transactions, while branches are connected with the accounts managed by them.

## Project Files

```text
Banking_System_DB/
│
├── Banking_System_DB.sql
├── ER_DIGRAM.mwb
├── ER_DIGRAM.mwb.bak
└── README.md
```

`Banking_System_DB.sql` contains the database creation, tables, data, queries, and views used in the project. The repository also contains the MySQL Workbench ER diagram files.

## Database Analysis

The project can be used to find information such as:

* Total number of customers
* Customer account details
* Account balances
* Total balance in accounts
* Transaction details
* Total transaction amount
* Branch-wise account information
* Customer loan information
* Total loan amount
* Average account balance
* Branch performance

## Tools Used

* MySQL
* MySQL Workbench
* SQL

## Project Outcome

The final database provides a single place to store and manage banking information. It makes it easier to connect customer information with accounts, transactions, branches, and loans and use the stored data for further analysis.

## ER Diagram

The project includes an ER diagram created in MySQL Workbench to show the tables and their relationships.

File:

```text
ER_DIGRAM.mwb
```

## Author

**Tejas Palve**

GitHub:
https://github.com/tejaspalve986-droid
