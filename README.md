Air Quality Analysis

Overview
This project analyzes worldwide air quality data to compare Air Quality Index (AQI) levels between countries and cities.
It also explores relationships between different pollutants such as PM2.5, NO2, Ozone, and CO.

Dataset source:
Worldwide Air Quality Insights Dataset – OpenDataBay
https://www.opendatabay.com/data/science-research/08c51787-5d20-4697-9077-c70d3cd7a8fd

Dataset Description
Columns used in the analysis:

Country – name of the country
City – name of the city
AQI Value – overall Air Quality Index
AQI Category – air quality classification
CO AQI Value / Category – Carbon Monoxide
Ozone AQI Value / Category – Ozone
NO2 AQI Value / Category – Nitrogen Dioxide
PM2.5 AQI Value / Category – fine particulate matter

STEPS
Data Cleaning:
Removed duplicates
Removed rows with missing Country or City values

Analysis:
Average AQI by country
Top 20 cities with highest average AQI
Relationship between PM2.5 and NO2
Correlation between air quality variables

Visualizations:
Examples of visualizations saved in the "images" folder

Insights:
The analysis shows that air quality varies widely between countries, with some regions experiencing much higher pollution levels.
PM2.5 is the main factor influencing overall air quality, strongly correlated with AQI values.
PM2.5 and NO₂ tend to increase together, suggesting shared sources like traffic and industry.
Reducing PM2.5 emissions could lead to significant global air quality improvements.

Tools Used
Python
Pandas
Matplotlib
Seaborn
Plotly


Author
Created by Patrcyja Wardaszka-Pianka, 2025
