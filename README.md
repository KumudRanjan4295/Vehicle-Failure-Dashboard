# 🚗 Vehicle Failure Analytics Dashboard

An interactive, dynamic dashboard built using **R**, **Flexdashboard**, **Plotly**, and **Highcharter** to explore and analyze **vehicle failure patterns** across the United States.  
This project empowers automotive analysts, fleet managers, and researchers to make better operational and maintenance decisions through data-driven insights.

## 📋 Project Summary

This project transforms raw vehicle failure data into a visually engaging and highly interactive dashboard.  
It provides meaningful analytics across geography, failure timing, mileage, and cost dimensions, helping users quickly identify problem areas and operational trends.

## 🚀 Key Features

- 📍 **State-wise Failure Trends**: Bar charts, pie charts, and interactive maps.
- 💰 **Cost Monitoring**: Labor cost analysis using dynamic gauges and boxplots.
- 🛠️ **Temporal Failure Insights**: Trendlines showing mileage and month-based failure behavior.
- 📊 **Custom Data Exploration**: Interactive pivot tables for on-the-fly analysis.
- 🌐 **Fully Interactive Dashboard**: Seamless navigation through Flexdashboard and Plotly.

## 🛠 Technologies Used

- **R Programming Language**
- **Flexdashboard** for dashboard creation
- **Plotly** for interactive charts
- **Highcharter** for geographic visualizations
- **RPivotTable** for dynamic pivot tables
- **dplyr**, **tidyr** for data preprocessing

  ## 📈 Dataset Details

- **Source**: [Kaggle - Vehicle Failure Dataset](https://www.kaggle.com/)
- **Attributes**:
  - `fm`: Failure Month
  - `Mileage`: Vehicle mileage at time of failure
  - `lc`: Labor cost incurred
  - `State`: State where failure was reported
- **Preprocessing**:
  - Handled missing and anomalous values (e.g., negative failure months).
  - Summarized and filtered data for visualization readiness.

## 💡 Future Enhancements

- Build a **Shiny**-based version with advanced filtering options.
- Integrate **machine learning models** for predicting vehicle failure likelihood.
- Implement **live data ingestion** for real-time dashboard updates.
- Add **download/export options** for reports and summaries.


##💡 Future Enhancements
- Build a Shiny-based version with advanced filtering options.
- Integrate machine learning models for predicting vehicle failure likelihood.
- Implement live data ingestion for real-time dashboard updates.
- Add download/export options for reports and summaries.


## 📂 Project Structure

```bash
├── Dashboard.Rmd          # RMarkdown source file (main dashboard code)
├── Dashboard.html         # Rendered interactive dashboard (output)
├── vehicle.csv             # Raw dataset used for analysis
├── README.md               # Project documentation (this file)

