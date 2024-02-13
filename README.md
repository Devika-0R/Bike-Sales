# Sattionary Sales Analysis
----
## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

----

## Project Overview

This data analysis project aims to provide insights into sales of an stationary manufacturing company over past year. By analyzing various aspects of the stationary sales data, I seek to identify trends, make data driven recommendation, and gain the deeper understanding of the company's recommendation.

< AxesSubplot:xlabel='Rep'>

![Screenshot 2024-02-13 223822](https://github.com/Devika-0R/Stationary_sales/assets/153339996/e09eb6e0-914e-45ea-96ae-aa0a1dd40508)

## Data Sources

Sales Data: The primary dataset used for this analysis is "Stationary sales.csv" file, containing detailed information about each sale made by the company.

## Tools Used

- Excel - Data cleaning
- PowerBI - Data analysis, Creating report

## Data cleaning / Data preparation

In the initial data preparation phase, I performed the folllowing tasks:
 1. Data loading and inspection.
 2. Handling missing values.
 3. Data cleaninig and formatting.

## Explotary data analysis
EDA involved exploring the sales data to answer key questions. such as,

- Which products are top sellers?
- What are the peak sales period?
- What is the overall sales?

## Data Analysis
Included some interesting measures and calculations such as;


| Most Sold Rep = 
{
var A = Sales
var B = MAXX(A,Sales[Units])
var C = FILTER(A, Sales[Units]=B)
var D = MAXX(C,Sales[Rep])
Return D
}|



## Result

The analysis results are summarized as follows:
1. The company's sales have been steadily increasing over the past year, with a noticeable peak during the exam period (School days).
2. Product item "Binder" is the best selling product in terms of sales and revenue.

## Recommendations

Based on the analysis, I recommend the following actions:
- Invest in marketing and promotios during peak sales season to maximize revenue.
- Focus on expanding and promoting products "Binders" and "Pencil set".

## Limitations

I had to remove all zero values from sales and units sold columns because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers even after the omissions but even then we can still see that there is a positive correlation sales and unit cost.

## References

1. Excel for cleansing
2. [Excel](www.microsoft.com)




