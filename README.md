AW&H Employee Portal
A PHP-based web application for AW&H employees to securely connect to the company database, view employment details, send emails, execute queries, and update records.

Features:

Secure Login: Employees authenticate using their EIN, username, and database credentials (max 3 attempts).
Employment Details: View current BAN, branch, salary calculations, and highest qualification.
SQL Execution: Run predefined queries or custom SELECT and UPDATE queries on the employee database.
Email Notifications: Send employment details (excluding password) to a specified email.
User Confirmation & Feedback: Ensures successful updates and provides appropriate messages for errors.
Exit Confirmation: Requests user confirmation before disconnecting from the database.
Tech Stack:
> Backend: PHP
> Frontend: HTML, CSS
> Database: MySQL

Installation:

Clone the repository:

Set up a local server (e.g., XAMPP, WAMP).
Configure database connection in config.php.
Run the application in a web browser.


Usage:

Enter login credentials (EIN, username, database).
Upon successful connection, access available menu options.
Select and execute predefined queries or custom SQL statements.
Send employment details via email if needed.
Confirm before exiting the application.

