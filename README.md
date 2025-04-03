SQL Assignment: Introduction to SQL and Basic Queries
Question 1
Retrieve checkNumber, paymentDate, and amount from the payments table:

sql
SELECT checkNumber, paymentDate, amount
FROM payments;
Question 2
Retrieve orderDate, requiredDate, and status of 'In Process' orders, sorted by orderDate (descending):

sql
SELECT orderDate, requiredDate, status
FROM orders
WHERE status = 'In Process'
ORDER BY orderDate DESC;
Question 3
Display firstName, lastName, and email of 'Sales Rep' employees, sorted by employeeNumber (descending):

sql
SELECT firstName, lastName, email
FROM employees
WHERE jobTitle = 'Sales Rep'
ORDER BY employeeNumber DESC;
Question 4
Retrieve all columns and records from the offices table:

sql
SELECT *
FROM offices;
Question 5
Fetch productName and quantityInStock, sorted by buyPrice (ascending), limited to 5 records:

sql
SELECT productName, quantityInStock
FROM products
ORDER BY buyPrice ASC
LIMIT 5;
