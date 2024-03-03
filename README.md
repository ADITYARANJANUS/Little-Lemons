# Meta-SQL-Project

SQL Project on Little Lemons Restaurant. 

# Description:

This is a SQL Analysis Project on Little Lemons Resturant where various SQL queries have been implemented such as WHERE, JOIN, VIEW , Aggregate functions like GROUP BY, Subquery and many more are used to find out the records of bookings, names of the customers made the bookings on a specific date, calculation on total bookings made on each booking date, bookings data based on certain criteria, etc.

# Key Responsibilities:

1) Data Filtering with WHERE Clause:

Utilized SQL statements to filter data from the Bookings table based on specified booking dates using the BETWEEN operator.
Implemented logical operators to retrieve all records for bookings made between 2021-11-11 and 2021-11-13.

2) JOIN Query Creation:

Developed SQL JOIN statements to combine data from the Customers and Bookings tables.
Created a JOIN query to retrieve the full names of customers and their corresponding booking IDs for bookings made on a specific date (e.g., 2021-11-11).

3) Grouping and Aggregation with GROUP BY:

Constructed SQL statements utilizing the GROUP BY clause to group bookings data by booking dates.
Implemented aggregation functions such as COUNT() to calculate the total number of bookings placed on each booking date.

4) Data Modification with REPLACE Statement:

Designed SQL REPLACE statements to update specific records in the Courses table.
Implemented REPLACE statements to modify the cost of a particular course (e.g., Kabsa) from $17.00 to $20.00.

5) Table Creation with Constraints:

Created a new table named "DeliveryAddress" in the Little Lemon database with defined columns and constraints.
Specified constraints such as PRIMARY KEY, NOT NULL, DEFAULT values, and FOREIGN KEY referencing to ensure data integrity and consistency.

6) Table Structure Alteration:

Developed SQL statements to alter the structure of existing tables.
Added a new column named 'Ingredients' to the Courses table with the specified data type (VARCHAR(255)).

7) Subquery Implementation:

Implemented SQL subqueries to retrieve data based on nested queries.
Created a subquery within a SELECT statement to obtain the full names of customers who made bookings on a specific date (e.g., 2021-11-11).

8) Virtual Table Creation with Views:

Defined a virtual table named "BookingsView" using CREATE VIEW statements.
Specified conditions to filter bookings data based on certain criteria (e.g., before 2021-11-13 and with more than 3 guests).

9) Stored Procedure Development:

Created a stored procedure named 'GetBookingsData' with a parameter for input date.
Utilized the procedure to retrieve all booking data from the Bookings table based on user-provided dates.

10) String Function Utilization:

Utilized appropriate MySQL string functions within SELECT queries to format and display booking details.
Constructed SELECT queries to list booking details including booking ID, date, and number of guests in a specified format (e.g., ID: 10, Date: 2021-11-10, Number of guests: 5).
