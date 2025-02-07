## German Housing Market Analysis & Forecasting

### Project Overview

This project analyzes the German housing market using historical data on house prices, rental trends, vacancy rates, and demand indices. The dataset was cleaned, visualized, and used to build a predictive model for future house prices.

### Dataset Information

- Source: Provided housing dataset

- Key Variables:

 - Year: The year of data collection
  
 - City: The city where data was collected
  
 - Avg_House_Price_€: The average house price in euros
  
 - Avg_Rent_Price_€_per_sqm: The average rental price per square meter
  
 - New_Houses_Built: The number of new houses built in that year
  
 - Population_Growth_%: The percentage growth in population
  
 - Total_Renters_%: The percentage of people renting in the city
  
 - Vacancy_Rate_%: The percentage of vacant houses in the city
  
 - Avg_Household_Size: The average household size
  
 - Rental_Demand_Index: A measure of rental demand

## Project Workflow

### 1️⃣ Data Cleaning & Preprocessing

- Standardized city names (removed extra spaces, capitalized properly)

- Converted price and percentage columns to numeric format

- Handled missing values using:

  - Median imputation for skewed distributions
  
  - Mean imputation for normally distributed values

-Removed duplicate rows

### 2️⃣ Exploratory Data Analysis (EDA)

🔹 Housing Price Trends

- Visualized average house prices over time

- Compared house price variations across cities using boxplots and bar charts

🔹 Rental Market Analysis

- Analyzed rent prices trends over time

- Compared rent prices across different cities

🔹 Vacancy Rate & Rental Demand

- Identified cities with high/low vacancy rates

- Analyzed rental demand index across different cities

- Correlation analysis between house prices, rent prices, population growth, and demand factors

### 3️⃣ Predictive Modeling: House Price Forecasting

- Built a Linear Regression model to predict future house prices based on historical data

- Forecasted house prices for 2025, 2030, and 2035

- Visualized predictions with scatter plots and regression trend lines

#### 4️⃣ Key Findings & Insights

✅ Most Expensive City: Bremen (Avg. House Price: ~€649,267)✅ Most Affordable City: Augsburg (Avg. House Price: ~€507,631)✅ Highest Price Variation: Hanover, Dresden, and Essen✅ Vacancy Rate Trends: Some cities have high vacancy rates, while others show strong rental demand.✅ Future Price Predictions:

- 2025: ~€600,171

- 2030: ~€608,115

- 2035: ~€616,058
