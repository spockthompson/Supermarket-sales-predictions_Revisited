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
- Fit and evaluate our tree-based regression model using our dataframe X_train and X_test data.
- Extract and visualize the feature importances that our model determined.
- Identify the top 5 most important features.
- ![Alt text](https://github.com/spockthompson/Supermarket-sales-predictions_Revisited/blob/main/Data/importances.png))


# Explain our tree-based model with shap:
![Alt text](https://github.com/spockthompson/Supermarket-sales-predictions_Revisited/blob/main/Data/summary_plot_rf.png))
The most important features using SHAP are almost idetical to the original feature importance with the exception of the outlet type(Supermarket type 3)
## Visualization using summary plot, dot version
![Alt text](https://github.com/spockthompson/Supermarket-sales-predictions_Revisited/blob/main/Data/summary_plot_dot.png))
### Interpret the top 3 most important features and how they influence our model's predictions.
1. Item MRP:
  - The more the item cost the more likely the amount in total sales will increase
2. Outlet type "Grocery Store"
  - Although this "type of outlet is lower on the feature value it seems to affect to amount of sales positively.
3. Outlet Type "Supermarket Type 3":
  - The higher this value is(more of this type of building) the more it increase the amount of sales.
