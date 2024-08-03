
# Readme

This was the third project that I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned in Business Analytics. The purpose was to analyze the companies' raw transaction logs and turn the event logs into business metrics.
![Business Analytics](https://github.com/mudumbaigth/Dataprojects_Tripleten/blob/main/E-Commerce%20company/Business_Analytics.png)

## Table of Contents

1. [Business Analytics Project](https://github.com/mudumbaigth/Dataprojects_Tripleten/blob/main/E-Commerce%20company/Business%20Analytics%20Project.xlsx) - The original data file provided by TripleTen that was used in the analysis of this project.
2. README - This current page with all relevant information about the project.
3. [Requirements](https://github.com/mudumbaigth/Dataprojects_Tripleten/blob/main/E-Commerce%20company/Requirements.txt) - A simple .txt file with the provided project requirements as provided by TripleTen.

| Section Title | Description |
| ------------- | ----------- |
| DATA          | Describes the source of data included files tables and fields. |
| Description   | Describes the final product's purpose software format and included visuals. |
| Assumptions   | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Process       | A general outline of how this project formed from start to finish. |
| Findings      | Insights learned from the data analysis. |

## Data

The data was one Google spreadsheet file provided by TripleTen:
- user_id: unique customer IDs
- event_type: the type of activity by the user
- category_code: category of the product being viewed or purchased
- brand: company that makes the product
- price: price of the product in USD
- event_date: date of the user activity in YYYY-MM-DD format

## Description

- 8 page spreadsheet
- Includes raw data (Hidden) processed data data analysis and pivot tables.

## Assumptions

1. The "raw_user_activity" sheet accurately reflects all website activity for the relevant timeframe.
2. Missing values or inconsistencies in the data are minimal and can be ignored.
3. The provided data format (columns data types) is correct and consistent.

## Process

I first explored, filtered, and cleaned the data. Then I created and built a conversion funnel. I prepared data for cohort analysis. Calculated retention rates. Lastly I finalized formatting and documentation for the client's readability.

## Results

Conversion Funnel: The conversion rates from shopping cart to purchase is better than the total conversion rates. For calculating total conversion rates I have divided Stage2 by stage 1 and stage 3 by stage 1 as well to compare them to get the number of people who have all the way from view event. For calculating the conversion rates I have divided the Stage2 by Stage 1 and Stage 3 by Stage 2 by doing this we are calculating the number of peolpe who go into the next stage versus the previous stage. In total conversion rates percentage of people who went from view to shopping cart is 29% whereas the percentage of people who went from view to purchase is 10%. In conersion rate the percentage of people who went fromview to shopping cart is 29% whereas the percentage of people who went from shopping cart to purchase is appoximately 36%.

Retention Rates: Retention rates have reduced after the first cohort. The retention rate is the lowest in the third cohort.
