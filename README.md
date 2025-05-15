# Car Dataset Analysis

This project involves a comprehensive exploration and analysis of a car dataset to understand the key factors that influence car pricing, fuel efficiency, and market segmentation.
The analysis includes data preprocessing, visualizations, statistical summaries, and insights derived from multivariate techniques.

## Project Structure

- `Car_Dataset.csv` — Raw dataset used for analysis
- `Car_Analysis.ipynb` — Python script performing the data analysis using Jupiter Notebook
- `Car_Analysis_Report.pdf` — Final report with visualizations and detailed explanations

## Analysis Objectives

- Clean and preprocess the data (handle duplicates, outliers, and missing values)
- Perform exploratory data analysis (EDA) through descriptive statistics and plots
- Investigate relationships between multiple variables using correlation and aggregation
- Provide insights into car pricing trends and segmentation by attributes like body style and drive type

## Key Findings

- **Outliers:** Managed using log transformation for some variables like price and engine size
- **Missing values:** Handled using median for numerical data and 'Unknown' for categorical
- **Correlations:**
  - Engine size, curb weight, and horsepower are strongly positively correlated
  - Fuel efficiency (mpg) is negatively correlated with engine size and car weight
- **Pricing trends:** Rear-wheel and luxury body styles like hardtops are generally more expensive
- **Market segmentation:** Useful insights for consumers and manufacturers to guide pricing and production decisions

## Full Report

To read the full detailed report including graphs, insights, and methodology, click below:

 [Car_Analysis_Report.pdf](./Car_Analysis_Report.pdf)

---

##  Academic Acknowledgment

This project was completed as part of the **COMP517 – Data Analysis** course at Auckland University of Technology, during Semester 2, 2023.

**Lecturer** Dr Akbar Ghobakhlou
**Teaching Assistant** Steven Pan
**Student:** Thuan Nguyen (ID: 23194073)



