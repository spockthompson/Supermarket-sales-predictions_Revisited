# Supermarket sales predictions_Revisited
 
# Task
- For this assignment, we will revisit our first project to predict supermarket sales. we will apply what we have learned to explain how our models made their predictions.

## Project 1 Revisited - Part 1: Remaking, Saving, and Explaining Your Models
- For this part of the project, we will be producing a new version of our final project notebook using the updated tools in sklearn v1.1.
- Remake our X_train and X_test as DataFrames with the feature names extracted from the column transformer instead of combining your preprocessor and model into 1 pipeline.
# LinearRegression
- Fit and evaluate our LinearRegresion model using our dataframe X_train and X_test data.
- Extract and visualize the coefficients that our model determined.
- Select the top 3 most impactful features and interpret their coefficients in plain English.
- ![Alt text](https://github.com/spockthompson/Supermarket-sales-predictions_Revisited/blob/main/Data/coeffs.png))
# Tree-Based Model
- Fit and evaluate your tree-based regression model using your dataframe X_train and X_test data.
- Extract and visualize the feature importances that your model determined.
- Identify the top 5 most important features.
- ![Alt text](https://github.com/spockthompson/Supermarket-sales-predictions_Revisited/blob/main/Data/importances.png))
# Serialize Your Best Models with Joblib
