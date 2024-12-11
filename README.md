# Machine Learning Regression Oil

## Project Description
Training a regression model for choosing the best region to develop new oil wells.

This notebook performs a brief EDA in 3 datasets for 3 different regions. 

To work with 3 datasets, define functions for split and scaling, fit and predictions, calculate average predictions and RMSE e RMSE.

Calculates the profit of the best wells in each region. Performs bootsrapping to calculate the average profit, confidence interval and risk of loss.

The data is synthetic and does not include any contract details or well characteristics.

## Dataset
- id* — unique oil well identifier

- f0, f1, f2* — three point characteristics (their specific meaning is not important, but the characteristics themselves are significant)

- product* — volume of reserves in the oil well (thousands of barrels).

## Objectives
- Perform exploratory data analysis.
- Encode categorical variables.
- Scale the data.
- Train a regression model.
- Calculate average predictions and RMSE.
- Calculate the profit of the best wells in each region.
- Perform bootstrapping to calculate the average profit, confidence interval and risk of loss.

## Tools and Libs used
- Python: Main language used for analysis.
- Pandas: Library for data manipulation and analysis.
- NumPy: Library for numerical operations.
- Matplotlib and Seaborn: Libraries for data visualization.
- Scikit-learn: Library for machine learning.

## Methodology
#### EDA
- Import libraries.
- Load the dataframes.
- Perform exploratory data analysis using summary statistics and data visualization.
#### Preprocessing
- Identify and treat missing values.
- Identify and treat outliers.
- Scale the data.
#### Modeling
- Train a regression model.
- Calculate average predictions and RMSE.
#### Profit Calculation
- Calculate the profit of the best wells in each region.
- Perform bootstrapping to calculate the average profit, confidence interval and risk of loss.

## Learnings
- Data analysis: Interpreting and extracting valuable insights from large volumes of data.
- Data cleaning: Identifying and correcting missing, duplicate, and anomalous values.
- Creating graphics: Using matplotlib and seaborn to visualize data in an intuitive and informative way.
- Data preprocessing: Preparing Data for analysis, including cleaning and treat the data.
- Use of libraries and tools: Practical application of various libraries and tools from the Python ecosystem, such as Pandas, Numpy, Sklearn, Matplotlib and Seaborn.
- Data visualization: Creating very detailed graphs and other types of visualizations to identify patterns and trends.
- Data-driven decision making: Using insights derived from data analysis to guide strategic decisions.
- Regression Models: Train and evaluate regression models.
- Model comparison: Compare models based on different metrics
- Scaling: Scaling the data to have zero mean and unit variance.