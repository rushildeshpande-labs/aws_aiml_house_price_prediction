# House Price Analysis and Prediction

## Project Overview
This project explores house-price data using Python and builds a Linear Regression model to predict house prices. It was completed as part of the AWS AI/ML Volunteer recruitment task.

## Dataset
The dataset contains the following columns:
- `area` — house area
- `bedrooms` — number of bedrooms
- `age` — age of the house
- `price` — house price

The dataset is synthetic and is used for learning and experimentation.

## Tasks Completed

### Task 1: Data Handling and Exploratory Data Analysis
- Inspected the dataset using Pandas.
- Handled missing values using median imputation.
- Used NumPy for numerical operations.
- Calculated descriptive statistics.
- Examined correlations between numerical features.
- Grouped data by bedroom count to compare average prices.
- Created visualizations to explore the data.

### Task 2: House Price Prediction
- Used Linear Regression from Scikit-learn.
- Selected house features to predict price.
- Split the data into training and testing sets.
- Evaluated the model using MAE, RMSE, and R².
- Compared actual and predicted prices using a plot.

## Files
- `House_Price_Analysis_and_Regression.ipynb` — notebook containing the analysis, code, outputs, and model evaluation.
- `house_data.csv` — dataset used in the project.

## Tools and Libraries
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Limitations and Future Scope
The dataset is synthetic, so the results may not represent real-world housing markets. Future work could use a real housing dataset, explore additional features, and compare Linear Regression with other regression algorithms.

## Learning Outcome
This project provided practical experience in data cleaning, exploratory data analysis, visualization, and introductory machine learning.
