# E-Commerce
Analyzing Simulated E-commerce Transaction Data

Project Overview
This project focuses on applying fundamental data science skills to a simulated dataset representing online sales transactions for a small fictional e-commerce store. It involves generating synthetic data using Python libraries such as Pandas and NumPy, performing exploratory data analysis (EDA), and visualizing key findings using Matplotlib and Seaborn.

Project Steps
The core steps for this project are as follows:

1. Data Generation
A synthetic dataset of at least 500 rows is generated, including the following features:
TransactionID(datetime): Date of the transaction
CustomerID
ProductCategory(string): Product group (3–5 unique categories)
PurchaseAmount(float): Monetary value of each transaction
TransactionDate
PaymentMethod

Tools & Libraries Used

Python 3

Pandas

NumPy

Matplotlib

Seaborn

3. Data Loading and Cleaning
The generated data is loaded into a pandas DataFrame. Initial inspection checks for data
types and missing values to ensure data quality.

5. Descriptive Statistics
Key descriptive statistics (mean, median, standard deviation) are calculated for the PurchaseAmount variable, both overall and grouped by ProductCategory.

7. Visualization
Two distinct visualizations are created to illustrate key insights:
A histogram showing the distribution of purchase amounts.
A bar chart detailing the frequency of different product categories or payment

Key Findings

Purchase amounts follow a roughly continuous distribution with visible spending ranges

Certain product categories show higher transaction counts, indicating stronger demand

Grouped statistics reveal differences in average spending across categories

Conclusion

This project successfully demonstrates how synthetic data can be used to practice real-world data analysis workflows. The descriptive statistics provide insights into overall and category-wise spending behavior, while the visualizations highlight transaction distribution and product popularity.

Such analysis is useful for:

Identifying high-performing product categories

Understanding customer spending trends

Supporting data-driven business decisions

Overall, this EDA serves as a strong foundation for more advanced analyses such as customer segmentation, time-series analysis, or predictive modeling.
