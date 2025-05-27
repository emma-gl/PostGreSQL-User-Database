# PostgreSQL User Database / Flutter App
# Overview

The following software (specifically the .js file) performs a series of queries in SQL language to view, add, delete, and update user data inside the connected database. This works by using Node's connection pooling which maintains a connection to the user database and various JavaScript functions to perform the queries.

I wrote this software to eventually integrate it with a webpage which takes in inputted data from a user and apply it to the database via the backend. So, this database will be acted upon by any user on the web.


# Relational Database

[PostGreSQL15](https://www.postgresql.org/about/news/postgresql-15-released-2526/)

<b>Tables:</b>

users:
 - first_name (VARCHAR)
 - last_name (VARCHAR)
 - city (VARCHAR)
 - phone (VARCHAR)
 - gender (VARCHAR)
 - orientation (VARCHAR)
 - email (VARCHAR)
 - date_of_birth (DATE)

matches:
 - id (INT)
 - swipe_yes (INT)
 - swipe_no (INT)


# Development Environment

Tools used:
- Node JS
- npm
- PgAdmin 4
- Render

Languages used:
- SQL (for database)
- JavaScript (for backend)
- <i>HTML/CSS (for frontend)</i>*

# Useful Websites

- [Creating a REST API Backend using Node.js, Express and Postgres by GeeksForGeeks](https://www.geeksforgeeks.org/creating-a-rest-api-backend-using-node-js-express-and-postgres/)
- [Node.js MySQL Create Database by w3](https://www.w3schools.com/nodejs/nodejs_mysql_create_db.asp)

# Future Work

Being that this is the foundational database for a future app, there is a lot to build upon, such as:

- Connect web frontend to input user data 
- Deploy site on web
- Fine tune table columns/data types
