# Bank-Management-System

Bank Management System
This project is a basic bank management system implemented in Java with a MySQL database backend. It provides functionalities such as creating customer accounts, depositing and withdrawing funds, transferring funds between accounts, and viewing transaction history.

Table of Contents
Features
Requirements
Setup
Usage
Database Schema
Contributing
License
Features
Create new customer accounts.
Deposit and withdraw funds from customer accounts.
Transfer funds between accounts.
View transaction history.
User-friendly graphical interface built using Java Swing.
Requirements
Java Development Kit (JDK) 8 or higher
MySQL Server
MySQL Connector/J library
IDE (Integrated Development Environment) such as IntelliJ IDEA or Eclipse (optional)
Setup

Create MySQL Database:

Install MySQL Server if not already installed.
Create a new database named bank_management_system.
Execute the SQL script database.sql located in the database directory to create the necessary tables.
Configure Database Connection:

Open the DBConnection.java file located in the src directory.
Modify the DB_URL, USERNAME, and PASSWORD constants to match your MySQL database configuration.
Add MySQL Connector/J library:

Download the MySQL Connector/J library from here.
Add the JAR file to your project's build path.
Usage
Compile and Run:

Compile the Java files using your preferred IDE or command line.
Run the Main.java file to start the application.
Login:

Use the provided username and password to log in to the system.
Explore the functionalities:

Create new customer accounts.
Deposit, withdraw, and transfer funds.
View transaction history.
Database Schema
The database schema consists of the following tables:

customers: Stores information about customers.
accounts: Stores information about bank accounts.
transactions: Stores transaction history.
For detailed information on the schema, refer to the database.sql file.

Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to contribute to this project.
