# **Sales Forecasting & Anomaly Detection – Power BI (AI Project)**

## **Project Overview**
- This project uses **AI-powered analytics in Power BI** to move from reactive reporting to predictive analytics
- The focus is on forecasting future sales, detecting anomalies, and generating automated insights

## **Problem Statement**
- Forecast future sales
- Detect unusual sales patterns
- Identify risks and opportunities early
- Manual analysis is insufficient due to increasing data volume

## **Solution Approach**
- Analyze historical sales trends using line charts
- Identify seasonality patterns in sales data
- Forecast future sales using AI-powered forecasting
- Detect anomalies using Power BI AI visuals
- Generate automated insights using Smart Narratives

## **Data Preparation**
- Verified and corrected data types
- Standardized date formats
- Created a separate **Date table** for time-based analysis
- Prepared data for forecasting and anomaly detection

## **Data Model**
- **Fact Table**
  - Orders
- **Dimension Tables**
  - Date
  - People
  - Returns
- Star Schema used to improve performance and simplify analysis

## **Dashboard Pages**
- **Sales Overview Dashboard** – KPIs and historical sales trends
- **Sales Analysis** – Category-wise and profitability insights
- **Sales Forecasting using AI** – Actual vs forecasted sales with confidence intervals
- **AI-Based Sales Anomaly Detection** – AI-identified unusual sales patterns
- **Q&A Insights** – Natural language questions for instant insights

## **Key Measures**
- `Total Sales = SUM(Orders[Sales])`
- `Total Profit = SUM(Orders[Profit])`
- `Total Quantity = SUM(Orders[Quantity])`

## **Key Insights**
- Sales show clear seasonal patterns
- AI forecasting predicts future sales trends effectively
- Anomalies highlight unusual spikes and drops in sales
- Certain categories and regions contribute most to revenue

## **Business Impact**
- Enables proactive decision-making using AI insights
- Helps identify risks early through anomaly detection
- Supports demand planning using sales forecasts
- Reduces dependency on manual analysis

## **Tools Used**
- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Power BI AI Features (Forecasting, Anomaly Detection, Smart Narratives)
