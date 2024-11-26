## **Assignment Answers**

#### 1. State and Explain the components of a DBMS(Database Management System)

A Database Management System (DBMS) is composed of several key components that work together to manage data effectively. These components include:

- **Storage Engine**: The core component that interacts with the file system to store and retrieve data.

- **Query Language**: A standardized language used to perform (CRUD) operations on the data, such as SQL (Structured Query Language).

- **Query Processor**: This interprets user queries and translates them into commands that the DBMS can execute.

- **Optimization Engine**: Enhances performance by optimizing query execution plans and database structure.

- **Metadata Catalog**: A repository that stores metadata about the database objects, helping in managing and accessing data efficiently.

- **Log Manager**: Keeps track of all transactions and changes made to the database, which is essential for recovery and auditing.

- **Reporting and Monitoring Tools**: These tools help in generating reports and monitoring database performance and usage statistics.

### 2. What is a relational database? Give 4 examples.

A relational database organizes data into tables (or relations), which consist of  columns to represent entries and rows to hold values for each column. 
Examples include:
- MySQL
- PostgreSQL
- Microsoft SQL Server
- Oracle Database.


### 3. State and Explain three classifications of SQL?

SQL commands can be classified into four main categories:

- **Data Definition Language (DDL)**: Used to define and manage all database structures, such as creating or altering tables.

- **Data Manipulation Language (DML)**: Deals with the manipulation of data within the database, including operations like insert, update, delete, and select.

- **Data Control Language (DCL)**: Manages permissions and access controls for users within the database.

- **Transaction Control Language (TCL)**: Manages transactions within the database, allowing for operations like commit and rollback.

### 4. What is the difference between a Primary Key and a Foreign Key?

- The primary key uniquely identifies each record in a table, while the foreign key establishes a link between two tables maintains referential integrity by linking records across tables.

- The primary key must contain (not null) unique values.
- Foreign can contain duplicate values and accept null values

### 5. What is an Entity-Relationship Diagram?

An Entity-Relationship Diagram (ERD) is a visual representation of the entities within a database and their relationships. It consists of:

- **Entities**: Objects or concepts represented as tables (e.g., Customer, Order).

- **Attributes**: Properties or characteristics of entities (e.g., Customer Name, Order Date).

- **Relationships**: Connections between entities that define how they interact with each other (e.g., one customer can place many orders).

### 6. What are the advantages of relational databases?

- **Data Integrity**: They ensure accuracy and consistency through constraints like primary keys and foreign keys.

- **Flexibility**: Changes to data structures can be made without affecting existing data.

- **Complex Queries**: They support complex queries that allow for sophisticated data retrieval.

### 7. State four types of data type used to store data in tables?

- **Integer**: For whole numbers.
  
- **Varchar**: For variable-length strings.
  
- **Date/Time**: For storing date and time values.
  
- **Boolean**: For true/false values. 


### 8. What is the purpose of a database management system (DBMS)?  

The primary purpose of a DBMS is to provide a systematic way to create, retrieve, update, and manage data in databases. It facilitates, data organization, efficient querying, data integrity, security management and  backup and recovery facilities.
