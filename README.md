# Media Campaign Cost Prediction

## Goal
The primary objectives of this project are:

1. To predict the cost of media campaigns in food marts across the USA based on customer income, product, promotion, and store features.
2. To identify and explore the key factors that affect the cost of these media campaigns.
## Solution Plan
### Dataset Overview
#### 1.Understanding the Dataset:
    Analyze the dataset variables, data types, and data distribution.
    Identify and address any missing values or outliers.
Exploratory Analysis
Patterns and Relationships:
Perform exploratory data analysis to uncover patterns, relationships, and correlations between variables.
Utilize visualizations like histograms, scatter plots, and box plots to understand data distribution.
Simple Data Cleaning & Feature Selection
Data Cleaning:
Handle missing values and outliers.
Feature Selection:
Use correlation analysis and feature importance ranking to select the most relevant features.
Machine Learning
Model Training:

Train a machine learning model on the cleaned and feature-selected data.
Use regression algorithms such as linear regression or decision tree regression to predict media campaign costs.
Model Evaluation:

Evaluate model performance using metrics such as mean squared error, mean absolute error, or R-squared.
Exploratory Analysis
Analysis of Product Characteristics
Food Category, Food Department, and Food Family:
Assess if the cost of media campaigns differs across various food categories, departments, and families using bar charts.
Conclusion: The difference is minimal, indicating that product characteristics do not significantly affect campaign costs.
Impact of Promotions
Promotion Name:
Use bar charts to visualize the relationship between promotion names and media campaign costs.
Conclusion: Some promotions have a significantly higher cost than others, indicating that promotions can significantly impact campaign costs.
Consumer Demographics
Average Annual Income, Marital Status, and Gender:
Use bar charts and box plots to explore the relationship between consumer demographics and media campaign costs.
Conclusion: Costs appear evenly distributed across demographic groups, suggesting that other factors may significantly impact campaign costs.
Data Cleaning & Feature Selection
Numerical Features:
Examine the correlation matrix to identify groups of correlated variables and potential collinearity issues.
Categorical Features:
Use ANOVA tests to determine the significance of categorical variables on the target variable.
Drop features with high P-values and low F-values, indicating a lack of strong influence on the target variable.
Feature Transformation
Convert Categorical Variables:
Transform categorical variables into dummy variables for modeling.
Machine Learning Models
Model 1: Linear Regression
Train and test a linear regression model to predict media campaign costs.
Evaluate model performance using Mean Squared Error (MSE) and R-squared (R^2) metrics.
Conclusion: The linear regression model explains 36% of the variation in campaign costs.
Model 2: LASSO Regression
Train and test a LASSO regression model.
Evaluate model performance and interpret the coefficients to understand feature importance.
Conclusion: The LASSO model provides similar performance to linear regression, with additional insights into feature importance.
Model 3: Random Forest Regressor
Train and test a Random Forest Regressor model.
Evaluate model performance using MSE and R^2 metrics.
Conclusion: The Random Forest Regressor explains 99.95% of the variation in campaign costs, indicating a strong model fit.
Conclusion
The project aimed to predict the cost of media campaigns in Food Mart of USA using data on 60,000 customers.
Key factors affecting media campaign costs include promotion names, media types, and store features like grocery and frozen sqft.
The Random Forest Regressor provided the best performance with an R^2 score of 0.9995.
Insights from this project can help optimize spending on promotions and advertising to acquire new customers efficiently while minimizing costs.
Financial Impact
To convert the results into financial terms, multiply the predicted values by the unit cost of the media campaign.
Example: If the average cost per customer acquisition is $100 and the model predicts $80, the expected cost for that customer would be $80.
This approach helps evaluate the financial impact of different factors on customer acquisition costs, enabling better decision-making to optimize media campaign expenses.
