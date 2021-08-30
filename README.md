## sql-challenge

# Georgia Tech SQL Homework

This project demonstrates understanding of SQL databases and the ability to perform:
1. Data Engineering 
2. Data Analysis

The goal was to analyze employee data for a fictional company using 6 existing CSV data tables. This was broken down into tasks:
1. Inspect the CSVs and sketch out an ERD of the tables
2. Create a table schema for each of the six CSV files
3. Import each CSV file into the corresponding SQL table
4. Complete the following data analysis:
    * List the following details of each employee: employee number, last name, first name, sex, and salary.
    * List first name, last name, and hire date for employees who were hired in 1986.
    * List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
    * List the department of each employee with the following information: employee number, last name, first name, and department name.
    * List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."
    * List all employees in the Sales department, including their employee number, last name, first name, and department name.
    * List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
    * In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

All files (less the README) can be found in the **EmployeeSQL** directory:
* **data** directory contains 6 original CSV data tables
* **Employee_ERD** visualizes the relationship between the tables in the database
* **employee_schema** is the logical collection of database objects used in SQL queries
* **employee_queries** is the list of SQL queries performed on the dataset
