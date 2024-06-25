# Online Sales Data Analysis and Machine Learning

This repository contains an exploratory data analysis (EDA) and machine learning project based on an online sales dataset. The project answers various questions related to sales performance, product analysis, customer behavior, and predictive modeling.

## Dataset

The dataset `Online Sales Data.csv` contains the following columns:
- `Transaction ID`
- `Date`
- `Product Category`
- `Product Name`
- `Units Sold`
- `Unit Price`
- `Total Revenue`
- `Region`
- `Payment Method`

## Project Structure

- `online_sales_analysis.py`: Main script for data analysis and machine learning.
- `Online Sales Data.csv`: The dataset used for analysis.

## Analysis Questions

### Data Overview
1. What is the total number of transactions in the dataset?
2. What is the time range of the sales data?

### Sales Performance
3. What is the total revenue generated?
4. What are the average, minimum, and maximum unit prices of products?

### Product Analysis
5. Which product category has the highest total revenue?
6. Which product has the highest units sold?
7. What is the distribution of total revenue across different product categories?

### Sales Trends
8. What are the monthly sales trends in terms of total revenue and units sold?
9. How does the average unit price change over time?

### Regional Analysis
10. Which region has the highest total sales revenue?
11. What is the distribution of sales (total revenue and units sold) across different regions?

### Payment Methods
12. What is the most commonly used payment method?
13. How does the total revenue and units sold vary by payment method?

### Customer Behavior
14. What is the average number of units sold per transaction?
15. How many transactions involve multiple units of a product?

### Top Performers
16. Which specific product generates the most revenue in each product category?
17. What are the top 10 highest-grossing transactions?

### Sales by Date
18. What are the peak sales days in terms of total revenue and units sold?
19. How do weekend sales compare to weekday sales?

### Outliers and Anomalies
20. Are there any outliers in terms of unit price or total revenue?
21. Are there any anomalies in sales data that require further investigation?

### Machine Learning
22. Can we predict the total revenue of a transaction based on features such as product category, unit price, units sold, region, and payment method?
23. Can we segment customers based on their purchase behavior using clustering algorithms?
24. Can we forecast the demand (units sold) for different product categories over time using time series analysis?

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/akadve/Sales_EDA.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Sales_EDA
    ```
3. Ensure you have the required libraries installed:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
4. Run the analysis script:
    ```bash
    python Sales_EDA.py
    ```

## Results

The results of the analysis will be printed to the console and visualized using Matplotlib and Seaborn plots. Key insights and machine learning model evaluations will be provided.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

