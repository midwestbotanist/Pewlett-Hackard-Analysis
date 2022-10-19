# Pewlett-Hackard-Analysis
## **Overview of Project**

Pewlett Hackard is an employer to thousands of employees. Due to an aging population of employees, the company needs to prepare retirement packages for soon to retire employees while also knowing which positions they will be need to recruit for and fill as their current employees retire.

In order to future-proof Pewlett Hackard, this analysis needs to:
    1) Determine which employees will be retiring in the next few years
    2) Determine both how many and which positions will need to be filled
    3) To do steps 1 and 2, upgrade the companies analyzing methods to incorporate SQL to more effectively crunch the data from 6 CSV files currently holding all of the employee information

## **Results/Analysis**

### A) Overview

In order to put gather our data into tables, first an Entity Relationship Diagram (ERD) was created to visualize how the six CSV files of data relate together and how they will be used to combine/extract the information.

![EmployeeDB](https://user-images.githubusercontent.com/101941048/196597391-ae81c6fe-1f11-425c-9dda-b8d0e2bd8aac.png)


### B) Results:

    1) Over 133,776 rows of employees are returned from our query for employees soon to retire, however this does not exclude duplicate information for employees who have worked multiple positions
    2) Once the duplicate information has been removed, there are 90,398 employees set to retire and they each hold one of seven possible job titles
    3) The most held job titles are Senior Engineer and Senior Staff, the least held is Manager
    
![Screenshot 2022-10-18 233609](https://user-images.githubusercontent.com/101941048/196599378-9a089f3e-400e-4960-9aed-5290206cca19.png)

    4) Of current employees, 1,549 are eligible for partaking in the company mentorship program

## Summary:

Currently over half of the employees at Pewlett Hackard are set to retire in the next few years, something which would be devastating to an ill prepared company. Luckily, due to conducting this analysis early, the results can be used to help guide the company as it looks to mentor younger employees to fill roles - a valuable approach as it is much more cost effective to train current employees over hiring new employees. And yet, also this prepares the company to determine which roles will need to be recruited for ahead of time to give adequate preparation to find good future employees.

## Resources
**Data Sources:** departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv
**Software:** Excel, Quick DBD, PostgreSQL, pgAdmin
