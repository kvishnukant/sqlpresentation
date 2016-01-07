Please do the following:
 
1. Download all the scripts in a folder (for example, c:\myfolder).
2. Login to SCOTT or any other account where you want to create the tables (Emp, Dept, Employees, Departments etc.).
3. Run the hr.sql script from the SQL prompt:
 
SQL> @c:\myfolder\hr.sql
 
 This script will call other scripts automatically.


UTLXPLAN.sql script is used to create the PLAN_TABLE. This helps in finding out the execution plan by running the utlxpls.sql script.