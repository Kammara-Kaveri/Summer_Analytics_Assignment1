# Summer_Analytics_Assignment1
Assignment contains an interesting set of questions to get a basic understanding of pandas and data visualization libraries.


## Overview
This project analyzes the Cars.csv dataset using Python and Pandas. The dataset contains car details like mpg, horsepower, weight, etc., across various years and origins. The assignment includes tasks to manipulate and analyze the data, such as calculating metrics, filtering, and aggregating.
Dataset

**File**: Cars.csv
**Columns**: mpg, cylinders, displacement, horsepower, weight, acceleration, model_year, origin, name
**Rows**: 406 cars from 1970 to 1982, sourced from various regions (usa, japan, europe).

## Tasks Completed

-Display the shape of the DataFrame: (406, 9).
-Set the name column as the index.
-List unique mpg values.
-Create a column hp_to_weight (horsepower/weight) and set it as the index.
-Find the car with the highest horsepower: pontiac catalina (225.0).
-Count cars with mpg ≥ 35: 26 cars.
-Find the most common origin for cars with horsepower > 100 and weight < 3000: europe.
-Calculate the mean acceleration of cars from Japan: 15.99 (rounded to 2 decimals).
-Identify the year with the highest average mpg: 1982 (average 31.58).

## Requirements

Python 3.x
Pandas (pip install pandas)

## How to Run

-Clone the repository: git clone <https://github.com/Kammara-Kaveri/Summer_Analytics_Assignment1>
-Place Cars.csv in the project directory.
-Run the Python script: python cars_analysis.py
-Ensure all tasks are in a single script or run each task’s code individually.


## Files

**Cars.csv**: Dataset file
**Assignment_1.py**: Python script with all tasks (create this file with the code from each task)
**README.md**: This file
