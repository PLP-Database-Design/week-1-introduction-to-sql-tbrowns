# SQL Assignment Week 1

1. State and Explain the components of a DBMS(Database Management System)  

   i. Database Engine:
      Core component responsible for storing, retrieving, and managing data in the database.
      Handles the execution of queries and transactions.
   
   ii. Database Schema:
      The structure of the database, defining tables, fields, relationships, and constraints.
      Acts as the blueprint for how data is organized.
   
   iii. Query Processor:
      Interprets and executes SQL queries.
      Optimizes queries for efficient data retrieval and manipulation.
   
   iv. Transaction Management:
      Ensures the integrity of the database by managing ACID properties (Atomicity, Consistency, Isolation, Durability).
      Handles concurrent access and ensures data consistency.
   
   v. Data Dictionary:
      Metadata repository that stores information about the database structure, such as table definitions, column types, and constraints.
   
   vi. User Interface:
      Provides tools for users to interact with the DBMS, such as command-line tools, graphical interfaces, or APIs.
   
2. What is a relational database? Give 4 examples.
   
   A relational database organizes data into tables (relations) with rows (tuples) and columns (attributes). Each table has a unique key to identify its rows and may have       relationships with other tables.
   Examples: MySQL, PostgreSQL, Oracle Database, Microsoft SQL Server

3. State and Explain three classifications of SQL?
   
   Data Definition Language (DDL):

   Used to define and modify the structure of a database.
   Commands: CREATE, ALTER, DROP, TRUNCATE
   Example: CREATE TABLE students (id INT, name VARCHAR(50));
   
   Data Manipulation Language (DML):

   Used to manipulate data within tables.
   Commands: INSERT, UPDATE, DELETE, SELECT
   Example: INSERT INTO students (id, name) VALUES (1, 'Alice');
   
   Data Control Language (DCL):

   Used to control access to the database.
   Commands: GRANT, REVOKE
   Example: GRANT SELECT ON students TO user1;

   
4. What is the difference between a Primary Key and a Foreign Key?  

   Primary Key:

   Uniquely identifies each record in a table.
   Must contain unique values and cannot have NULL.
   Example: id column in a students table.
   
   Foreign Key:

   Establishes a relationship between two tables.
   Refers to the primary key in another table.
   Example: student_id in a grades table, referencing the id column in the students table.  
   
5. What is an Entity-Relationship Diagram?  
   An Entity-Relationship Diagram is a visual representation of the entities in a database, their attributes, and relationships between them. It is used during database        design to illustrate the structure and interconnections of data.
   
6. What are the advantages of relational databases?
   
   i.    Data Integrity: Maintains accuracy and consistency through constraints and relationships.
   
   ii.   Flexibility: Allows complex queries using SQL.
   
   iii.  Normalization: Reduces redundancy and organizes data efficiently.
   
   iv.   Security: Offers access controls to protect sensitive information.
   
7. State four types of data type used to store data in tables?
   i.    Integer (INT): Stores whole numbers. Example: id INT
   
   ii.   Character/String (VARCHAR, CHAR, TEXT): Stores text data. Example: name VARCHAR(50)
   
   iii.  Date/Time (DATE, TIMESTAMP): Stores dates and times. Example: created_at TIMESTAMP
   
   iv.   Boolean: Stores true/false values. Example: is_active BOOLEAN
   
9. What is the purpose of a database management system (DBMS)?
   
    The purpose of a DBMS is to provide a system for efficiently storing, retrieving, and managing data while ensuring data integrity, security, and accessibility. It           serves as an interface between the database and users or applications, supporting operations like data manipulation, querying, and reporting.


