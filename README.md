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

## Project-1 (Basics)

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

## Project-2 (Superstore)

### Dataset Description

| **Column Name**     | **Description**                                                      |
|---------------------|----------------------------------------------------------------------|
| `Row ID`          | A unique identifier for each row in the dataset.                     |
| `Order ID`        | A unique identifier for each order placed.                           |
| `Order Date`      | The date when the order was placed.                                  |
| `Ship Date`       | The date when the order was shipped.                                 |
| `Ship Mode`       | The method used to ship the order (e.g., Second Class).              |
| `Customer ID`     | A unique identifier for each customer.                               |
| `Customer Name`   | The name of the customer who placed the order.                       |
| `Segment`         | The segment of the customer (e.g., Consumer, Corporate).             |
| `Country`         | The country where the order was shipped.                             |
| `City`            | The city where the order was shipped.                                |
| `State`           | The State where the order was shipped.                               |
| `Postal Code`     | The postal code of the shipping address.                             |
| `Region`          | The region where the order was shipped (e.g., South, West).          |
| `Product ID`      | A unique identifier for each product.                                |
| `Category`        | The category of the product (e.g., Furniture, Office Supplies).      |
| `Sub-Category`    | The sub-category of the product (e.g., Bookcases, Chairs).           |
| `Product Name`    | The name of the product.                                             |
| `Sales`           | The sales amount for the order.                                      |
| `Quantity`        | The quantity of the product ordered.                                 |
| `Discount`        | The discount applied to the order.                                   |
| `Profit`          | The profit earned from the order.                                    |

### Concepts and Operations

1. Display Top 5 rows
2. Display Last 5 rows
3. Find Shape of Dataframe
4. Get Information about Dataframe
5. Check Null Values
6. Check for Duplicates
7. Statistics about Dataframe
8. Drop Unnecessary Columns
9. Hypothesis-1: Technology products have the highest profit margin compared to other product categories.
10. Hypothesis-2: The East region has the highest sales compared to other regions.
11. Hypothesis-3: Sales are higher during certain months of the year.
12. Hypothesis-4: Orders with same-day shipping have the lowest rate of returned products.
13. Hypothesis-5: The company's profit is more on weekdays than on weekends.

## Case Study - 1 (Ecommerce Purchases)

### Dataset Description

| Column Name        | Description                                              |
|--------------------|----------------------------------------------------------|
| `Address`          | The address of the purchaser                             |
| `Lot`              | Lot number associated with the purchase                  |
| `AM or PM`         | Indicates whether the purchase was made in the AM or PM  |
| `Browser Info`     | Information about the browser used to make the purchase  |
| `Company`          | The company associated with the purchase                 |
| `Credit Card`      | The credit card number used for the purchase             |
| `CC Exp Date`      | Expiration date of the credit card                       |
| `CC Security Code` | Security code of the credit card                         |
| `CC Provider`      | Provider of the credit card                              |
| `Email`            | Email address of the purchaser                           |
| `Job`              | Job title of the purchaser                               |
| `IP Address`       | IP address from which the purchase was made              |
| `Language`         | Language preference of the purchaser                     |
| `Purchase Price`   | The price of the purchase                                |

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

## Case Study - 2 (San Francisco Salaries)

### Dataset Description

| Column Name        | Description                                                         |
|--------------------|---------------------------------------------------------------------|
| `Id`               | A unique identifier for each employee                               |
| `EmployeeName`     | The name of the employee                                            |
| `JobTitle`         | The job title of the employee                                       |
| `BasePay`          | The base salary of the employee                                     |
| `OvertimePay`      | The overtime pay received by the employee                           |
| `OtherPay`         | Any other type of pay received by the employee                      |
| `Benefits`         | The benefits received by the employee (if available)                |
| `TotalPay`         | The total pay received by the employee (BasePay + OvertimePay + OtherPay) |
| `TotalPayBenefits` | The total pay including benefits received by the employee           |
| `Year`             | The year the pay information is from                                |
| `Notes`            | Any additional notes related to the employee or the pay information |
| `Agency`           | The agency the employee works for                                   |
| `Status`           | The employment status (e.g., PT for part-time)                      |

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

## Case Study - 3 (Adult Income)

### Dataset Description

| Column Name        | Description                                               |
|--------------------|-----------------------------------------------------------|
| `age`              | Age of the individual                                     |
| `workclass`        | Work classification of the individual                     |
| `fnlwgt`           | Final weight, a measure used by the census bureau         |
| `education`        | Education level of the individual                         |
| `educational-num`  | Number of years of education                              |
| `marital-status`   | Marital status of the individual                          |
| `occupation`       | Occupation of the individual                              |
| `relationship`     | Relationship status within the family                     |
| `race`             | Race of the individual                                    |
| `gender`           | Gender of the individual                                  |
| `capital-gain`     | Capital gain of the individual                            |
| `capital-loss`     | Capital loss of the individual                            |
| `hours-per-week`   | Hours worked per week                                     |
| `native-country`   | Country of origin                                         |
| `income`           | Income bracket of the individual (`<=50K` or `>50K`)      |

### Concepts and Operations

1. Import dataset
2. Top 10 rows
3. Bottom 10 rows
4. Shape of dataset
5. Information about dataset
6. Fetch random samples from the dataset (50%)
7. Check null values
8. Plot heatmap on null values
9. Perform data cleaning (replace '?' with 'NaN')
10. Plot heatmap on Null Values
11. Drop all the missing values
12. Check for duplicate data and drop them
13. Statistics about Dataframe
14. Drop the columns educational-num, capital-gain and capital-loss
15. What is the distribution of age column?
16. Find total number of persons having age between 17 to 48 (Inclusive) using Between Method
17. What is the distribution of Workclass column?
18. How many persons having Bachelors or Masters Degree?
19. Replace Income values ['<=50K', '>50K'] with 0 and 1
20. Which Workclass gets the highest salary?
21. Who has better chance to get salary >50K, male or female?
22. Convert workclass column's datatype to category datatype

## Case Study - 4 (Titanic)

### Dataset Description

| Column Name  | Description                                             |
|--------------|---------------------------------------------------------|
| `PassengerId`  | Unique identifier for each passenger.                   |
| `Survived`     | Survival status (0 = No, 1 = Yes).                      |
| `Pclass`       | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).               |
| `Name`         | Full name of the passenger.                             |
| `Sex`          | Gender of the passenger (male or female).               |
| `Age`          | Age of the passenger in years.                          |
| `SibSp`        | Number of siblings or spouses aboard the Titanic.       |
| `Parch`        | Number of parents or children aboard the Titanic.       |
| `Ticket`       | Ticket number.                                          |
| `Fare`         | Passenger fare.                                         |
| `Cabin`        | Cabin number.                                           |
| `Embarked`     | Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton). |

### Concepts and Operations

1. Import Dataset
2. Top 5 rows
3. Bottom 3 rows
4. Find shape of Dataset
5. Information of dataset
6. Statistics of dataset
7. Data Filtering
8. Check null values
9. Drop the column
10. Handle Missing Values
11. Categorical Data Encoding
12. How many people survived and how many died?
13. How many passengers were in First Class, Second Class and Third Class
14. Number of Male and Female passengers
15. Who has better chance of survival Male or Female? 
16. Which passenger class has better chance of survival (First, Second or Third Class)
17. Feature Engineering

## Case Study - 5 (Google Play Store Apps)

### Dataset Description

| **Column Name**   | **Description**                                                                                                     |
|-------------------|---------------------------------------------------------------------------------------------------------------------|
| `App`             | The name of the application.                                                                                        |
| `Category`        | The category under which the app is listed on the Google Play Store.                                                |
| `Rating`          | The user rating of the app (out of 5).                                                                              |
| `Reviews`         | The number of user reviews for the app.                                                                             |
| `Size`            | The size of the application, typically in megabytes (M).                                                            |
| `Installs`        | The number of installations of the app, represented as a range (e.g., "10,000+").                                   |
| `Type`            | The type of the app (Free or Paid).                                                                                 |
| `Price`           | The price of the app in USD (if the app is paid); otherwise, it is 0 for free apps.                                 |
| `Content Rating`  | The age group for which the app is suitable (e.g., "Everyone", "Teen").                                             |
| `Genres`          | The genre or genres under which the app falls (e.g., "Art & Design", "Pretend Play").                               |
| `Last Updated`    | The date when the app was last updated on the Play Store.                                                           |
| `Current Ver`     | The current version of the app.                                                                                     |
| `Android Ver`     | The minimum Android version required to run the app.                                                                |

### Concepts and Operations

1. Top 5 rows
2. Bottom 5 rows
3. Shape of Dataset
4. Information about Dataset
5. Statistics about dataframe
6. Total number of app titles contain astrology
7. Find average app rating
8. Find total number of unique category
9. Which Category gets the highest average rating?
10. Find total number of apps having 5 star rating
11. Find average value of reviews
12. Find total number of Free and Paid Apps
13. Which app has maximum reviews?
14. Display Top 5 Apps having highest reviews
15. Find average rating of free and paid apps
16. Display top 5 apps having maximum installs

## Case Study - 6 (Udemy Courses)

### Dataset Description

| **Column Name**          | **Description**                                                                 |
|--------------------------|---------------------------------------------------------------------------------|
| `course_id`              | Unique identifier for each course.                                              |
| `course_title`           | The title of the course.                                                        |
| `url`                    | Link to the course page on Udemy.                                               |
| `is_paid`                | Boolean value indicating whether the course is paid (True) or free (False).      |
| `price`                  | The price of the course in USD.                                                 |
| `num_subscribers`        | The number of subscribers enrolled in the course.                               |
| `num_reviews`            | The number of reviews the course has received.                                  |
| `num_lectures`           | The total number of lectures included in the course.                            |
| `level`                  | The difficulty level of the course (e.g., All Levels, Intermediate Level).       |
| `content_duration`       | The total duration of the course content in hours.                              |
| `published_timestamp`    | The date and time when the course was published.                                |
| `subject`                | The subject category of the course (e.g., Business Finance).                    |

### Concepts and Operations

1. Top 3 rows
2. Bottom 3 rows
3. Shape of Dataframe
4. Information about Dataframe
5. Statistics about Dataframe
6. Check null values
7. Check for duplicate data and drop them
8. Find out number of courses per subjects
9. For which levels, Udemy Courses provides the courses
10. Display the count of Paid and Free Courses
11. Which course has more lectures (free or paid)?
12. Which courses have a higher number of subscribers Free or Paid?
13. Which Level has the highest number of subscribers?
14. Find most popular course title
15. Display 10 most popular courses as per number of subscribers
16. Find the course which is having the highest number of reviews.
17. Does Price affect number of reviews?
18. Find total number of courses related to python
19. Display 10 most popular python courses as per number of subscribers
20. In which year the highest number of courses were posted?
21. Display Category-wise count of posted subjects (year-wise)

## Case Study - 7 (Top 5000 Youtube Channels)

### Dataset Description

| **Column Name** | **Description**                                                          |
|-----------------|--------------------------------------------------------------------------|
| `Rank`        | The position of the channel in the overall ranking.                      |
| `Grade`       | The grade assigned to the channel based on its performance (e.g., A++, B+). |
| `Channel Name`| The name of the YouTube channel.                                         |
| `Video Uploads`| The total number of videos uploaded by the channel.                     |
| `Subscribers` | The number of subscribers the channel has.                               |
| `Video Views` | The total number of views across all videos on the channel.              |

### Concepts and Operations

1. Display all rows except the last 5 rows using head() method
2. Display all rows except the first 5 rows using tail() method
3. Shape of Dataframe
4. Information about Dataframe
5. Statistics about Dataframe
6. Data cleaning (replace '--' to NaN)
7. Check null values
8. Data cleaning (Rank Column)
9. Data Cleaning (Video Uploads & Subscribers)
10. Data Cleaning (Grade Column)
11. Find Average views for each channel
12. Find out top five channels with maximum number of video uploads
13. Find Correlation Matrix
14. Which Grade has a maximum number of video uploads?
15. Which Grade has the highest average views?
16. Which Grade has the highest number of Subscribers?
17. Which Grade has the highest Video Views?

## Case Study - 8 (IMDB Movie)

### Dataset Description

| **Column**           | **Description**                                                                 |
|----------------------|---------------------------------------------------------------------------------|
| `Rank`             | The ranking of the movie based on a specific criterion.                         |
| `Title`            | The title of the movie.                                                         |
| `Genre`            | The genre(s) of the movie, separated by commas.                                 |
| `Description`      | A brief summary or plot of the movie.                                           |
| `Director`         | The director of the movie.                                                      |
| `Actors`           | The main actors in the movie, separated by commas.                              |
| `Year`             | The year in which the movie was released.                                       |
| `Runtime (Minutes)`| The total runtime of the movie in minutes.                                      |
| `Rating`           | The IMDb rating of the movie (out of 10).                                       |
| `Votes`            | The number of votes the movie received on IMDb.                                 |
| `Revenue (Millions)`| The revenue generated by the movie, in millions of dollars.                   |
| `Metascore`        | The Metascore rating of the movie, a weighted average of reviews from top critics (out of 100). |

### Concepts and Operations

1. Top 3 rows
2. Last 3 rows
3. Shape of Dataframe
4. Information about Dataframe
5. Check missing values
6. Drop all the missing values
7. Check for Duplicate Data
8. Statistics about Dataframe
9. Display Title of the Movie having Runtime >= 180 Minutes
10. In which year there was the highest average voting?
11. In which year there was the highest average revenue?
12. Find the average rating for each director
13. Display Top 10 lengthy movies title and runtime
14. Display number of movies per year
15. Find most popular movie title (highest revenue)
16. Display Top 10 highest rated movie Titles and its Directors
17. Display Top 10 Highest Revenue Movie Titles
18. Find average rating of movies year wise
19. Does Rating affect the Revenue?
20. Classify Movies Based on Ratings [Excellent, Good and Average]
21. Count number of action movies
22. Find Unique values from Genre
23. How many films of each genre were made?

## Case Study - 9 (Forest Fires In Brazil)

### Dataset Description

| **Column**  | **Description**                                                        |
|---------|--------------------------------------------------------------------|
| `year`   | The year of the event (e.g., 1998, 1999, 2000).                    |
| `state`  | The state where the event occurred (e.g., Acre).                   |
| `month`  | The month in which the event took place (e.g., Janeiro).           |
| `number` | The recorded number of events during that time period.             |
| `date`   | The specific date of the event in `YYYY-MM-DD` format.             |

### Concepts and Operations

1. Top 3 rows
2. Last 3 rows
3. Shape of Dataframe
4. Information about Dataframe
5. Check for duplicate data and drop them
6. Check null values
7. Statistics about Dataframe
8. Rename Month Names to English
9. Total number of fires registered
10. In which month maximum number of forest fires were reported?
11. In which year, maximum number of forest fires were reported?
12. In which state maximum number of forest fires were reported?
13. Find total number of fires that were reported in Amazonas
14. Display number of fires that were reported in Amazonas (Year-Wise)
15. Display number of fires that were reported in Amazonas (Day-wise)
16. Find total number of fires that were reported in 2015 and Visualize Data based on each 'month'.
17. Find average number of fires that were reported from highest to lowest (state-wise)
18. Find the state names where fires were reported in 'dec' month

## Case Study - 10 (Heart Disease)

### Dataset Description

| **Column**   | **Description**                                                                                   |
|----------|-----------------------------------------------------------------------------------------------|
| `age`    | Age of the individual.                                                                         |
| `sex`    | Sex of the individual (1 = male, 0 = female).                                                  |
| `cp`     | Chest pain type (0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptomatic). |
| `trestbps` | Resting blood pressure (in mm Hg).                                                          |
| `chol`   | Serum cholesterol level (in mg/dl).                                                            |
| `fbs`    | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false).                                         |
| `restecg` | Resting electrocardiographic results (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy). |
| `thalach` | Maximum heart rate achieved.                                                                  |
| `exang`  | Exercise-induced angina (1 = yes, 0 = no).                                                     |
| `oldpeak` | ST depression induced by exercise relative to rest.                                           |
| `slope`  | The slope of the peak exercise ST segment (0 = upsloping, 1 = flat, 2 = downsloping).          |
| `ca`     | Number of major vessels (0-3) colored by fluoroscopy.                                          |
| `thal`   | Thalassemia (1 = normal, 2 = fixed defect, 3 = reversible defect).                             |
| `target` | Target variable (1 = presence of heart disease, 0 = absence of heart disease).                |

### Concepts and Operations

1. Display Top 5 Rows of The Dataset
2. Check The Last 5 Rows of The Dataset
3. Find Shape of Our Dataset (Number of Rows And Number of Columns)
4. Get Information About Our Dataset
5. Check Null Values In The Dataset
6. Check For Duplicate Data and Drop Them
7. Get Overall Statistics About The Dataset
8. Draw Correlation Matrix 
9. How Many People Have Heart Disease, And How Many Don't Have Heart Disease In This Dataset?
10. Find Count of  Male & Female in this Dataset
11. Find Gender Distribution According to The Target Variable
12. Check Age Distribution In The Dataset
13. Check Chest Pain Type
14. Show The Chest Pain Distribution As Per Target Variable
15. Show Fasting Blood Sugar Distribution According To Target Variable
16.  Check Resting Blood Pressure Distribution
17. Compare Resting Blood Pressure As Per Sex Column
18. Show Distribution of Serum cholesterol
19. Plot Continuous Variables