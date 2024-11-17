# Customer Churn Dashboard

An interactive and data-driven customer churn  dashboard built with **Power BI** to visualize key metrics like customer demographics with churn probability and more. This project helps telecom businesses track their performance, identify risks, and make data-driven decisions.

## Table of Contents
- [Overview](#Overview)
- [Objective](#Objective)
- [Key feature](#Key-Features)
- [Project](#Project)
- [DataSet](#dataset)
- [Data Cleaning and Preparation](#Data-Cleaning-and-Preparation)
- [Key Insights](#Key-Insights)
- [Suggestion](#Suggestion)
- [Dashboard Navigation Guide](#Dashboard-Navigation-Guide)
- [Tools and Technologies](#Tools-and-Technologies)
- [Business Impact](#Business-Impact)
- [Future Enhancements](#Future-Enhancements)
- [Installation and Setup](#Installation-and-Setup)
- [Contact](#contact)

## Overview
This project presents an in-depth analysis of customer churn within a telecom company using a set of interactive Power BI dashboards. The analysis is structured to give executives, analysts, and stakeholders a clear understanding of churn dynamics and the risk factors associated with customer attrition.

The project consists of two main dashboards:
1. **Customer Churn Dashboard**: Provides insights into customer demographics and KPIs, filtered specifically for churned customers (`Churn = 'Yes'`).
2. **Churn Risk Analysis Dashboard**: Segments customers based on their risk of churning and identifies key drivers behind churn behavior.

## Project Objective
The primary objective of this project is to:
- Analyze patterns and trends in customer churn.
- Highlight key metrics and demographic attributes associated with churned customers.
- Segment the current customer base based on churn risk to support proactive retention strategies.
- Enable data-driven decision-making to reduce churn and increase customer satisfaction.

## Key Features
### 1. **Customer Churn Dashboard**
This dashboard focuses on analyzing customers who have already churned. Key features include:
- **Customer Demographics**: Breakdown by age, gender, location, and other demographic factors to understand which groups are more prone to churn.
- **Service Details**: Insights into the types of services used by churned customers (e.g., internet, phone, streaming services).
- **Financial Metrics**: KPIs like average monthly charges, total revenue loss, and contract type distribution for churned customers.
- **Interactive Filters**: Users can drill down into the data using filters for demographics, service types, and billing methods to gain a deeper understanding of churn drivers.
  ![Custoemr-churn-dashboard](assets/images/Churn_Dashboard.png)

### 2. **Churn Risk Analysis Dashboard**
This dashboard provides a forward-looking analysis of the current customer base, focusing on identifying those at risk of churning:
- **Customer Segmentation**: Classification of customers into different risk segments (Low, Medium, High) based on key factors like service usage, billing issues, and customer support interactions.
- **Churn Risk Factors**: Visualizations highlighting top predictors of churn, such as contract length, support call frequency, and tenure.
- **Retention Strategy Insights**: Suggestions for retention strategies tailored to different risk groups, emphasizing data-driven decision-making.
- **Risk-Based Prioritization**: Easy-to-use visuals for prioritizing high-risk customers and taking proactive measures to retain them.
  ![Churn-risk-analysis-Dashboard](assets/images/Churn_Risk_Analysis.png)

##Project
  ## **Project** : [![project](Customer Churn Dashboard.pbix)](assets/Projects/Customer Churn Dashboard.pbix)

## Dataset
The dashboards are built using only one dataset, which is telecom customer churn dataset, which includes detailed information about customer behavior and demographics. The dataset features:
- **Customer Details**: Customer ID, gender, age, and geographic location.
- **Service Information**: Type of internet and phone services used, add-on features like streaming, and tenure.
- **Billing Information**: Monthly charges, total charges, payment methods, and billing issues.
- **Tech Support**: Number of times customer support was contacted and type of issue resolved.
- **Churn Status**: A binary indicator showing whether a customer has churned (`Yes` or `No`).

### Data Cleaning and Preparation
The dataset was preprocessed to handle missing values, standardize categorical features, and transform the data for efficient analysis in Power BI. Outliers were examined and addressed where necessary to improve data quality.

## Key Insights
1. Certain age groups and geographic regions show higher churn rates. Senior citzens are less likely to churn than non-senior citizens.
2. Customers on month-to-month contracts have a significantly higher churn rate compared to those on long-term contracts.
3. High monthly charges are correlated with a higher likelihood of churn.
4. Identifying customers with medium to high churn risk allows for targeted retention efforts, such as personalized offers or loyalty programs.
5. The customr churn rate last month was 27%, which means that our of 7043 customers, 1869 left the company.
6. Customer who don't have any dependents or partners are more prone to churn than those who do.
7. Gender does not seem to have a significant impact on the churn decision. However, senior citizens are less likely to churn than non-senior citizens.
8. Customers who use fiber optic internet service experience a higher churn rate compared to those who use other types of internet service.
9. Additionally, payment method plays a significant role in churn decisions, with electronic check being the most frequently used method among churned customers.
10. Customers who do not receive services like Tech Support, Device Protection, and Online Security tend to be more dissatisfied and are more likely to explore other options.

## Suggestion
1. Give special deals or fun packages for younger people so they want to stick around.
2. Give gifts, discounts, or points if people sign up for longer contracts instead of month-to-month plans.
3. Make cheaper plans that fit everyone’s needs better.
4. Make a rewards program to thank people who stay longer, like free stuff or discounts.
5. Make paying with electronic checks simpler and give prizes for setting up auto-pay.

## Dashboard Navigation Guide
1. **Customer Churn Dashboard**:
   - Use demographic filters to explore which customer groups have higher churn rates.
   - Examine service usage patterns and billing details to identify potential pain points.
2. **Churn Risk Analysis Dashboard**:
   - View the segmentation of customers into risk categories.
   - Analyze churn risk factors and understand which variables most strongly influence churn.
   - Use the insights to prioritize retention strategies.

## Tools and Technologies
- **Data Visualization**: Power BI
- **Data Preparation**: Excel for initial data cleaning and transformation
- **Interactive Features**: Filters, slicers, and drill-down options in Power BI

## Business Impact
The insights provided by these dashboards can help the telecom company:
- **Reduce Churn Rates**: By understanding the factors driving churn and implementing targeted retention strategies.
- **Optimize Customer Support**: Prioritize support for high-risk customers and address their issues proactively.
- **Enhance Customer Experience**: Use segmentation analysis to deliver personalized and value-driven experiences.

## Future Enhancements
- **Predictive Modeling**: Integrate machine learning models to predict churn probability and automate churn prevention strategies.
- **Advanced Segmentation**: Refine customer segments using more granular features for greater precision in risk analysis.
- **Incorporate Real-Time Data**: Enhance the dashboards with real-time data feeds for dynamic churn analysis.

## Installation and Setup
1. Download the Power BI dashboard file from this repository.
2. Open the file in Power BI Desktop.
3. Connect to the telecom churn dataset (if needed) and refresh the data.
4. Use the interactive visuals to explore and analyze customer churn.

## Contact
- [Sahil Patra]
- [+91 7735367833]
- [sahilpatra1004@gmail.com]
- [[LinkedIn Profile](https://www.linkedin.com/in/sahil-patra10)]

## Acknowledgements
- Thanks to the Power BI community for valuable tutorials and resources.
- Special mention to open data sources for providing the telecom churn dataset.

---

