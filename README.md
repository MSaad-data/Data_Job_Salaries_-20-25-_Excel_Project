# Data_Job_Salaries_-20-25-_Excel_Project

## Data_set Used
 <a href="https://github.com/MSaad-data/Data_Job_Salaries_-20-25-_Excel_Project/blob/main/USA_salaries_2025.xlsx">Dataset view</a>

This project begins with a simple question: **what do data science jobs really pay, and how do these salaries change across different roles and experience levels?** 

To explore this question, this project uses a public dataset from Kaggle titled Latest Data Science Job Salaries 2020–2025. The data was collected by ai-jobs.net Salaries and contains salary records from many companies across the USA.

The full dataset includes many fields, but this project focuses on three key columns: 

work_year 

experience_level

job_title

salary_in_usd

These columns help show how salaries change over time, how job roles differ, and how pay shifts with experience. By looking at these simple fields, anyone can get a clear picture of basic salary patterns in the data world.

The goal of this project is to practice the first steps of **Exploratory Data Analysis (EDA)**. EDA helps break down a dataset into simple parts so that the main patterns become clear. In this project, the focus is on basic EDA tools such as **count,** **average,** **median,** **quartiles,** **minimum,** **maximum,** **mode,** and **standard deviation**. These tools help show how the salaries spread, how they group, and how they differ from one another.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/1778bb80-23ca-4f7d-b8fa-a08d22cd4551" />

### Here is what this dataset reveals through the basic statistics.

The count value shows that the dataset is very large with 93,597 salary records, so the numbers represent a wide job market. The average salary is $157,548, but the median is $146,232. The average is higher than the median, which means some very high salaries pull the average up. This pattern shows that the salary data is right-skewed. A few very high-paying jobs lift the average even though most jobs pay less than that.

The minimum salary is $15,000, and the maximum salary is $800,000. This is a very wide range. This gap signals that the dataset includes many job levels, such as junior, mid-level, senior, and leadership roles. The first quartile is $106,250, and the third quartile is $198,000. This means half of all salaries fall between these two values. This wide middle range shows that salaries in data work change a lot even within common job levels.

The mode is $160,000, which means this is the most common salary in the dataset. This shows that jobs around this pay level appear many times. This aligns with the average being pulled upward, because the most common salary sits near the mid-to-high range.

The standard deviation is $73,649, which is large compared to the average. This shows that salaries move far away from the average in both directions. It confirms that the market has high variety. It also confirms that job roles, experience levels, and salary bands are not consistent. Instead, they spread widely across the dataset.

After completing the basic statistics, the project uses pivot tables to look at two roles: Data Analyst and Data Scientist. The pivot tables show how the salary numbers change for each role when looking at counts, sums, averages, minimums, and maximums. A slicer lets any user switch to other job titles from the dataset to compare results in a quick and clean way.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/6311fee0-13dd-4cbb-b9f3-bb9fd638dfae" />

### Here is what the pivot tables reveal.

The count numbers show that Data Scientist roles (13,848 records) appear more often than Data Analyst roles (9,081 records). This pattern suggests a strong demand for Data Scientist jobs in this dataset.

The average salary for Data Scientists is $156,931, which is much higher than the Data Analyst average of $105,596. This shows that the market rewards more technical roles with higher pay. The difference is strong enough to confirm a pattern, not an accident.

The sum values show that Data Scientists contribute about $2.17B to total salary, while Data Analysts contribute about $958M. This again shows that the dataset contains more high-paying Data Scientist roles.

The minimum values for both roles are low (around $15,000). This usually points to internships, junior roles, or low-pay markets in the dataset. The maximum values are high for both roles ($750K–$774K). These values point to leadership or advanced technical roles.

The slicer opens the full dataset of over 300 job titles, so users can see if these patterns repeat or if some roles behave differently. This allows comparisons across many job types and helps find groups with higher or lower pay patterns.


These steps build a simple path from raw data to clear insights. The work begins with basic EDA, moves to pivot tables, and ends with a general view of salary patterns across common roles in data. The goal is to make the data easy to explore, easy to compare, and easy to understand for anyone interested in data careers.
