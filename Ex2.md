# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/057d8315-879d-4bb9-8cce-d2e5c5a930d7)


## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/fcd66cfd-a608-4bd1-8caf-9f8a433e21a1)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/1d2858ac-abd8-4d85-bc61-23c0906ce52d)

### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/15e1ebf0-899f-4589-aee8-0ea4570cefba)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/952f69fc-2a92-4cc6-bbe8-f9f8b27da90d)

### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:

![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/efef081a-dee4-41dc-9c85-7346b9d034f0)

### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/3ac4d2af-ada2-4677-b530-b917949b9b53)

### Q5)	List the names of Clerks from emp table.


### QUERY:


### OUTPUT:


### Q6)	List the names of employee who are not Managers.


### QUERY:


### OUTPUT:


### Q7)	List the names of employees not eligible for commission.


### QUERY:


### OUTPUT:


### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:


### OUTPUT:


### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:


### OUTPUT:


### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:


### OUTPUT:


### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:


### OUTPUT:


### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:


### OUTPUT:

### Q13) Find number of rows in the table EMP

### QUERY:


### OUTPUT:


### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:


### OUTPUT:


### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:


### OUTPUT:
