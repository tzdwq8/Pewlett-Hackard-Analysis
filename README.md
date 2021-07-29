# Pewlett Hackard Analysis

## Project Overview
Pewlett Hackard is anticipating that the number of employees that will be retiring will increase in the near future.  This is being referred to as the “silver tsunami”.  This is due to the amount of employees who have a birth date between 1952 and 1955, while being hired between 1985 and 1988.  This project is aimed at future-proofing the company by determining how many people will be retiring and which positions will need to be filled.  To conduct this analysis a SQL database will need to be created.  Currently the necessary information is being held among six csv files that were created using Excel and VBA.  The final analysis will include a report determining the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program.

## Resources
- Data Source: employees.csv, departments.csv, dept_emp.csv, dept_manager.csv, titles.csv, salaries.csv
- Software: pgAdmin 4 5.2. PostgreSQL 11.12, Quick DBD

## Results
The two deliverables were tables (below) which illustrated the number of retiring employees by titles and identified employees who are eligible to participate in a mentorship program.

### Retiring Employees

![retiring_titles](https://user-images.githubusercontent.com/85590155/127409097-c1d4e18f-2cd9-44bd-b8cd-6138bdd9ea5a.PNG)

### Mentorship Eligibility (sample)

![mentorship_eligibility](https://user-images.githubusercontent.com/85590155/127409266-12ca34da-ff17-4616-9a7f-c7df2c014283.PNG)

### Analysis
- Senior positions (29,414 Senior Engineers and 28,254 Senior Staff) are the titles most affected. This points to a large knowledge drain/skill gap that needs to be addressed.
- 40,497 of the retiring titles have the title of Staff.  This is a generic title which will need to be broken down further to understand the roles and responsibilities which need to be filled.
- There are 1,549 employees that have mentorship eligibility, while there are 90,398 retiring employees.  This points to a potential deficiency when developing onboarding / training programs.
-  There are 90,398 retiring employees vs a total of 300,024 employees.  This represents 30% reduction in workforce which means a multi prong solution will need to be employed (i.e. onboarding, succession planning, productivity gains, outsourcing, etc.)

## Summary

