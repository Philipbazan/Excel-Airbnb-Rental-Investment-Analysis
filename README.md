# Excel-Airbnb-Rental-Investment-Analysis
[Project Link](https://docs.google.com/spreadsheets/d/1oRqedcTyJUbjffimmSklRnZwha5YC1Ka8rg4Oml9JQA/edit?usp=sharing)

## Introduction

Which airbnb rentals in the New York Area present the most profitable investment opportunity?

## Objective

Clean and analyze dataset of NYC Airbnb data and use pivot tables to perform analyses on Top 10 Popular Neighborhoods, Bedroom # Popularity, Average Occupancy, Weekday Rental Preference, and ultimately combine these analyses to determine the Annual property revenue estimate and propose specifically which apartments are most profitable for an investment opportunity.

## 1.0 Explore and Filter Data

1.1: Data Cleaning

 • Removed Long-Term Rentals

 • Filtered Data for Short-Term Rentals

 • Improved Relevance by Eliminating Long-Term Listings

 • (Only Short-Term Rentals with 7 Days or Less Minimum Night Requirements Incorporated)

1.2: Data Refinement Based on Reviews

 • Removed Listings with No Reviews in the Last 12 Months

 • Excluded Inactive Listings

1.3: Standardized Neighborhood Data

 • Created "neighborhood_clean" Column

 • Enhanced Data Consistency by Standardizing Neighborhood Labels

 • Determine Targeted Property Types

## 2.0: Identify Top Vacation Rental Neighborhoods

2.1 Built Pivot Table to Determine Popular Neighborhoods

 • Highlighted Top 10 Neighborhoods with Maximum Reviews

![Top 10 Popular Neighborhoods by Reviews](https://github.com/user-attachments/assets/d089ea66-9c78-403a-a0a3-995a5f3fd30e)

2.2: Analyze Property Size Preferences and Distribution

 • Built Pivot Table to Compare Bedroom Preferences by Displaying Size Distribution

 • Investigated Property Size Variation Within Top 10 Neighborhoods

 • Identified Most Popular Number of Bedrooms for Rentals

![# of bedroom popularity](https://github.com/user-attachments/assets/5d864a0b-825c-4d81-8c09-40cad6d8c631)
![Bedroom Popularity by Neighborhood](https://github.com/user-attachments/assets/e8281ecd-0c8a-4feb-8404-9cd63c3a9b5b)

## 3.0: Calculate Occupancy Rates

3.1: Create New Columns

 • Introduce "Occupied" and "Day_of_Week" Columns

 • Created Columns for Occupancy and Day of the Week

 • Laid Foundation for Occupancy Rate Calculation

3.2: Determine Average Occupancy

 • Built Pivot Table for Average Occupancy

 • Analyzed Listing-Level Occupancy Rates

3.3: Explore Weekly Occupancy Variations

 • Built Pivot Table to Analyze Weekly Occupancy

 • Identified Days of the Week with Highest Occupancy Rates

![Weekday Occupancy Preference](https://github.com/user-attachments/assets/9f25a5f9-a83d-4bb0-8adc-b29aea529f1e)

## 4.0: Estimate Revenue for Investment Properties

4.1: Refine Data for Relevant Neighborhoods

 • Removed Listings Outside Top 10 Neighborhoods

 • Focused Analysis on High-Potential Areas

4.2: Filter for Quality Listings

 • Removed Listings with Rating Below 4

 • Ensured Quality Standards for Revenue Estimation

4.3: Target Specific Property Types

 • Filtered for 1 Bedroom Listings

 • Narrowed Down Property Type for Accurate Revenue Estimates

4.4: Calculate Estimated Annual Revenue

 • Built Pivot Table for Revenue Calculation

 • Calculated Annual Revenue for Targeted Listings

![Average Revenue Estimate](https://github.com/user-attachments/assets/c46837e2-7a2b-4bf6-989c-5e4bd71e3177)
