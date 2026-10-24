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
### Model Evaluation Results

The Linear Regression model was evaluated on the test dataset using the following metrics:

- **Mean Absolute Error (MAE):** ₹4,47,693.09
- **Root Mean Squared Error (RMSE):** ₹8,77,894.12
- **R² Score:** 0.9348

The model achieved an R² score of 0.9348, indicating that it explains approximately 93.48% of the variation in house prices in the test dataset.

The learned coefficients were:
- **Area:** ₹4,493.69
- **Bedrooms:** ₹4,04,029.15
- **Age:** −₹8,444.37
- **Intercept:** ₹6,05,962.92

These coefficients represent the model's estimated relationship between each feature and house price, keeping the other features constant. Since the dataset is synthetic, the results should not be interpreted as reliable estimates for the real housing market.
