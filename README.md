# excel_economic

The project's objective is to analyze macroeconomic data to understand economic trends and their impact on markets. The dataset provides a comprehensive view of sales transactions, including information on customer age, gender, location, product costs, and revenue.
The analysis involves both numeric and categorical data, requiring a variety of analysis and visualization techniques.


![WhatsApp Image 2025-08-03 at 19 34 13_c59c5efd](https://github.com/user-attachments/assets/a12d864e-ca15-4d09-918d-b7cb8e4f48c6)

# Project Overview and objectives


The project aims to achieve the following:

 * Define the Scope and Objective: Identify specific economic indicators to analyze, such as GDP, unemployment rate, inflation rate, and interest rates. The project's scope is the US economy over a ten-year period.
   
 * Data Collection: Gather data from reliable sources like the World Bank and the Federal Reserve Economic Data (FRED).
   
 * Data Preparation: Clean the data to remove inconsistencies and combine datasets into a single file using tools like Pandas.
   
 * Exploratory Data Analysis (EDA): Perform EDA to understand data distribution and identify patterns, using visualization tools like Matplotlib and Seaborn.
   
 * Statistical Analysis: Conduct statistical analysis to find correlations and trends using Python libraries such as Pandas and Statsmodels.
   
 * Predictive Modeling: Build predictive models to forecast future economic trends using machine learning algorithms like Linear Regression, ARIMA, or SARIMA.
   
 * Reporting: Summarize all findings in a comprehensive report, supported by visualizations.


# Methodology

The project follows a step-by-step implementation plan:

 * Data Collection and Preparation: GDP, unemployment rate, inflation rate, and interest rate data are loaded from CSV files. Date columns are converted to datetime format, and the datasets are merged. The merged dataset columns are renamed for clarity.
   
 * Exploratory Data Analysis (EDA): The prepared data is used to plot time series graphs for each economic indicator (GDP, unemployment rate, inflation rate, and interest rate) to visualize trends over time.
   
 * Statistical Analysis: A correlation matrix is computed to show the relationships between the economic indicators, and a heatmap is used to visualize the matrix.
   
 * Predictive Modeling: The project utilizes an ARIMA model to forecast future GDP trends for the next 12 months. The model's performance is evaluated using the Mean Squared Error (MSE).
   
 * Reporting: The final step involves generating a summary report that details the data overview, key findings from the EDA and statistical analysis, and the results of the predictive modeling.


   
# Conclusion
This project provides a comprehensive analysis of economic data, from collection and preparation to predictive modeling. The insights gained from the analysis and the predictive model can be valuable for economic planning and decision-making.
