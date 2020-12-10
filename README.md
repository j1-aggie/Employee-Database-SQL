
# SQL Homework - Employee Database: A Mystery in Two Parts



## Background

It is a beautiful spring day, and it is two weeks since you have been hired as a new data engineer at Pewlett Hackard. Your first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

In this assignment, I designed tables to hold data in the CSVs, imported the CSVs into a SQL database, and answered questions about the data. In other words, performed:

1. Data Engineering

3. Data Analysis


### First I created.

1. A new repository for this project called `sql-challenge`. **Do not add this homework to an existing repository**.

2. Cloned the new repository to computer.

3. Created a directory for the SQL challenge. Used a folder name to correspond to the challenge: **EmployeeSQL**.

4. Added my files to this folder.

5. Pushed the above changes to GitHub.

## Instructions

#### Data Modeling

Inspected the CSVs and sketched out an ERD of the tables. 
Used a tool like [http://www.quickdatabasediagrams.com](http://www.quickdatabasediagrams.com).

![QuickDBD-HMK 9](https://user-images.githubusercontent.com/66078772/95275971-8e4ee980-080f-11eb-9b03-3ffa1892a4d4.png)


#### Data Engineering

* Used the information I had to create a table schema for each of the six CSV files. Specified data types, primary keys, foreign keys, and other constraints.

* Imported each CSV file into the corresponding SQL table. 

#### Data Analysis

Once the database was completed and set up I completed the task below:

1. List the following details of each employee: employee number, last name, first name, sex, and salary.

2. List first name, last name, and hire date for employees who were hired in 1986.

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

## Bonus (Optional)

1. Imported the SQL database into Pandas using SQL Alchemy. 
   ```sql
   from sqlalchemy import create_engine
   engine = create_engine('postgresql://localhost:5432/<your_db_name>')
   connection = engine.connect()
   ```

2. Created a histogram to visualize the most common salary ranges for employees.

![Salary_Frequency](https://user-images.githubusercontent.com/66078772/95275827-32846080-080f-11eb-9797-bfe8b5d87643.png)

3. Created a bar chart of average salary by title.

![Average Salary](https://user-images.githubusercontent.com/66078772/95275897-5ba4f100-080f-11eb-9d72-1187b6d18201.png)

## Epilogue

Searched the employee ID number 499942.

## Submitted 

* An image file of your ERD.

* A `.sql` file of your table schemata.

* A `.sql` file of your queries.

* Created a Jupyter Notebook of the bonus analysis.

* Created and uploaded a repository with the above files to GitHub and post a link on BootCamp Spot.

* Ensured my repository had regular commits (i.e. 20+ commits) and a thorough README.md file


