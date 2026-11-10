# Retail Sales Exploratory Data Analysis (EDA)

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a retail sales dataset as part of the Oasis Infobyte Data Analytics Internship.

The objective is to analyse retail transaction data, identify sales trends, understand customer purchasing behaviour, and discover useful business insights through Python and data visualisations.

## Project Objectives

- Understand the structure and characteristics of the dataset.
- Perform data cleaning and statistical analysis.
- Analyse monthly and quarterly sales trends.
- Explore customer demographics based on age and gender.
- Compare revenue across product categories.
- Identify relationships between numerical variables.
- Generate insights and actionable business recommendations.



## Tools and Technologies

The following tools and libraries were used in this project:

- Python – Programming language
- Pandas – Data manipulation and analysis
- NumPy – Numerical operations
- Matplotlib – Data visualisation
- Seaborn** – Statistical data visualisation
- Jupyter Notebook – Interactive analysis and documentation
- VS Code – Development environment
- Git and GitHub – Version control and project hosting

## Dataset Information

- Dataset: Retail Sales Dataset
- Total Records: 1,000 transactions
- Total Columns: 9
- Time Period: January 2023 – January 2024
- File Format: CSV

The dataset contains the following columns:

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

The dataset was used to analyse customer demographics, transaction values, sales trends, and product category performance.

## Analysis Performed

The following analyses were performed during this project:

1. Data Inspection
   - Checked dataset dimensions, column names, and data types.
   - Checked for missing values and duplicate records.

2. Descriptive Statistics
   - Calculated mean, median, mode, and standard deviation for numerical columns.

3. Monthly and Quarterly Sales Analysis
   - Analysed monthly and quarterly sales trends.
   - Created line charts to understand changes in sales over time.

4. Customer Demographics Analysis
   - Grouped customers into different age categories.
   - Analysed customer distribution by gender.

5. Product Category Revenue Analysis
   - Compared total revenue across product categories using a bar chart.

6. Correlation Analysis
   - Used a correlation matrix and heatmap to examine relationships between numerical variables.

7. Average Spending by Age Group
   - Compared average transaction amounts across different age groups to identify spending pattern

## Key Findings

The analysis revealed the following insights:

- The dataset contains 1,000 transactions with no missing values or duplicate records.
- Electronics generated the highest revenue, with a total of 156,905.
- Clothing generated 155,580 in revenue, while Beauty generated 143,515.
- The fourth quarter of 2023 recorded the highest quarterly sales, totalling 126,190.
- Customers aged 46–55 represented the largest age group, with 229 transactions.
- Female customers accounted for 51% of transactions, while male customers accounted for 49%.
- Customers aged 18–25 had the highest average transaction amount of 500.30.
- Price per Unit showed a strong positive correlation with Total Amount (0.85).
- Quantity showed a moderate positive correlation with Total Amount (0.37).

## Business Recommendations

Based on the analysis, the following recommendations can be considered:

1. Focus on Electronics: Maintain appropriate inventory and explore promotional campaigns for the highest-revenue category.
2. Target Younger Customers: Consider offers and campaigns aimed at customers aged 18–25, who showed the highest average transaction amount.
3. Analyse Seasonal Trends: Investigate the lower sales recorded in Q3 2023 and consider targeted promotions during weaker periods.
4. Maintain Balanced Marketing: Continue reaching both male and female customers, as their transaction distribution is nearly equal.
5. Review Product Pricing: Examine pricing and product mix to better understand their relationship with transaction amounts.


## Project Structure


DataAnalytics-L1-EDARetailSales/
│
├── dataset/
│   └── retail_sales_dataset.csv
│
├── outputs/
│
├── screenshots/
│   ├── monthly_sales.png
│   ├── quarterly_sales.png
│   ├── customer_demographics.png
│   ├── category_revenue.png
│   ├── correlation_heatmap.png
│   └── average_spending_by_age.png
│
├── Retail_Sales_EDA.ipynb
├── README.md
└── requirements.txt


## How to Run the Project

Follow these steps to run the project locally.

1. Clone the repository

```bash
git clone https://github.com/jhaAshwani30/OIBSIP.git
```

2. Navigate to the project folder

```bash
cd OIBSIP/DataAnalytics-L1-EDARetailSales
```

3. Create a virtual environment

```bash
python -m venv venv
```

4. Activate the virtual environment (Windows PowerShell)

```powershell
.\venv\Scripts\Activate.ps1
```

5. Install the required libraries

```bash
pip install -r requirements.txt
```

6. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Retail_Sales_EDA.ipynb` and run the notebook cells.

## Dataset Limitation

The dataset provides product categories rather than individual product names or product IDs. Therefore, individual top 10 products could not be identified. Instead, the analysis compares revenue across the available product categories.

## Conclusion

This project demonstrates the use of Python libraries for exploratory data analysis, statistical analysis, and data visualisation. The findings provide insights into retail sales patterns and customer purchasing behaviou
