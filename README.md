# Data Engineering. Data Modeling Practice.
Simple Data Modeling Practice with postgreSQL and python in Jupyter notebook

For this project I practiced creating an ER diagram then creating and populating a database in postgreSQL using python.

First I created an Entity relationship diagram for fictional Employees data that I created myself. This consisted of creating tables and finding primary and foreign keys for each table as well as the joining relationships. This is shown in the ER diagram.

I then used python to create a postgreSQL database and manually created the tables. Then populated with data.
Next I did this again with another dataset. However this dataset was already in an excel csv file. I used python to create a database for this and load the data from this dataset into the database in postgreSQL. 

The data for each dataset is now ready for cleaning and analysis!

## ER Diagram
A fictional ER diagram I've created of an Employees database. 

### What is a data model?
A data model organizes elements of data and standardizes how they
relate to one another and properties of real-world entities.

### Why is data modeling important?
* Organizes data across multiple tables to more easily maintain tables
* Organizes data and determines later data use
* Begin prior to build out apps, business logic, and analytical model
* It is an iterative process

### Relational Data Models
* Organizes data into tables with a unique key identifying each row
* Structure of how data looks.
### Relational Database
* Digital database based on relational model of data
* A software system used to maintain relational database is a relational database management system (RDBMS)
* MySql, PostgreSql, Oracle, MSSQL, etc

### Basics of relational database
Database/Schema is a collection of tables  
Tables/Relations are a group of rows sharing the same labeled elements

### Advantages of using a Relational Database
* Ease of use - SQL
* Ability to join tables
* Ability to do aggregations and analytics
* Smaller data volumes
* Flexibility of Queries
* ACID transactions - Data Integrity

### When not to use Relational Database
* Large amounts of data
* Need to be able to store different data types formats
* Need a flexible schema
* Need high availablity
* Need horizontal scalibility



