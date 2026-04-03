# Exploratory-data-analysis-of-a-2014-automobile-dataset

An in-depth exploratory data analysis of automobile specifications to uncover insights into pricing, fuel efficiency, and manufacturer trends.

 Overview

This project explores an automobile dataset containing 200+ vehicle models from various manufacturers. The goal was to understand key factors influencing car prices, fuel efficiency, and overall vehicle characteristics.

Through data cleaning, analysis, and visualisation, this project highlights meaningful patterns and relationships within the dataset.

 Objectives

The analysis was guided by the following questions:

Which are the most expensive cars in the dataset?
Which manufacturer produces the most fuel-efficient vehicles?
Which vehicles have the largest engine capacity?
Which manufacturer has the most car models?
Is there a relationship between engine size and price?
How are body styles distributed across the dataset?
 Data Cleaning

Several data quality issues were identified and resolved:

Replaced missing values encoded as '?' with NaN
Converted numeric columns from object to appropriate numeric types
Removed irrelevant columns (symboling, normalized-losses)
Checked for and removed duplicate rows
Dropped rows with missing values to ensure analysis accuracy

 Final dataset: 174 rows, 24 columns

 Exploratory Data Analysis

The dataset was analysed to uncover:

Relationships between price and engine size
Differences in fuel efficiency across manufacturers
Distribution of vehicle body styles
Manufacturer representation in the dataset

Visualisations were used to clearly communicate findings and support insights.

 Key Insights
 Engine size vs price: There is a strong positive correlation (0.77), indicating that vehicles with larger engines tend to be more expensive
 Luxury brands dominate pricing: High-end manufacturers such as Mercedes-Benz, BMW, and Porsche consistently appear among the most expensive vehicles
 Fuel efficiency varies significantly: Audi recorded the highest average highway MPG, while some manufacturers lag behind due to heavier, high-performance models
 Toyota leads in model count: The dataset is unbalanced, with Toyota contributing the highest number of vehicles
 Body style trends: Sedans and hatchbacks dominate the dataset, reflecting common market preferences
 Visualisations

The project includes the following visualisations:

Bar chart of the top 5 most expensive vehicles
Fuel efficiency comparison by manufacturer
Scatter plot of engine size vs price (with trend line)
Bar chart of manufacturer model counts
Donut chart showing body style distribution
🛠️ Tools & Technologies
Python
Pandas
NumPy
Matplotlib / Seaborn
Jupyter Notebook
