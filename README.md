# Project4_Data_Analysis_With_Tableau
## E-Commerce Annual Sales Analysis 
### Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendation)

### Project Overview

This data analysis project aims to provide insights into the performance of the company from year 2019 to 2024. By analyzing and visualizing various aspects of the data to identify patterns and make recommendation for the company base on insight from the data.
	
### Data Sources

Primary dataset used for this analysis which are provided in the files attached to this project are:
-	customer.csv
-	marketing_campaigns.csv
-	transactions.csv
-	web_sessions.csv 

### Tools

- SQL Server: Data extraction 
- Tableau: Creating dashboards and reports

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection,
2. Handling missing values,
3. Data cleaning, formatting, pivoting
4. Putting columns in correct data type and labelling properly

### Exploratory Data Analysis (EDA)

EDA involves exploring the data to answer key questions, such as:

- What is the revenue pattern?
- What can you say about the purchase value?
- What is the outcome of comparing the discounted purchase value to non-discounted?

### Data Analysis

```SQL code
SELECT * from customers
```

### Result/Findings

The analysis results are summarized as follows:
1. Revenue does not appear strongly concentrated in a single product category.
2. Most purchases are relatively low in value, with a small number of very high-value transactions
3. Discount usage appears to not influence purchasing behaviour and spending levels
	
### Recommendations

Based on the analysis, we recommend the following actions:
- Revenue growth may require focusing on customer acquisition or purchase frequency rather than category prioritization.
- Use of discount with adequate advertisement to create awareness will be effective.
- Company should target Beauty product category because that is where purchase value was the highest.

### Limitations

- The data is limited to a sum up in each of the countries involved. There is no detail data about the activities of customers in each country this is a limiting factors as each of the country will differ in many ways. Otherwise, we could explore each country separately
- I had to remove all missing values from the data because they would have affected the accuracy of my conclusions from the analysis. 

### References
	
- [stack Overflow](https://stack.com)
- Statistics for Data Analysis by Using Python:	Dr. Sandeep Kumar (Quality Guru Inc.) - UDEMY
- Complete SQL Bootcamp - Go from Zero to Hero:     Dr. Jose Portilla (Pierian Training) - UDEMY
- Complete Microsoft Power BI:  By Nikolai Schuler, (Ligency, SuperDataScience Team) - UDEMY
- Microsoft Excel – Excel from Beginner to Advanced:	By Kyle Pew - UDEMY
- Tableau A-Z - Hands-on Tableau: By Kirill Eremenko, (SuperData ScienceTeam, Ligency)
- Python for Time Series Data Analysis:		By Dr. Jose Portilla (Pierian Training) - UDEMY
- Complete KoboToolbox (ODK), google form Training:	By Alexander Mtembenuzeni - UDEMY
- Map Academy: Get mapping quickly, with QGIS:	By Professor Alasdair Rae - UDEMY
- Map Academy: Taking QGIS to the next level: 		By Professor Alasdair Rae - UDEMY
- The Supervised Machine Learning Bootcamp:		By 365 Careers - UDEMY
