
# Readme

This was the first project I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned about Advanced Spreadsheets. This project is about analyzing Airbnb listings in Manhattan NYC to help a client decide what type of vacation rental property to invest in.
![Vacation Rental](https://github.com/mudumbaigth/Dataprojects_Tripleten/blob/main/Vacation%20Rental%20Market/vacation%20rental.png)

## Table of Contents

1. [Source Data](https://github.com/mudumbaigth/Dataprojects_Tripleten/blob/main/Vacation%20Rental%20Market/Source%20Data.xlsx) - The original data file provided by TripleTen that was used in the analysis of this project.
2. README - This current page with all relevant information about the project.
3. [Requirements](https://github.com/mudumbaigth/Dataprojects_Tripleten/blob/main/Vacation%20Rental%20Market/Requirements.txt) - A simple .txt file with the provided project requirements as provided by TripleTen.
4. [Reviewer remarks.png](https://github.com/mudumbaigth/Dataprojects_Tripleten/blob/main/Vacation%20Rental%20Market/Reviewer%20remarks.png) - This is a .png file showing the comments left by my project reviewer.

| Section Title | Description |
| ------------- | ----------- |
| DATA          | Describes the source of data included files tables and fields. |
| Description   | Describes the final product's purpose software format and included visuals. |
| Assumptions   | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Process       | A general outline of how this project formed from start to finish. |
| Findings      | Insights learned from the data analysis. |

## Data

The data was one Google spreadsheet file provided by TripleTen:
- 'nyc_airbnb_data.csv': each row corresponds to one listing on AirBnB in September 2022
- 'data_dictionary': summary of field titles seen in the file and its data type
- 'listings': uniquely listings available with all available data
- 'calendar': listings with upcoming availabilities and date-type data

## Description

- 17 page spreadsheet
- Includes raw data (Hidden) processed data data analysis pivot tables and a bar chart.

## Assumptions

1. The "raw_user_activity" sheet accurately reflects all website activity for the relevant timeframe.
2. Missing values or inconsistencies in the data are minimal and can be ignored.
3. The provided data format (columns data types) is correct and consistent.

## Process

I first explored, filtered, and cleaned the data. Then I created aggregations and pivot tables to determine the type of properties that should be targeted. I performed calculations, pivot tables, and charts to determine occupancy and estimated revenue. I went a step further and chose to do an optional analysis to determine what attributes are important for a vacation rental. Lastly I finalized formatting for the client's readability.

## Recommendations

Based on the analysis the Lower East Side is most suitable for investment with an estimated annual revenue of $63,084.39

I have arrived at this conclusion by calculating the AveragePrice for Lower East Side which is $315.35

Average occupancy rate is 54%

Annual Revenue = 365 * 54% * $315.35 = $63,084.39
