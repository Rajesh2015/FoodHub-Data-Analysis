# FoodHub Data Analysis Project

## Project Overview

FoodHub is a food aggregator company that offers access to multiple restaurants through a single smartphone app. This app allows customers to place orders, which are then delivered by FoodHub’s delivery personnel. The goal of this project is to analyze the order data to understand the demand for different restaurants and improve customer experience.

## Objective

The objective of this project is to analyze the stored data of food orders to answer key questions posed by the Data Science team. The insights gained will help FoodHub enhance its business operations and customer satisfaction.

## Data Description

The dataset contains information about various food orders made by registered customers on the FoodHub platform. The data dictionary is as follows:

- **order_id**: Unique ID of the order
- **customer_id**: ID of the customer who ordered the food
- **restaurant_name**: Name of the restaurant
- **cuisine_type**: Cuisine ordered by the customer
- **cost_of_the_order**: Price paid per order
- **day_of_the_week**: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
- **rating**: Rating given by the customer out of 5
- **food_preparation_time**: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
- **delivery_time**: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information.

## Key Questions

The Data Science team has provided the following key questions that need to be answered through data analysis:

1. Which restaurants have the highest demand?
2. What are the most popular cuisines?
3. How does the order cost vary across different days of the week?
4. What is the average rating for different restaurants?
5. How does the food preparation time vary across different restaurants?
6. How does the delivery time vary across different days of the week?

## Methodology

1. **Data Cleaning**: Ensure the dataset is clean and free from inconsistencies.
2. **Exploratory Data Analysis (EDA)**: Perform EDA to understand the data distribution and identify patterns.
3. **Visualization**: Use visualization techniques to illustrate key findings.
4. **Statistical Analysis**: Conduct statistical analysis to answer the key questions.

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Results

The results of the analysis will be documented in a separate report, highlighting insights and recommendations for FoodHub.

## Conclusion

By analyzing the order data, FoodHub aims to better understand customer preferences and improve its service offerings. This project will provide actionable insights that can drive business decisions and enhance customer satisfaction.

## How to Run the Analysis

1. Clone the repository.
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the analysis script: `python analysis.py`

## Contact

For any questions or suggestions, please contact the Data Science team at FoodHub.

