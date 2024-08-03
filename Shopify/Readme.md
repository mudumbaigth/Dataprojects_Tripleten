
# Readme

This was the sixth project that I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned about Power BI. The purpose was to review the landscape of apps on the Shopify platform using data scraped from publicly available Shopify websites and to figure out what key factors play into the success of a Shopify app.

## Table of Contents

1. [Raw_data Shopify](https://docs.google.com/spreadsheets/d/1aGlqNupwqhg8wwoChU4xbjOUCtlDUe9A/edit?usp=drive_link&ouid=109133076986057267151&rtpof=true&sd=true) - The original data file provided by TripleTen that was used in the analysis of this project.
2. README - This current page with all relevant information about the project.
3. [Requirements](https://github.com/mudumbaigth/Dataprojects_Tripleten/blob/main/Shopify/Requirements.txt) - A simple .txt file with the provided project requirements as provided by TripleTen.
4. [Reviewer remarks.png](https://github.com/mudumbaigth/Dataprojects_Tripleten/blob/main/Shopify/Reviewer%20remarks.txt) - This is a .png file showing the comments left by my project reviewer.

| Section Title | Description |
| ------------- | ----------- |
| DATA          | Describes the source of data included files tables and fields. |
| Description   | Describes the final product's purpose software format and included visuals. |
| Assumptions   | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Process       | A general outline of how this project formed from start to finish. |
| Findings      | Insights learned from the data analysis. |

## Data

The Excel file provided by TripleTen was public data scraped from the Shopify App Store.
'shopify.xlsx': Excel Workbook containing 4 sheets:
- 'apps': Details of the apps on the Shopify apps marketplace
- 'apps_categories': Join tables to connect apps with categories
- 'categories': Categories of the apps. Each app has multiple categories
- 'reviews': Each review (row) contains information on user opinion about the related app (rating and comment). Also it contains the response from the developer if present.

## Description

- 3 page Power BI Dashboard
- Includes data analysis KPI cards and Charts

## Assumptions

1. Profits from sales are totaling in the negative.
2. There is one or more causes for negative profits directly related to orders and returns.
3. The operations department will need to make changes.

## Process

I first joined the sheets. Then I analyzed data using visualizations to determine what is causing returns. I built a dashboard for monitoring returns. Lastly I created a Tableau story to present my findings.

## Recommendations

1. Returned purchases are the leading cause of declining profits at Superstore.
2. There is a positive correlation between sales and returns.
3. The technology category has the largest return rate.
4. There are several customers who have a return rate of 100%.
5. Each state had different rates of return for different sub-categories.
6. Orders made throughout the year had higher return rates depending on the month.
7. Return rates do not correlate with the amount of product sold some of the lowest selling products had a return rate of 100%.
