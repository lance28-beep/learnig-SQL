# SQL Tutorial<br>

- SQL is a standard language for storing, manipulating and retrieving data in databases.<br>
- SQL stands for Structured Query Language<br>
- SQL became a standard of the American National Standards Institute (ANSTI) IN 1986, and of the International Organization for Standardization (ISO) in 1987<br>

## What can SQL do?<hr>

- SQL can execute queries against a database
- SQL can retrieve data from a database
- SQL can insert records in a database
- SQL can update records in a database
- SQL can delete records from a databases
- SQL can create new databases
- SQL can create new tables in a database
- SQL can create stored procedures in a database
- SQL can create views in a database
- SQL can set permissions on tables, procedures, and views

## SQL in your WEB site<br>

to build a website that shows data from a database, you will need:<br>

- an <code>RDBMS database</code> program (i.e MS Access, SQL Server, MySQL)<br>
- to use a server-side scripting language,
- to use SQL to get the data you want
- to use HTML / CSS to style the page<br>

## RDBMS

- stands for <code>Relational Database Management System</code>
- RDBMS is the basis for SQL, and for all modern database systems such as MS SQL server, IBM DB2,Oracle,MySQL, and Microsoft Access.
- The data in RDBMS is stored in database object called tables. A table is a collection of related data entries and it consist of columns and rows.
  > SELECT \* FROM Customers;

## Database Tables

- a database most oftern contains one or more tables.Each table is identified by a name(e.g "Customers" or "Orders").Tables contain records (rows) with data.<br>
  <img src='./img/database.PNG' width='500'><br>
- the table above contains five records(one for each customer) and seven columns (CustomerID, CustomerName, ContactName, Address, City, PostalCode, and Country)<br>:

## SQL Statements <br>

Most of the actions you need to perform on a database are done with SQL statements<br>

> SELECT \* FROM Customers;

Note:<br>
<code> Keep in Mind That...</code>

- SQL keywords are <code>not case sensitive</code>:<br>
- <b><u>select</u></b> is the same as <b><u>SELECT</u></b>.<br>

## Semicolon after SQL Statements?<br>
- some database systems require a semicolon at the end of each SQL statement.<br>
- semicolon is the standard way to separate each SQL statement in database systems that allow more than one SQL statement to be executed in the same call to the server.<br>

### Some of the Most Important SQL Commands
- <code>SELECT</code> - extracts data from a database<br>
- <code>UPDATE</code> - updates data in a database<br>
- <code>DELETE</code> - deletes data from a database<br>
- <code>INSERT INTO</code> - insert new data into in database<br>
- <code>CREATE DATABASE</code> - creates a new database<br>
- <code>ALTER DATABASE</code> - modifies a database<br>
- <code>CREATE TABLE</code> - creates a new table<br>
- <code>ALTER TABLE</code> - modifies a table<br>
- <code>DROP TABLE</code> - delete a table<br>
- <code>CREATES INDEX</code> - creates an index (search key)<br>
- <code>DROP INDEX</code> - deletes an index<br>

## SQL Select Statement<br>
the <code>SELECT</code> statement is used to select data from a database.<br>
