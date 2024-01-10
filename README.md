# <img src="https://emojis.slackmojis.com/emojis/images/1531849353/4244/blob-octopus.gif" width="60" height="60"/>  SQLINJECTION - MY STUDY NOTES


# # SQL Injection Awareness

## What is SQL Injection?

SQL Injection is an attack technique in which an attacker inserts malicious SQL code into an SQL query. This can lead to unauthorized execution of SQL commands and compromise system integrity and security.

## How it works

1. **Input Not Validated:**
   - The vulnerability typically occurs when user input is not properly validated before being used in SQL queries.

2. **Insertion of Malicious Code:**
   - An attacker inserts malicious SQL code through input fields such as web forms, URL parameters, or cookies.

3. **Execution of Unauthorized Commands:**
   - Malicious code runs against the database, allowing the attacker to manipulate, delete, or extract unauthorized information.

## How to Avoid SQL Injection

1. **Prepared Parameters:**
   - Use prepared parameters or parameterized queries to separate data from SQL code.

2. **Input Validation:**
   - Validate and filter all user input to ensure only valid data is accepted.

3. **Principle of Least Privilege:**
   - Assign the minimum necessary permissions for SQL queries, avoiding unnecessary access to sensitive data.

4. **Use ORM (Object-Relational Mapping):**
   - Consider using ORM to interact with the database in a more secure and less error-prone way.



