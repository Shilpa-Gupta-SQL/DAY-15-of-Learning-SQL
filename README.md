SQLSTATE & SIGNAL (Day 15)
📌 Overview
This repository documents my learning about SQLSTATE and SIGNAL, which are used for error handling and exception control in SQL. These concepts are mainly applied in stored procedures and triggers to enforce business rules and handle invalid operations gracefully.

🔍 What I learned
*What SQLSTATE is and why it is used
*Structure of SQLSTATE error codes (5-character format)
*Meaning of SQLSTATE classes and conditions
*How to use SIGNAL SQLSTATE to raise custom errors
*Using SQLSTATE for validation inside triggers and procedures 
*Writing meaningful error messages for better debugging

🧠 Key Concepts
*SQLSTATE is a standardized error code that identifies the type of SQL error
*It consists of:
*First 2 characters → error class
*Last 3 characters → specific condition
*45000 is commonly used for user-defined exceptions
*SQLSTATE helps stop execution when business rules are violated

⚙️ Practical Usage
*Preventing invalid data insertion
*Enforcing business logic at the database level
*Custom error handling in triggers
*Improving clarity of database errors
