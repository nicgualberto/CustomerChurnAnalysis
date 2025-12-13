# CustomerChurnAnalysis

CustomerChurnAnalysis is a data analysis project focused on understanding customer cancellation behavior (churn). The project explores customer data, identifies patterns related to churn, and proposes business actions based on data-driven insights.

## 🚀 Overview

The goal of this project is to analyze why customers cancel a service and identify the main factors that contribute to churn.

The workflow includes:
1. Loading and cleaning the dataset
2. Handling missing and inconsistent data
3. Performing exploratory data analysis
4. Visualizing churn patterns
5. Extracting insights and proposing solutions
6. Applying filters to simulate churn reduction strategies

## 📊 Dataset

- `cancelamentos_sample.csv`: customer data containing service usage, contract details, delays, call center interactions, and cancellation status.

## 🧹 Data Cleaning

The following steps were applied:
- Removal of irrelevant columns (e.g., `CustomerID`)
- Removal of missing values
- Standardization of the dataset for analysis

## 📈 Exploratory Data Analysis

Initial analysis focused on:
- Total number of canceled vs active customers
- Percentage of churn
- Impact of each variable on customer cancellation

Interactive histograms were generated for all columns using Plotly to visualize how each feature affects churn behavior.

## 🔍 Key Insights

From the analysis, the following patterns were identified:

- Customers who called the call center more than 4 times are more likely to cancel
- Customers with monthly contracts showed a 100% churn rate
- Customers with more than 20 days of payment delay always canceled

## 💡 Proposed Business Actions

Based on the insights:
- Trigger alerts when a customer contacts the call center for the 2nd time
- Offer discounts or incentives to customers with monthly contracts
- Notify the billing team when a customer exceeds 10 days of payment delay
- Improve call center processes to reduce churn risk

## 🛠 Technologies Used

- Python
- Pandas
- Plotly
- Jupyter Notebook

## ▶️ How to Run

1. Install the required dependencies:
   ```bash
   pip install pandas plotly
2. Make sure the file `cancelamentos_sample.csv` is in the project directory.
3. Run the notebook:
   ```bash
   jupyter notebook
4. Execute all cells to view the analysis and visualizations.

## 📚 What I Learned?

- Cleaning and preparing real-world datasets
- Performing exploratory data analysis (EDA)
- Identifying churn patterns using data visualization
- Transforming data insights into business actions
- Using Plotly for interactive visual analysis
