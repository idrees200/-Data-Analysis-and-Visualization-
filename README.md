# Data Analysis and Visualization Project

## Introduction
This project involves data analysis and visualization using various Python libraries. The project is divided into three parts:
- Part A: Analyzing agricultural data.
- Part B: Generating and analyzing student data.
- Part C: Building and evaluating a K-Nearest Neighbors (KNN) regression model.

## Data Description
- **Agricultural Data:** Contains agricultural statistics with attributes such as `Period`, `Data_value`, and `Series_title_2`.
- **Student Data:** A synthetic dataset generated with attributes `Name`, `Age`, `Height`, and `GPA`.

## Part A: Agricultural Data Analysis
1. **Loading and Describing Data:**
    - Load the data from `na-nov2021-agriculture-csv.csv`.
    - Display basic information and statistics about the dataset.

2. **Data Cleaning:**
    - Replace zero values in the `Data_value` column with the column's mean.
    - Drop columns with null values.

3. **Data Visualization:**
    - Bar Graphs:
        - `Period` vs `Data_value`
        - `Series_title_2` vs `Data_value`
    - Line Graph:
        - `Series_title_2` vs `Data_value`
    - Pie Chart:
        - Distribution of `Period`
    - Scatter Plots:
        - `Period` vs `Data_value`
        - `Series_title_2` vs `Data_value`

## Part B: Student Data Analysis
1. **Generating Student Data:**
    - Create a CSV file `Student.csv` with 1000 entries.
    - Each entry includes `Name`, `Age`, `Height`, and `GPA`.

2. **Data Visualization:**
    - Bar Graph:
        - Comparisons of some student statistics.
    - Line Graph:
        - `Age` vs `GPA`

## Part C: KNN Regression Model
1. **Model Training and Evaluation:**
    - Train a KNN regression model to predict GPA based on Age.
    - Evaluate the model using Mean Squared Error (MSE) and Mean Absolute Error (MAE).
    - Visualize the predicted values.

## Dependencies
- Python 3.x
- pandas
- matplotlib
- numpy
- scikit-learn


