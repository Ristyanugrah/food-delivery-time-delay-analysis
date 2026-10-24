# Food Delivery Time & Delay Risk Analysis

## Project Overview
This project explores food delivery performance and potential delay risks using Python and Tableau Public. The analysis focuses on delivery time, distance, preparation time, courier experience, weather, and traffic conditions.

## Objectives
- Understand delivery time patterns.
- Explore factors associated with delivery duration.
- Compare late delivery rates across distance groups.
- Identify unusually long delivery orders.
- Provide data-driven operational recommendations.

## Dataset
The dataset contains 1,000 orders and 9 columns.

Key variables include:
- Distance
- Weather
- Traffic Level
- Time of Day
- Vehicle Type
- Preparation Time
- Courier Experience
- Delivery Time

## Tools
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Google Colab
- Tableau Public

## Project Workflow
1. Data Understanding
2. Data Quality Assessment
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Correlation Analysis
6. Delay Risk Analysis
7. Key Findings and Recommendations

## Key Findings
- Average delivery time: 56.73 minutes.
- Median delivery time: 55.50 minutes.
- Distance has a positive correlation with delivery time (0.781).
- Preparation time has a positive correlation with delivery time (0.307).
- Courier experience has a weak negative correlation with delivery time (-0.089).
- Six orders exceeded the 116-minute IQR upper threshold.

## Limitations
The 116-minute threshold is an exploratory outlier threshold, not an official delivery SLA.

Distance-based delivery targets are analyst-defined assumptions, not official company standards. Correlation indicates association, not causation.

## Repository Contents
- `Food_Delivery_Times_Analysis.ipynb` — analysis notebook.
- `Food_Delivery_Times_Cleaned.csv` — cleaned dataset.

## How to Use
1. Open the notebook in Google Colab.
2. Upload the cleaned dataset or update the file path.
3. Run the notebook cells in order.

## Author
Risty Anugrah

Data Analyst Portfolio Project
