# Data Science Assignment: eCommerce Transactions Analysis
## Introduction
This project is a part of the Data Science Intern Assignment. The objective is to perform exploratory data analysis (EDA), build a Lookalike model, and conduct customer clustering using eCommerce transactions data.
## Dataset Overview
The analysis is based on three datasets:

1. **Customers.csv**:
   - Details about customers including ID, name, region, and signup date.
   
2. **Products.csv**:
   - Product details including ID, name, category, and price.
   
3. **Transactions.csv**:
   - Transaction data including transaction ID, customer ID, product ID, quantity, and total value.
## Tasks Performed

1. **Exploratory Data Analysis (EDA):**
   - Insights such as top-selling products, revenue by region, and revenue by product category were derived.
   - Visualizations were created to showcase trends and distributions.

2. **Lookalike Model:**
   - Built a model to recommend similar customers based on their profiles and transaction history.
   - Generated a CSV file with the top 3 recommendations for the first 20 customers.

3. **Customer Clustering:**
   - Applied clustering techniques to group customers based on their spending habits and transaction frequency.
   - Evaluated clustering performance using the Davies-Bouldin Index.
## File Structure

The repository contains the following files:

- **Data_Science_Assignment.ipynb**: Jupyter Notebook with all code and outputs.
- **Data_Science_Assignment.pdf**: PDF report summarizing the EDA, insights, and results.
- **Lookalike.csv**: CSV file with lookalike customer recommendations.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- Jupyter Notebook
