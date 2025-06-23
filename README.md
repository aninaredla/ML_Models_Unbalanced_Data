# Project Goal
- Evaluating the effectiveness of various machine learning algorithms on an unbalanced dataset.
- Compare and contrast models based on prediction metrics and model complexity.

## Dataset Summary
The dataset included data on corporate credit ratings for various companies spanning a 5 year period. There are 30 predictor variables (25 numeric) and one response variable (letter rating). Most of the instances have a credit rating in the upper mid-range, making this dataset incredibly unbalanced.

## Skills Used
Applied machine learning techniques to build models that predict corporate credit rating. Algorithms included LASSO regression, K-nearest neighbors and Principal Component Regression. Other techniques including decision trees, logistic regression and neural networks were explored but were deemed to be out-of-scope.

## Technical Skills
Leveraged Python libraries including pandas for data manipulation, scikit-learn for machine learning models, and matplotlib for data visualization. Additionally, scipy.stats was used for hypothesis testing, and sklearn metrics for computing model performance metrics.

## Real-World Impact
This project explores the feasibility of applying traditional machine learning techniques to untreated real-life datasets, which are often raw and unbalanced to begin with. Aspects including rating re-organization and downsampling have been determined as future steps to help derive better insights from the given dataset.

## Visualization Descriptions
- Scatter plots depict how densely clustered the data points are to each other around the upper mid-level ratings.
- The scree plot for principal components show that as many as 10 principal components were required to account for 90% of the original data's variance. This is more than the number of predictor variables in the linear regression model.
