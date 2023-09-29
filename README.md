# Paris_Housing_Practice
# Paris Housing Data Analysis

This repository contains a Python script for analyzing the Paris Housing dataset using popular data science libraries. Below is a step-by-step explanation of the code:

## Prerequisites

Before running the code, ensure that you have the following libraries installed:
- NumPy
- Pandas
- Seaborn
- Matplotlib
- scikit-learn

You can install these libraries using `pip install`.

## Code Explanation

1. **Importing Necessary Libraries**: In this section, we import the required Python libraries for data analysis.

2. **Reading the Dataset**: We load the Paris Housing dataset from a CSV file named "ParisHousing.csv" into a Pandas DataFrame called `paris_df`.

3. **Shape of the Dataset**: We print the shape of the dataset, which displays the total number of rows and columns.

4. **Information about the Dataset**: We use `paris_df.info()` to get information about the dataset, including data types, column names, and the number of non-null values.

5. **Checking for Missing Values**: The code checks for missing values in the dataset using `paris_df.isnull().sum()`.

6. **Statistical Analysis of Data**: We compute basic statistical summary metrics for the numeric columns using `paris_df.describe()`.

7. **Displaying the First Few Rows of Data**: We show the first few rows of the dataset using `paris_df.head()` to get an initial glimpse of the data.

8. **Correlation Analysis**: We calculate the correlation matrix between numeric variables and visualize it using a heatmap created with Seaborn.

9. **Identifying Relationship Between Features**: We plot the relationship between the "squareMeters" and "price" columns to visualize their correlation.

10. **Feature Selection**: We drop certain features from the dataset that may not be relevant for analysis or modeling.

11. **Machine Learning Model (Random Forest Regressor)**: We import scikit-learn libraries to build a Random Forest Regressor model. We split the data into training and testing sets.

12. **Model Evaluation Function**: We define a function `evaluate` to evaluate the model's performance in terms of accuracy and error.

13. **Evaluating the Model**: We evaluate the model on both the training and testing datasets.

14. **Feature Importance**: We calculate feature importance scores using the trained Random Forest model and display them in a DataFrame.

15. **Sorting Feature Importance**: We sort the features by importance in descending order.

## Running the Code

To run this code on your local machine, make sure you have the required libraries installed. You can execute the code in a Python environment or Jupyter Notebook.

Feel free to modify and adapt the code for your specific needs.

If you have any questions or suggestions, please feel free to open an issue or contact the repository owner.

Enjoy exploring the Paris Housing dataset!
