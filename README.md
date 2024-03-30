# Employee Satisfaction Analysis

## Summary
This project involves analyzing employee satisfaction data to understand various factors affecting satisfaction levels. The analysis includes data exploration, statistical summaries, outlier detection, visualization of categorical variables, explanation of salary differences, determination of relationships among variables, and prediction of satisfaction levels using XGBoost.

## Analysis Steps

### 1. Data Exploration and Preparation
- Imported necessary libraries.
- Loaded the dataset and performed initial data checks.
- Ensured appropriate data types and handled missing values.
- Identified outcome and input variables for analysis.

### 2. Statistical Summaries
- Calculated summary statistics for numerical and categorical variables.
- Provided insights into satisfaction levels, evaluation scores, project counts, working hours, tenure, work accidents, promotions, and salary distributions.

### 3. Outlier Detection
- Utilized boxplots to identify outliers in numerical columns.
- Applied the Interquartile Range (IQR) method to remove outliers if necessary.

### 4. Visualization of Categorical Variables
- Visualized department and salary distributions using count plots.

### 5. Explanation of Salary Differences
- Analyzed summary statistics grouped by salary levels to explain income differences.

### 6. Determination of Relationships Among Variables
- Utilized correlation analysis to determine relationships among variables.
- Provided explanations for different correlation strengths.

### 7. Prediction of Satisfaction Levels
- Utilized XGBoost Regressor to predict satisfaction levels.
- Calculated Mean Absolute Error (MAE) and R-squared score for model evaluation.

## Files
- **employee_satisfaction_analysis.ipynb**: Jupyter Notebook containing the analysis code.
- **README.md**: This file, providing an overview of the project.
- The dataset used in this analysis can be found on [Kaggle]([https://www.kaggle.com/datasets/redpen12/employees-satisfaction-analysis]).

## Instructions
1. Clone the repository.
2. Install the required libraries.
3. Run the Jupyter Notebook (`employee_satisfaction_analysis.ipynb`) to reproduce the analysis.

## Conclusion
This analysis provides valuable insights into factors affecting employee satisfaction. It highlights the importance of various workplace aspects such as workload, tenure, promotions, and salary levels. Additionally, the predictive model offers a tool for estimating satisfaction levels based on provided input variables.
