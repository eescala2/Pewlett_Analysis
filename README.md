# Pewlett_Analysis
A SQL exercise on retiring employees in a company


### The purpose of this analysis was to determine who would retire in the upcoming few years, and how many postions does the company, Pewlett Hackard, has to fill. Therefore, a generated list of employees eligible for the retirement package was used to find how many jobs will be available after the upcoming retirements on the horizon occur.

### Datasets used were: 
* departments.csv 
* dept_emp.csv 
* dept_manager.csv
* employees.csv
* salaries.csv
* titles.csv

### In Deliverable 1, the starter code for Employee Database Challenge was used as a template to create the retirement_titles. From the employees table, the emp_no, first_name, and last_name columns were taken from the Employees table. From the Titles table, the title, from_date, and to_date columns were retrieved. With both of these tables and their retrieved columns, a new table was created, creating the retirement_titles.csv. Continuing the exercise, using distinct on, we excluse all employees that have already left the company by filtering to_date to equal to '9999-01-1. With this data, we create the unique_titles.csv. 

### In the second deliverable, a query was written to retrieve columns from employees and dept_emp tables, with data filtered with current employees born in 1965 and order by emp_o. 

## Results show: 
* The retirement_tables that we are able to see each eligible retirement employees and how long they have worked for the position. 
* Unique titles table shows the most recent title for employees in that retirement age span.
* Retiring_titles show a majoairty of the individuals at retirement age hold senior titles. 
* Mentorship eligibilituy shows that most employees have senior titles. 
* A calculation of the retiring title shows 57,668/90,398 of employees which equals 64% hold senior titles.
* Conclusion is that close to sixty-four percent of the employees are looking at retirement to fill over five to ten years. Although this will be difficult to fill, an analysis of how the company nurtured this many employees to such a status to continue leading their employees. 
