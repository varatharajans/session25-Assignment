# session25-Assignment
DATA ANALYTICS WITH R, EXCEL AND TABLEAU SESSION 25 ASSIGNMENT 
Session 25 Assignment

Use the Sakila schema, which can be found in following link (to be installed in your local system) 
http://dev.mysql.com/doc/index-other.html("sakila database") 
http://dev.mysql.com/doc/sakila/en/sakila.html(for full documentation) 
Requirements 
For each question, you are required to provide the following: 
- The SQL query you used 
- The answers 
- Any assumptions you made 
Problem Statement 
Set up/Install the database sakila. 
The database will be used for next MySQL Assignments as well. 
Refer the Links given above for help in setting up the database.









Installation
The Sakila sample database is available from http://dev.mysql.com/doc/index-other.html. A downloadable archive is available in compressed tar file or Zip format. The archive contains three files: sakila-schema.sql, sakila-data.sql, and sakila.mwb.

The sakila-schema.sql file contains all the CREATE statements required to create the structure of the Sakila database including tables, views, stored procedures, and triggers.

The sakila-data.sql file contains the INSERT statements required to populate the structure created by the sakila-schema.sqlfile, along with definitions for triggers that must be created after the initial data load.

The sakila.mwb file is a MySQL Workbench data model that you can open within MySQL Workbench to examine the database structure..

To install the Sakila sample database, follow these steps:

1)Extract the installation archive to a temporary location such as C:\temp\ or /tmp/. When you unpack the archive, it creates a directory named sakila-db that contains the sakila-schema.sql and sakila-data.sql files.

2)Connect to the MySQL server using the mysql command-line client with the following command:
shell> mysql -u root -p

3)Enter your password when prompted. A non-root account can be used as long as the account has privileges to create new databases.

4)Execute the sakila-schema.sql script to create the database structure by using the following command:
mysql> SOURCE C:/temp/sakila-db/sakila-schema.sql;

5)Replace C:/temp/sakila-db with the path to the sakila-schema.sql file on your system.
Note
On Windows, use slashes, rather than backslashes, when executing the SOURCE command.
Execute the sakila-data.sql script to populate the database structure with the following command:
mysql> SOURCE C:/temp/sakila-db/sakila-data.sql;

6)Replace C:/temp/sakila-db with the path to the sakila-data.sql file on your system.
Confirm that the sample database is installed correctly. Execute the following statements. You should see output similar to that shown here.

USE sakila;
Database changed
SHOW TABLES;





