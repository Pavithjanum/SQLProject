# SQLProject
SQL Project

1. Create department table with following columns.
Dept_id -- Data Type: Integer Primary key,
D_Name --Data Type: NVARCHAR (100) Not null,
Contact_no -- Data Type: Integer Unique
2. Create employee table with following columns
Emp_id -- Data Type: Integer (Primary Key),
Dept_id -- Data Type: Integer (Foreign Key),
Emp_name --Data Type: NVARCHAR (100),
Designation --Data Type: NVARCHAR (100)
Salary -- Data Type: Money
3. ADD A NEW CLOUMN IN DEPARTMENT TABLE
Column – City
Data Type – NVARCHAR (50)
4. CHANGE THE DATATYPE OF SALARY TO CHAR(10) IN EMPLOYEE
Data Type: Change from Money to Char (10);
5. DELETE THE ‘CITY’ COLUMN FROM THE DEPARTMENT TABLE
Column: City
6. RENAME A COLUMN(D_NAME) IN DEPARTENT TABLE to (Dept_NAME)
7. Update the Contact_No of employee who stays in ‘Bangalore’ and id = 6
8. Select given selective columns from employee table.
EMP_ID
EMP_NAME
DESIG
9. Select all details of employee whose salary is greater than 30000.
10. Select details of employee whose salary is between 15000 and 30000
11. Select * from employee who lives in ‘Bangalore’ or ‘New Delhi’
12. Select * from employee who do not stay in cities ‘Bangalore’ and ‘New Delhi’
13. Select details of employee whose name starts with character ‘A’
14. Arrange the details of employee in descending order of their salary.
15. Retrieve the average salary of employee per department.
16. Get the details of Employee( dept_id, Salary) and its average salary whose average salary is greater than 30000
JOINS, STORED PROCEDURE AND VIEW
AIM: Create a Company and a Dept Database and solve the various join operations.
Step1. Create Company Table
Columns
a. Emp_id – Data Type Integer
Name NVARCHAR (50),
Age – Data Type: Integer,
Address – Data Type: NVARCHAR (50),
Salary – Data Type: Numeric (8, 2),
Join date – Date Type: Date)
Step2. Insert below data in Company Table.
Step3. Create Dept Table
Columns
a. Id – Data Type: Integer,
b. Dept -- Data Type: NVARCHAR(20)
c. emp_id – Data Type: Integer
Step4. Insert below data in dept table
17. Query1. Fetch following details for employee with id = 2
Emp_Id
Name
Dept
Dept_Id
Age
Salary
18. Create a stored procedure to fetch following columns from Company and Dept2 table based on a given emp id.
Emp_Id
Name
Dept ,
Dep_Id,
Age
Salary
19. Create a view to fetch the details of employee with following columns
Emp_Id
Name
Dept ,
Dep_Id,
Age
Salary
