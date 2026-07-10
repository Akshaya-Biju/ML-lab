# House-sales-prediction
# House Price Prediction - Data Exploration using Python

## Overview
This project demonstrates the basic steps involved in exploring a Machine Learning dataset using Python. The housing dataset is loaded, analyzed, and visualized to understand the relationship between the average number of rooms and house prices.

## Objectives
- Read a CSV dataset using Pandas.
- Explore the dataset structure.
- Display dataset information.
- Visualize the relationship between features using a scatter plot.
- Generate statistical summaries.

## Dataset
The project uses a housing dataset (`housing.csv`) containing information such as:
- Avg. Area Income
- Avg. Area House Age
- Avg. Area Number of Rooms
- Avg. Area Number of Bedrooms
- Area Population
- Price
- Address

## Technologies Used
- Python 3
- NumPy
- Pandas
- Matplotlib

## Libraries
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
```

## Steps Performed

1. Imported the required Python libraries.
2. Loaded the dataset using Pandas.
3. Displayed the complete dataset.
4. Displayed the dataset shape.
5. Displayed the first 10 rows.
6. Displayed the last 10 rows.
7. Displayed all column names.
8. Selected the feature:
   - Avg. Area Number of Rooms
9. Selected the target:
   - Price
10. Visualized the data using a scatter plot.
11. Generated the statistical summary using `describe()`.

## Output
The program displays:
- Dataset
- Dataset dimensions
- First and last 10 records
- Column names
- Selected feature values
- Scatter plot between Average Number of Rooms and Price
- Statistical summary of numerical columns

## Sample Visualization
A scatter plot is generated to visualize the relationship between:
- X-axis: Avg. Area Number of Rooms
- Y-axis: Price

## Learning Outcomes
After completing this project, I learned:
- Reading CSV files using Pandas.
- Understanding DataFrames.
- Selecting features and target variables.
- Basic data visualization using Matplotlib.
- Performing exploratory data analysis (EDA).

## Future Improvements
- Apply Linear Regression for prediction.
- Split data into training and testing datasets.
- Evaluate model performance.
- Improve prediction accuracy using additional features.

## Author
**Akshaya Biju**

B.Tech Computer Science and Engineering  
Machine Learning Laboratory
