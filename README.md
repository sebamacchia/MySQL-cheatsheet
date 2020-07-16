# MySQL-cheatsheet

## Basics
USE sql_store;

SELECT *

FROM customers
WHERE state = ‘CA’
ORDER BY first_name
LIMIT 3;

• SQL is not a case-sensitive language.
• In MySQL, every statement must be terminated with a semicolon.

## Comments
We use comments to add notes to our code.
—- This is a comment and it won’t get executed.

## SELECT Clause
—- Using expressions
SELECT (points * 10 + 20) AS discount_factor
FROM customers
Order of operations:
• Parenthesis
• Multiplication / division
• Addition / subtraction
—- Removing duplicates
SELECT DISTINCT state
FROM customers 
