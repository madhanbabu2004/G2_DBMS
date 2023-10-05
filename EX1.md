# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
create table student(roll_no numeric(10), name varchar(20), age numeric(20),adress varchar(20,phoneno numeric(20)));

### OUTPUT:
![output](./a.png)
![output](./b.png)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
alter table studento add Department varchar(20);

### OUTPUT:
![output](./b.png)


### 3) Drop the student table
 
### SQL QUERY: 
drop table studento;


### OUTPUT:
![output](./c.png)
![output](./d.png)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
truncate table studento;

### OUTPUT:
![output](./e.png)



### 5) Rename the student table to mystudent

### SQL QUERY: 

alter table studento rename to teacher;

### OUTPUT:
![output](./f.png)
