# Databases-and-ERDs

A database schema is a logical representation or blueprint of the structure and organization of a database.
It defines the tables, fields, relationships, constraints, and other elements that make up the database.

- Data Organization: A schema helps in organizing data into tables and defines the relationships between these tables.
- Data Integrity: Schemas allow you to enforce data integrity by defining constraints such as primary keys, unique keys, foreign keys, and check constraints
-  In SQL, you can create tables, define columns and data types, specify constraints, and establish relationships using statements like CREATE TABLE, ALTER TABLE, and others.
-  schemas can be visualized using Entity-Relationship (ER) diagrams, which represent the tables and their relationships graphically.

 Database keys are used to establish relationships between tables and ensure data integrity within a database. 

Primary Key:
A primary key is a unique identifier for each record in a table.

Foreign Key:
A foreign key is a field or combination of fields in one table that refers to the primary key in another table.

Composite Key:
A composite key, also known as a compound key, is a primary key composed of multiple columns

In a relational database, relationships define the associations between tables based on common fields or keys.

One-to-One (1:1) Relationship:
A one-to-one relationship occurs when a single record in one table is associated with at most one record in another table,
and vice versa. In this relationship, the primary key of one table is directly related to the primary key of another table. 

any-to-Many (M:N) Relationship:
A many-to-many relationship exists when multiple records in one table are associated with multiple records in another table
