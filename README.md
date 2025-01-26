# SQL Notes
My notes on the most popular SQL commands and their use in database theory

## What is SQL?
SQL stands for Structured Query Language, is a standard language which allows you to manipulate and storage data into a relational database
> **_NOTE:_**  You can write SQL commands using either uppercase or lowercase letters, but using uppercase letters is strongly recommended as a good practice

## Creating a database in SQL
MySQL installation comes with some default schemas (or databases), which are:

* information_schema
* mysql
* performance_schema
* sys
In order to see these databases or those in existence, you must write the following command:
```
SHOW DATABASES;
```
> **_NOTE:_**  The use of semicolons is mandatory in all SQL commands
If you want to create a new database, named "test" in this example, you have to use the following command:
```
CREATE DATABASE test;
```
Or you can use this one as an alternative:
```
CREATE SCHEMA test;
```
## Select a database to work with
Perfect! Now we have our new database in our list.
Now imagine that we want to create some tables using our data in this database
Before you can modify a database you have to select it with the next command:
```
USE test;
```
