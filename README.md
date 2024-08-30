# Restaurant-DB---SQL-Project

The restaurant ordering system is very important for a restaurant to be successful because it
affects how happy customers are and how much money the restaurant makes. The old way of
writing orders on paper can be slow and mistakes can happen, which can make customers
upset and cause the restaurant to lose money. To solve these problems, our SQL project on
the restaurant ordering system aims to provide a comprehensive solution to manage the
restaurant's ordering process efficiently and accurately.

We made a plan (called a schemo) that uses different tables to store information about
customers, their orders, menu items, and staff.

The customer table stores important information like their name, address, phone number
and email.
The menu item table has information about all the food and drinks the restaurant serves, like
their names and prices.
The orders table is used to store data on customer orders, which include order ID, order date,
customer ID and total cost of the order.
The staff table stores data on the restaurant staff, including staff ID, name, position, hourly
rate, and hire date.


Our SQL code includes create table statements for each table, which define the table's
structure by specifying its attributes, such as the data types, size, and constraints that need to
be followed.

The tables' primary keys are used to ensure data integrity and to link the tables using foreign
keys.

There is a one-to-mony relationship between the "customer id" column in the "customer" table
and the "customer_id" column in the "order" table.
This means that each customer can have many orders placed by them, but each order can
only belong to one customer. This relationship is established through the use of foreign keys.
where the "customer_id" column in the "order" table references the "customer _id" column in
the "customer" table.

To sum up, our restaurant ordering SQL project is a helpful and easy-to-use solution that
helps restaurants manage their orders, menu items, and staff with accuracy and ease. The
project can be adjusted as needed, with tables, features, and rules being added or removed
with ease. This flexible design provides a practical and economical solution for managing
restaurant operations and increasing customer happiness and income.

![image](https://github.com/user-attachments/assets/e1f547db-6f4c-43f5-aa82-29e352c251ec)

