# Supermarket-Sales-Analytics-and-Forecasting-Project
## Table of Content
  - [Project Overview](#Overview)
  - [Data Scources](#Data-Used)
  - [Tools](#Tools-and-Libraries)
  - [Key Metrics and Techniques](#Key-Metrics-and-Techniques)
  - [Steps in the Project](#Steps-in-the-Project)
  - [Key Findings](#Key-Findings)
  - [Recommandations](#Recommandations)
  - [Limitations](#Limitations)

# Supermarket Business Analysis Project

## Overview
This project focuses on performing data analysis and building predictive models for a supermarket business. The goal is to enhance decision-making by analyzing business performance, customer behavior, sales trends, and the effectiveness of promotions. The project is structured around four main objectives:

1. **Business Performance Tracking**
   - Analyze key performance metrics to track the supermarket's financial health and performance.
   - Metrics: Sales Performance Index (SPI), Profitability Index (PI).

2. **Customer Insights**
   - Segment customers based on purchasing patterns and behaviors, providing insights to optimize marketing strategies.
   - Metrics: Customer Segment Score (CSS), Purchasing Power Pattern Index (PPP Index), Customer Value Index (CVI).

3. **Sales Forecasting**
   - Build a predictive model to forecast future sales trends and understand seasonal fluctuations.
   - Metrics: Sales Prediction Index (SPI), Seasonal Insight Index (SII).

4. **Promotion Effectiveness**
   - Measure the effectiveness of marketing promotions and their impact on customer acquisition and sales growth.
   - Metrics: Promotion Impact Score (PIS), Customer Acquisition Rate (CAR).

## Data Used
The project uses a supermarket sales dataset containing transactional data, customer demographic information, and promotional details. The data is analyzed using Python for exploratory data analysis (EDA), visualization, and predictive modeling.

## Tools and Libraries
- **Python**: For data analysis, model building, and visualization.
- **pandas**: Data manipulation and analysis.
- **matplotlib, seaborn**: Visualization of trends and insights.
- **scikit-learn**: Machine learning models for sales forecasting and prediction.
- **Tableau**: For interactive dashboards and reporting.
- **Google Colab/Jupyter Notebooks**: For running the Python code and documentation.

## Key Metrics and Techniques
- **Sales Performance Index (SPI)**: A composite metric that combines sales volume, profitability, and market share.
- **Profitability Index (PI)**: Measures profit relative to sales for each product category.
- **Customer Segment Score (CSS)**: Categorizes customers based on purchasing behavior, loyalty, and demographic information.
- **Purchasing Power Pattern Index (PPP Index)**: Analyzes customer spending habits to identify high-value segments.
- **Customer Value Index (CVI)**: Measures the lifetime value of customers based on historical data and future projections.
- **Sales Prediction Index (SPI)**: Predicts future sales based on historical trends, seasonal patterns, and other relevant factors.
- **Seasonal Insight Index (SII)**: Identifies key seasonal trends affecting sales.
- **Promotion Impact Score (PIS)**: Assesses the return on investment for promotions, looking at sales uplift and customer engagement.
- **Customer Acquisition Rate (CAR)**: Tracks the success of marketing efforts in attracting new customers.

## Steps in the Project
1. **Data Collection and Cleaning**: Import the dataset, handle missing data, and preprocess for analysis.
2. **Exploratory Data Analysis (EDA)**: Visualize and analyze data trends to understand customer behavior, sales patterns, and business performance.
3. **Feature Engineering**: Create new features like SPI, PI, CSS, and others based on the dataset for deeper insights.
4. **Sales Forecasting Model**: Use machine learning models (like linear regression or time-series analysis) to predict future sales.
5. **Promotion Effectiveness Analysis**: Measure the impact of promotions using PIS and CAR.
6. **Results and Recommendations**: Summarize findings and provide actionable insights for business optimization.

## Key Findings

1. **Sales Forecasting**:
   - **ADF Test** confirms stationarity of the series for time series forecasting (ADF: -5.8308, p-value: 3.98e-07).
   - **Model Evaluation**:  
     - **RMSE**: **41,900.49**  
     - **MAE**: **35,370.81**  
     The forecast for the next 12 months closely follows the observed sales trend, demonstrating the model’s robustness despite moderate prediction errors.

2. **Sales Performance**:
   - Sales show cyclical patterns with stronger performance in specific months and weaker sales in others (e.g., **Month 2017**, **April 2015**).
   - Categories like **Health & Hygiene** perform well, while **Organic Staples** and **Snacks** underperform.

3. **Customer Segmentation**:
   - **Loyalists** contribute significantly to sales and profitability.
   - **Intermittent Shoppers** show irregular shopping patterns, with potential for increased purchase frequency.
   - **Seasonal Shoppers** underperform in frequency, recency, and spending, presenting an opportunity for targeted seasonal campaigns.

4. **Promotion Effectiveness**:
   - **Customer Acquisition Rate (CAR)**: **48.18%** increase from promotions.
   - Despite high CAR, the **Promotion Impact Score (PIS)** of **-0.53327%** suggests limited sales impact during promotions.

## Recommendations

1. **Loyalists**: Implement targeted **loyalty programs** and **upselling** opportunities.
2. **Seasonal Shoppers**: Design tailored **seasonal campaigns** to boost engagement.
3. **Intermittent Shoppers**: Increase shopping frequency with **re-engagement campaigns**.
4. **Product Categories**: Focus on high-performing categories and optimize low-performing ones through **pricing adjustments** or promotions.

## Limitations

- **Granular Data**: More detailed segmentation (e.g., demographics) could provide deeper insights.
- **External Factors**: Economic conditions and competition are not accounted for.
- **Predictive Modeling**: Additional machine learning models could enhance decision-making, such as churn prediction.

## Conclusion

This analysis highlights opportunities to refine forecasting models, optimize promotional strategies, and better understand customer behavior. By focusing on **targeted promotions**, improving **customer retention**, and utilizing **advanced modeling**, the supermarket can increase profitability and customer loyalty.

