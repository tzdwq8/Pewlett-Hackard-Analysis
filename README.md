# Pewlett Hackard Analysis

## Project Overview
Pewlett Hackard is anticipating that the number of employees that will be retiring will increase in the near future.  This is being referred to as the “silver tsunami”.  This is due to the amount of employees who have a birth date between 1952 and 1955.  This project is aimed at future-proofing the company by determining how many people will be retiring and which positions will need to be filled.  To conduct this analysis a SQL database will need to be created.  Currently the necessary information is being held among six csv files that were created using Excel and VBA.  The final analysis will include a report determining the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program.

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
From the table above we can see that seven titles, encompassing 90,398 positions, will need to be filled as the "silver tsunami” takes effect.  Filling these positions will be a daunting task.  Also, there are only 1,549 employees eligible to mentor incoming employees.  To gain greater insight, the retiring employees by titles are broken out by birth year below.

### 1952
![1952](https://user-images.githubusercontent.com/85590155/127798667-08d7fcbb-79fe-4551-8829-0db9e5e6a3f1.PNG)

### 1953
![1953](https://user-images.githubusercontent.com/85590155/127798745-b04f5fd9-0fa9-472f-91fe-3b7977a1b814.PNG)

### 1954
![1954](https://user-images.githubusercontent.com/85590155/127798904-73a011e9-8217-472e-9539-78184bdb98c0.PNG)

### 1955
![1955](https://user-images.githubusercontent.com/85590155/127798797-c9846cad-2627-4a84-b621-12d8334cbf3e.PNG)

The retiring employees by birth year are relatively flat with 23% in 1952, 25% in 1953, 26% in 1954, and 26% in 1955.  This means if every eligible mentor can mentee roughly 15 employees per year, there will be enough resources to properly onboard.  If this is not possible steps can be taken to lessen the amount of onboarding which include:
- Offering packages to employees to delay retirement.
- Implementing lean strategies to increase productivity.
- Determine if any roles and responsibilities can be outsourced.
