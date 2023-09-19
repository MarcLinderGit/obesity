# Feature Selection Using Wrapper Methods

### Project Brief

**Objective:** In this project, I will perform feature selection using three different wrapper methods on a dataset obtained from a survey about eating habits and weight. The goal is to identify a smaller subset of features that can accurately predict whether a survey respondent is obese or not.

Data source: [UCI Machine Learning Repository - Estimation of obesity levels](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition)

### Tasks Overview

Here's a breakdown of the tasks I'll be performing using Python and various packages:

1. **Data Loading and Inspection**: I'll load the dataset and inspect its structure using `pandas`. This will help me understand the available features and the target variable.

2. **Logistic Regression Model**: I'll create a logistic regression model using `LogisticRegression` from `sklearn` to establish a baseline accuracy for comparison.

3. **Sequential Forward Selection (SFS)**: I'll implement SFS using the `SequentialFeatureSelector` class from `mlxtend` to select a subset of features that maximizes accuracy. I'll then evaluate the model's accuracy on this reduced feature set.

4. **Sequential Backward Selection (SBS)**: I'll implement SBS using the `SequentialFeatureSelector` class from `mlxtend` to select another subset of features that maximizes accuracy. Again, I'll evaluate the model's accuracy on this subset.

5. **Recursive Feature Elimination (RFE)**: I'll standardize the data and apply RFE using `RFE` from `sklearn` to select a subset of features. I'll also evaluate the model's accuracy on this reduced feature set.

6. **Visualizing Results**: I'll visualize the results of SFS and SBS by plotting the model accuracy as a function of the number of features used.