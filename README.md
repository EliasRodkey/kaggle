# Kaggle Learning

Repository that holds kaggle machine learning training materials and documents

## Lessons

1. **Intro to Machine Learning**
    - The basics of using sklearn and pandas to make decision tree and random forest predictive models.
    - Reading viewing and manipulating data.
    - Conventions in machine learning (X, y).
    - Introduction to the concept of under and overfitting.
    - Introduction to training data train and validation splits.

2. **Pandas**
    - Basics of the pandas DataFrame, how it is structured, how to include an index, and how to pull from different sources.
    - Grabbing specific data: .loc (label based selection) and .iloc (index based location) functions.
    - Using comparators to refine search criteria.
    - Summary methods .mean(), .median(), .unique(), .value_counts(), .idxmax().
    - Data mapping using the .map() and .apply() methods to transform data.
    - The .groupby() function groups together data based on a given column. Creates mutli-index dataframe.
    - The .agg() mehtod is a groupby() method that can run a number of functions on a series at once.
    - reset_index() can be used to flatten multi indexed dataframe again.
    - Simple DataFrame sorting techinques using .sort_values() and .sort_index().
    - How to read and change column dtypes.
    - How to fill missing values or replace values using .fillna() and .replace().

3. **Intermediate Machine Learning**
    - Categorical variables: options for dealing with them are dropping, ordinal encoding, or one-hot encoding.
    - Cross-validation: Using all the available data in chunks to train the model more efficiently with less data.
    - Data leakage: When data  used to train the model will not be available in production. How to spot and avoid.
    - Missing values: how to deal with missing values. Strategies include dropping columns, replacement, or imputation + extension.
    - pipelines: once you figure out how you want to process / clean the data wrap it all in a pipeline.
    - xgboost: basics of xgboost regression boosting aggregated learning package.

4. **Data Visualization**
    - Lineplots: Use sns.lineplot to create a chart of data or a subset of data.
    - Bar Charts and Heatmaps: Use sns.barplot and sns.heatmap to create custom plots.
    - Scatter Plots: 