# Pewlett-Hackard-Analysis

Pewlet-Hackard has asked us to determine how many employees will be retiring soon from the company. They are preparing for this “silver tsunami” by determining how many employees will leaving each department, and what position that they currently hold. The company would like to hold on to some of these retirees to be a part of mentorship program for the new employees coming in to replace them, as part-time workers teaching them all the in and outs around the company. 

## Resources
  - Data Sources: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv
  - Software: Postgres, pgAdmin, QuickDBD

We took several steps to compile these lists for Pewlett Hackard, such as making a flow chart on QuickDBD to help determine which parts of information are connected within each chart. After the connections were determined, we used different types of joins to cut and copy tables into new tables, and sort through that data by filtering out what information is not needed to get the proper tables asked for by Pewlett-Hackard.

Flow chart:
![Table1](https://github.com/jugvirpabla/Pewlett-Hackard-Analysis/blob/master/EmployeeDB.png)

Sample Code Snippet:
![Picture1](https://github.com/jugvirpabla/Pewlett-Hackard-Analysis/blob/master/ME_Code_Sample.png)

It was determined that thousands of employees are Pewlett-Hackard will be retiring soon, and many of them could continue to stay with the company and be mentors to the new incoming employees. This a great starting point for management to figure how they will transition the retirees to different roles, or leave the company. There could be more analysis done to find out when the exact months the employees could retire to have potential new employees hired and into training by that time.
