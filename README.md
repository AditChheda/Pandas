# Pandas
This repository contains a collection of my projects and exercises using the Pandas library in Python. 

These projects showcase various data manipulation, analysis, and visualization techniques using Pandas. 
<br> 
Each project is aimed at solving real-world data problems and exploring different datasets.

### Contents

- **Data Cleaning:** Scripts for cleaning and preprocessing raw data.
- **Data Analysis:** Notebooks with exploratory data analysis (EDA) and descriptive statistics.
- **Data Visualization:** Examples of creating insightful visualizations using Pandas and other libraries like Matplotlib and Seaborn.
- **Case Studies:** In-depth case studies on specific datasets, including detailed analysis and insights.
- **Practice Exercises:** Smaller exercises and practice problems to sharpen Pandas skills.

## Project-1

This project demonstrates various fundamental operations using the Pandas library in Python. 
<br>
Below is a detailed list of concepts and operations covered in this project.

### Dataset Description

The dataset contains information about students, including their names, marks, and gender. 
<br>
It is represented in the form of a dictionary with three keys: `Name`, `Marks`, and `Gender`. 
<br>
Each key maps to a list of corresponding values. 

### Concepts and Operations

1. Demonstrates how to initialize a DataFrame using a dictionary.
2. Shows how to retrieve the first few rows of the DataFrame.
3. Shows how to retrieve the last few rows of the DataFrame.
4. Retrieves the dimensions (number of rows and columns) of the DataFrame.
5. Accesses specific rows and columns of the DataFrame.
6. Provides a concise summary of the DataFrame, including data types and non-null values.
7. Identifies null (missing) values within the DataFrame.
8. Counts the number of null values in each column of the DataFrame.
9. Generates descriptive statistics.
10. Extends the description to include categorical data.
11. Extracts unique values from the 'Gender' column.
12. Counts the unique values in the 'Gender' column.
13. Tallies occurrences of unique values within the 'Gender' column.
14. Filters and counts students whose marks fall within the specified range.
15. Computes the average marks of students.
16. Utilizes the `apply` method to perform operations along the axis of the DataFrame.
17. Employs the `map` function for element-wise transformations of a Series.
18. Removes specified column(s) from the DataFrame.
19. Retrieves the column names of the DataFrame.
20. Retrieves the index (row) names of the DataFrame.
21. Sorts the DataFrame based on the 'Marks' column.
22. Sorts the DataFrame based on the 'Marks' and 'Gender' columns.
23. Filters and retrieves the names and marks of female students.

## Case Study - 1

### Dataset Description

- `Address`: The address of the purchaser.
- `Lot`: Lot number associated with the purchase.
- `AM or PM`: Indicates whether the purchase was made in the AM or PM.
- `Browser Info`: Information about the browser used to make the purchase.
- `Company`: The company associated with the purchase.
- `Credit Card`: The credit card number used for the purchase.
- `CC Exp Date`: Expiration date of the credit card.
- `CC Security Code`: Security code of the credit card.
- `CC Provider`: Provider of the credit card.
- `Email`: Email address of the purchaser.
- `Job`: Job title of the purchaser.
- `IP Address`: IP address from which the purchase was made.
- `Language`: Language preference of the purchaser.
- `Purchase Price`: The price of the purchase.

### Concepts and Operations

1. Displaying the first 10 rows of the dataset.
2. Displaying the last 10 rows of the dataset.
3. Checking the datatype of each column in the dataset.
4. Identifying null values in the dataset.
5. Getting the number of rows and columns in the dataset.
6. Finding the highest and lowest purchase prices in the dataset.
7. Calculating the average purchase price.
8. Counting the number of people who have French as their language preference.
9. Identifying job titles that contain the word "Engineer".
10. Locating the email of the person with the specified IP address.
11. Counting how many people have Mastercard as their credit card provider and made a purchase above 50.
12. Locating the email of the person with the specified credit card number.
13. Counting how many people made purchases in the AM and PM.
14. Counting how many people have a credit card that expires in 2020.
15. Identifying the top 5 most popular email providers among the purchasers.

## Case Study - 2

### Dataset Description

- `Id`: A unique identifier for each employee.
- `EmployeeName`: The name of the employee.
- `JobTitle`: The job title of the employee.
- `BasePay`: The base salary of the employee.
- `OvertimePay`: The overtime pay received by the employee.
- `OtherPay`: Any other type of pay received by the employee.
- `Benefits`: The benefits received by the employee (if available).
- `TotalPay`: The total pay received by the employee (BasePay + OvertimePay + OtherPay).
- `TotalPayBenefits`: The total pay including benefits received by the employee.
- `Year`: The year the pay information is from.
- `Notes`: Any additional notes related to the employee or the pay information.
- `Agency`: The agency the employee works for.
- `Status`: The employment status (e.g., PT for part-time).

### Concepts and Operations

1. Display the first 10 rows of the dataset to get an overview of the data.
2. Display the last 10 rows of the dataset to see the end portion of the data.
3. Get the number of rows and columns in the dataset using the `.shape` attribute.
4. Use the `.info()` method to get a concise summary of the dataset.
5. Check for missing values in the dataset using the `.isnull().sum()` method.
6. Remove the 'ID', 'Notes', 'Agency', and 'Status' columns using the `.drop()` method.
7. Get descriptive statistics of the dataset using the `.describe()` method.
8. Find the top 5 most frequent employee names using the `.value_counts()` method on the 'EmployeeName' column.
9. Determine the number of unique job titles using the `.nunique()` method on the 'JobTitle' column.
10. Find the number of job titles containing the word 'Captain' using the `.str.contains()` method on the 'JobTitle' column.
11. Filter and display all employee names who work in the fire department using the `.str.contains()`.
12. Calculate the minimum, maximum, and average base pay using the `.min()`, `.max()`, and `.mean()` methods on the 'BasePay' column.
13. Replace 'Not Provided' values in the 'EmployeeName' column with `NaN` using the `.replace()` method.
14. Remove rows that have 2 or more missing values.
15. Retrieve the job title of the employee named 'ALBERT PARDINI' by filtering the dataset.
16. Calculate the total pay including benefits for 'ALBERT PARDINI'.
17. Identify and display the name of the person with the highest base pay.
18. Calculate the average base pay of all employees for each year using the `.groupby()` method.
19. Calculate the average base pay of all employees for each job title using the `.groupby()` method.
20. Calculate the average base pay of employees with the job title 'ACCOUNTANT'.
21. Identify the top 5 most common job titles using the `.value_counts()` method on the 'JobTitle' column.