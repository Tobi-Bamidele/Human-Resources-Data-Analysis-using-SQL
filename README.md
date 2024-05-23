# Human-Resources Data Analysis using SQL

In this project, we are given a csv file containing HR data. We are required to give answers to the following questions.

- What is the gender breakdown of employees in the company?
- What is the race/ethnicity breakdown of employees in the company?
- What is the age distribution of employees in the company?
- How many employees work at the HQ versus remote locations?
- What is the average length of employment for employees who have been terminated?
- What is the distribution of employees across locations by state?


To give answers to the following, we followed these steps using MYSQL Work-Bench
- Data Import
- Data cleaning and Data Transformation
- Then we proceeded to answer the questions

#### Summary of Findings
- There are more male employees
- White race is the most dominant while Native Hawaiian and American Indian are the least dominant.
- The youngest employee is 20 years old and the oldest is 57 years old
- 5 age groups were created (18-24, 25-34, 35-44, 45-54, 55-64). A large number of employees were between 25-34 followed by 35-44 while the smallest group was 55-64.
- A large number of employees work at the headquarters versus remotely.
- The average length of employment for terminated employees is around 7 years.
- A large number of employees come from the state of Ohio.

#### Limitations
- Some records had negative ages and these were excluded during querying(967 records). The ages used were 18 years and above.
- Some term dates were far into the future and were not included in the analysis(1599 records). The only term dates used were those less than or equal to the current date.

For step-by-step details the project including the SQL codes, results and Images, [see here](https://mavenanalytics.io/project/10798)
