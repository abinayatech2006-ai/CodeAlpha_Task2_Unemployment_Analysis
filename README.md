Unemployment Analysis in India — CodeAlpha Internship Task 2

This project analyzes unemployment trends in India using publicly available unemployment datasets. The goal is to understand regional variations, monthly patterns, and the major spike during the Covid-19 pandemic.

Dataset
Source: Unemployment data for India
File Used: Unemployment_Rate_upto_11_2020.csv

Features:
Column	Description
Date	Time of data record
State	Indian state / region
Unemployment Rate	Percentage of unemployed individuals
Employed	Estimated employed population
Labour Participation Rate	Economic participation rate

Data Cleaning Steps
✔ Converted Date column into proper datetime format
✔ Removed duplicate/unusable records
✔ Standardized feature names
✔ Filtered missing unemployment values

Exploratory Data Analysis
1️) Trend visualization across states
2️) State-wise unemployment comparison
3️) Pre-Covid vs During-Covid trend difference
4️) National monthly unemployment rate change

Findings / Insights
Massive unemployment spike occurred during March–May 2020 due to lockdown.
Urban states showed higher unemployment volatility than rural-focused states.
Recovery started slowly but unemployment remained unstable for months.
Seasonal and regional patterns are strongly visible.

Visualizations Included
Line chart: State-wise unemployment trends
Bar chart: Average unemployment by state
Box plot: Covid-19 impact comparison
Time series chart: Monthly national unemployment trend
Seasonal decomposition

Output File
Cleaned_Unemployment_India.csv — processed dataset saved after cleaning
Python (Pandas, NumPy)
Matplotlib, Seaborn
Statsmodels (Seasonal decomposition)

Conclusion
India experienced one of the highest unemployment surges in decades during the Covid-19 lockdown. Although the situation improved later, employment instability continued throughout 2020.
