# Ex. No: 4 Creating Procedures using PL/SQL

### AIM: To create a procedure using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

### Program:
1) Creating table:
      create table employee(empid number, empname varchar(10), dept varchar(10), salary number);
2) Creating Procedure:
       create or replace procedure employee_data as
    begin
    insert into employee(empid,empname,dept,salary) values (1,'Sita','HR',70000);
    insert into employee(empid,empname,dept,salary) values (2,'Anjali','MD',95000);
    insert into employee(empid,empname,dept,salary) values (3,'Chandhini','Finance',80000);
    commit;
    end;
    /
 begin
    employee_data;
    end;
    /

### Output:
![image](https://github.com/dineshgl/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/103019882/8be68a91-c4ec-4139-8d1a-b7facd0b57fc)
![image](https://github.com/dineshgl/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/103019882/4fa4aa74-6bbc-45d5-adec-18d901a3ffd4)


### Result:
Hence the procedure using pl/sql is created successfully.
