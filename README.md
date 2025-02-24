# Data-Processing-and-Visualization
## Analyzing Global University Rankings and California Housing Trends
This repository contains the coursework for the module: Data Processing and Visualisation, as part of the academic year 2024-25 (Cardiff University). The coursework involves analyzing and visualizing data using Python, specifically focusing on the QS World University Rankings and California Housing Prices datasets.

## Contents:
1. 2018-QS-World-University-Rankings-Top200.xlsx
2. California Housing Prices (CHP) dataset.csv
3. Coursework FIle (CW_23112887.ipynb)

## Tasks:
## 1. QS World University Rankings

## Task 1: Data Reading and Visualization
- Imported Libraries: Used pandas for data manipulation and matplotlib for visualization.
- Data Loading: Read the QS World University Rankings data from an Excel file.
- Data Filtering: Filtered the dataset to include only UK universities and sorted them by rank.
- Visualization: Created a horizontal bar graph displaying the Overall Score of UK universities, with appropriate labels and title. Inverted the y-axis to show the highest-ranked university at the top.

## Task 2: Analysis of Academic Reputation
- Location Filtering: Counted the number of institutions per location and filtered to include only those with three or more institutions.
- Mean Calculation: Grouped the data by location and calculated the mean of the "Academic Reputation" metric.
- Confidence Interval: Calculated the 95% confidence interval for the mean values.
- Visualization: Plotted a vertical bar graph showing the mean Academic Reputation by location, including error bars for the confidence intervals.

## Task 3: Statistical Comparision
- Data Preparation: Filtered the dataset for Australia, the United States, and France.
- Independent t-tests: Conducted t-tests to compare the "Academic Reputation" between the selected countries.
- Results Summary: Printed concise summaries for each comparison, indicating whether the differences were statistically significant.

## 2. California Housing Prices (CHP)

## Task 4: Correlation Analysis
- Data Loading: Imported the California Housing Prices dataset and dropped rows with missing values.
- Correlation Calculation: Analyzed the linear correlation between predictor variables and the target variable (Median House Value).
- Visualization: Created a bar graph to visualize the correlation coefficients, adding labels and values for clarity.

## Task 5: Linear Regression Model Development
- Model Definition: Defined two linear regression models (Model A and Model B) with specified predictor variables.
- Model Training: Trained both models using the cleaned dataset and calculated the Mean Squared Error (MSE) for each.
- Model Comparison: Printed the linear equations for both models and visualized the MSE values to compare their performance.

## Task 6: Model Comparision Reporting
- Results Interpretation: Summarized the findings regarding the accuracy and reliability of the models based on MSE.
- Limitations Discussion: Discussed the limitations of the models, including the assumptions made and the need for further testing with new data.
