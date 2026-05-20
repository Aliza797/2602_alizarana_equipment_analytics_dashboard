# Predictive Maintenance & Equipment Risk Dashboard

## About This Project

This project is based on predictive maintenance analysis using equipment operational data.  
I performed data analysis in Python and created an interactive dashboard in Power BI to understand equipment failures and risk patterns.

The main aim of this project was to:
- analyze machine failure behavior,
- identify high-risk equipment,
- and study how factors like torque and tool wear affect failures.

This project also helped me improve my skills in:
- Exploratory Data Analysis (EDA)
- Power BI dashboard development
- Data visualization and reporting

## Tools Used

### Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Power BI
- KPI Cards
- Interactive Charts
- Filters & Slicers
- Risk Analysis Dashboard


## Dataset Information

The dataset contains machine and operational information such as:

Column 	Description
Product ID	Unique Equipment ID
Type	Equipment Category
Torque_nm	Operational Torque Value
Tool_Wear_min	Tool Wear Duration
Failure_Type	Type of machine failure
Target	Failure indicator
Risk_Level	Risk Classification



## Dashboard Overview

The dashboard includes:

- Total Equipment Count
- Failure Rate %
- Average Torque
- High-Risk Equipment Count
- Type of Equipment
- Failure Type Analysis
- Equipment Risk Distribution
- Equipment Count by Type
- Torque vs Tool Wear Analysis
- High-Wear Equipment Table


## Key Insights

- Heat Dissipation Failure was the most common failure type.
- Most equipment belonged to the low-risk category.
- Higher tool wear showed increased operational risk.
- Type L equipment had the highest count in the dataset.
- Torque and tool wear showed noticeable operational patterns.

More detailed findings are available in:
[Insights.md]

## Dashboard Screenshot

Predictive Maintenance Dashboard.png


## Files Included

FILE NAME	DESCRIPTION
equipment predictive maintenance.ipynb	Python analysis notebook
Equipment_analytics_dashboard.pbix	Power BI Dashboard File
Predictive Maintenance Dashboard.png	Dashboard screen shot
README.md	Project overview
Insights.md	Analysis, Findings and observation


## Challenges Faced

One challenge during this project was handling dense scatter plot data and making the dashboard visuals more readable and organized.


## Future Improvements

In the future, I would like to:
- add machine learning models for failure prediction,
- improve dashboard design,
- and implement real-time monitoring features.


## Author

Aliza Rana 
GitHub: https://github.com/Aliza797