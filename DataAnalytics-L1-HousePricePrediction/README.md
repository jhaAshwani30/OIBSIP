# House Price Prediction Using Linear Regression

## Project Overview
This project focuses on predicting house prices using Machine Learning techniques. Linear Regression is used as the primary model, with Ridge and Lasso Regression implemented for comparison.

The project uses Python and popular data analysis and machine learning libraries to explore housing data, train regression models, and evaluate their performance.

## Dataset
- Dataset: Housing.csv
- Records: 545
- Columns: 13
- Target Variable:** Price

The dataset contains information about house area, bedrooms, bathrooms, stories, parking, furnishing status, and other property features.

Note: The dataset does not contain exact location names or house age.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Dataset loading and inspection
2. Exploratory Data Analysis
3. Missing-value checking
4. Descriptive statistical analysis
5. House price distribution visualization
6. Feature selection
7. One-Hot Encoding
8. Correlation heatmap
9. Training and testing data split
10. Linear Regression model training
11. House price prediction
12. Model evaluation using MSE, RMSE, and R²
13. Actual vs Predicted visualization
14. Residual analysis
15. Feature coefficient analysis
16. Ridge and Lasso Regression comparison

## Model Performance

| Model | RMSE (Approx.) | R² Score |
|---|---:|---:|
| Linear Regression | 1,324,507 | 0.652924 |
| Ridge Regression | 1,324,703 | 0.652821 |
| Lasso Regression | 1,324,507 | 0.652924 |

Linear Regression and Lasso Regression achieved almost identical performance. Ridge Regression performed slightly worse.

## Visualizations
The `screenshots/` folder contains:
- House price distribution
- Correlation heatmap
- Actual vs Predicted prices
- Residual plot
- Feature coefficient chart
- RMSE comparison chart
- R² score comparison chart

## How to Run the Project

1. Clone this repository.
2. Open the project folder.
3. Create and activate a virtual environment.
4. Install the required libraries:

```bash
pip install -r requirements.txt
```

5. Open Jupyter Notebook:

```bash
jupyter notebook
```

6. Open `House_Price_Prediction.ipynb` and run the cells.

## Conclusion
This project demonstrates how Linear Regression can be used to predict house prices based on property features. Ridge and Lasso Regression were also evaluated to compare their performance.

## Future Improvements
- Use a larger housing dataset.
- Include house age and location information.
- Experiment with Decision Tree and Random Forest models.
- Apply hyperparameter tuning.
- Develop a web application for house price prediction.
