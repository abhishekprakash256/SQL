## SQL

A database is a collection of the information that can be of any types.  The databases can be stored in different ways in computer, in paper, in mind etc. Dbms is a system to manage the data, security , backups ,Concurrency etc. The operations performs are as follows CREATE, READ, UPDATE , DELETE. The types of the database are relational databases (table and columns) and non-relational database (key-value store). The database query are request made to system to perform specific actions. 

The primary key defines the row of the database what data is stored , it has to be unique in the database. The key has to be unique to the element. Foreign key defines the relationship in two tables. 

### The SQL

- The sql is a structured query language used for the interaction with the relational database 
- used to design the schema 
- perform administrative tasks (security tasks)
- create and manage databases 
- to perform the CRUDE operations in the db

### Commands 

```bash
mysql --version
sudo mysql -u root
sudo mysql -u root -p  #then enter password
show databases;
```

### Types of the data-types

- INT,DECIMAL (decimal number exact values ), VARCHAR , BLOB (binary large databases), DATE, TIMESTAMP (used for logging)

### Keywords 

- for creation of the table 

```sql
CREATE TABLE 
```

- 