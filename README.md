# Data Analysis Project - Coupon Acceptance

## Overview

This project explores the acceptance of coupons by drivers in various scenarios. The goal is to understand the factors that influence whether a driver accepts a coupon for a specific destination and type of business. The analysis focuses on different coupon types, demographics, and contextual factors.

## Project Structure

- `data/`: This directory contains the dataset used for the analysis (`coupons.csv`).

- `images/`: Images

## Data Description

The dataset used for this analysis is sourced from the UCI Machine Learning repository and collected via surveys on Amazon Mechanical Turk. It includes information on user attributes, contextual attributes, and coupon attributes.

## Analysis Steps

The project follows these steps:

1. **Data Loading and Cleaning**: The dataset is loaded, and missing or problematic data is addressed. Data cleaning includes handling missing values and duplicates.

2. **Exploratory Data Analysis (EDA)**: Initial exploratory data analysis is performed to understand the distribution of variables, check for patterns, and visualize key insights.

3. **Coupon Acceptance Rate**: The proportion of observations where coupons were accepted is calculated and visualized.

4. **Coupon Type Analysis**: The analysis focuses on specific coupon types (e.g., "CoffeeHouse" and "RestaurantLessThan20") to determine the characteristics of passengers who accept these coupons.

5. **Demographics Analysis**: Demographics such as age, gender, and marital status are explored to understand their influence on coupon acceptance.

6. **Contextual Factors**: Factors like weather, time of day, and destination are considered to determine their impact on coupon acceptance.

7. **Hypotheses and Conclusions**: Hypotheses are formulated based on observations, and conclusions are drawn regarding the characteristics of passengers who accept coupons.

## Dependencies

- Python 3.x
- Libraries: Pandas, NumPy, Matplotlib, Seaborn

## How to Use

1. Clone the repository to your local machine

