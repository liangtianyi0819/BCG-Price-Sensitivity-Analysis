# BCG Price Sensitivity Analysis: Conclusive Report

Project creator: [Tianyi Liang](https://www.linkedin.com/in/tianyi-liang-at-bu/)
Create date: 06/07/2023.

# BCG Price Sensitivity Analysis

This project conducts an in-depth analysis of two datasets: `client_data.csv` and `price_data.csv`, with the aim of understanding the price sensitivity of customers and its impact on customer churn. 

## Table of Contents

1. [Project Description](#project-description)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Key Insights](#key-insights)
5. [Business Strategy](#business-strategy)
6. [Final Thoughts](#final-thoughts)

## Project Description <a name="project-description"></a>

The `client_data.csv` dataset provides comprehensive information about SME customers, including their consumption patterns, contract details, forecasted consumption and prices, margins, and churn status. The `price_data.csv` dataset contains the historical prices for these customers from the year 2015.

The analysis proceeds through the following steps:

- Descriptive Statistics and Visualization
- Data Cleansing
- Exploratory Data Analysis (EDA) and Visualization
- Data Merging
- Feature Selection and Train-Test-Split
- Model Selection
- Hypothesis Verification
- Discount Impact Evaluation

## Installation <a name="installation"></a>

This project requires Python and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

## Usage <a name="usage"></a>

In a terminal or command window, navigate to the top-level project directory `BCG-Price-Sensitivity-Analysis/` (that contains this README) and run one of the following commands:

```bash
jupyter notebook BCG_Price_Sensitivity_Analysis.ipynb
```

This will open the Jupyter Notebook software and project file in your web browser.

## Key Insights <a name="key-insigts"></a>

Our analysis revealed several key insights:

1. **Churn Rate**: We found that the churn rate before applying any discount was 10.39%. This indicates that over 10% of customers were leaving the service, which is a significant proportion that warrants further investigation and action.

2. **Price Sensitivity**: After applying a 20% discount to a subset of customers who had churned, the churn rate dropped to 3.54%. This is a significant reduction and suggests that price is a major factor influencing customer churn.

3. **Global Impact**: The discount strategy resulted in a 6.85% change in the global churn rate and a 65.94% reduction in the churn rate among the customers who received the discount. This demonstrates the potential effectiveness of a price-based strategy in reducing customer churn.

## Business Strategy <a name="business-strategy"></a>

Based on these insights, we propose the following strategies:

1. **Implement a Discount Program**: Given the significant reduction in churn rate following the application of a 20% discount, implementing a discount program could be a viable strategy for reducing churn. This program could target customers identified as being at high risk of churn.

2. **Personalize Pricing**: The impact of the discount suggests that customers are sensitive to price changes. Therefore, a personalized pricing strategy, where prices are tailored based on individual customer behavior and characteristics, could be effective.

3. **Enhance Customer Engagement**: While price is a significant factor, it's not the only reason customers churn. Improving customer engagement through better communication, service, and value-added offerings could also help reduce churn.

## Final Thoughts <a name="final-thoughts"></a>

This analysis provides a valuable starting point for understanding customer churn and price sensitivity. However, it's important to remember that customer behavior is influenced by a multitude of factors. Therefore, while the strategies proposed here are based on our current data and analysis, they should be continually reviewed and refined as more data becomes available and as market conditions evolve.

In conclusion, the power of data analysis lies in its ability to reveal patterns and insights that can inform strategic decision-making. In the case of customer churn and price sensitivity, our analysis has shown that a well-planned discount strategy could potentially lead to a significant reduction in churn rate. However, the most effective approach will likely involve a combination of strategies, including price adjustments, personalized customer engagement, and continuous monitoring of customer behavior.
