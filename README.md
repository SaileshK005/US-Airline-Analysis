# US Airline Delay Analysis

## Overview
This project involves analyzing airline delay data to uncover key insights and build predictive models. The goal is to understand flight delay patterns, examine the effect of factors such as airport altitude and runway length, and build machine learning models to predict delays. The project also involves handling missing values, web scraping, data visualization, and model building.

## Data Sources
- **Flight Data**: Over 500,000 flight records
- **Airports Data**: 73,805 airport entries
- **Runways Data**: Information on runway length, surface, and conditions
- **Airline Information**: Scraped from [Wikipedia](https://en.wikipedia.org/wiki/List_of_airlines_of_the_United_States)

## Key Features
- **Data Aggregation**: Combined flight, airport, runway, and airline data into a single dataset with 95% missing value reduction.
- **Web Scraping**: Automated extraction of airline founding year data and airport passenger traffic from Wikipedia.
- **Exploratory Data Analysis (EDA)**: Identified patterns such as 70% of delays from Southwest Airlines and fewer delays on Day 6 of the week.
- **Data Visualization**: Used heatmaps and count plots to visualize correlations and delay patterns.
- **Model Building**:
  - Logistic Regression and Decision Tree models achieved **80% accuracy**.
  - 5-fold cross-validation applied to ensure robust model evaluation.

## Technology Stack
- **Python**: Data analysis and machine learning
- **Pandas, NumPy**: Data manipulation and cleaning
- **Matplotlib, Seaborn**: Data visualization
- **Scikit-Learn**: Model building and evaluation
- **BeautifulSoup**: Web scraping

## Results
- **Delay Patterns**: Identified strong correlations between airport altitude, runway length, and flight delays.
- **Best Performing Models**: Logistic regression and decision tree with 80% accuracy.
- **Recommendations**: Found that older airlines generally have better on-time performance.

## Future Improvements
Use more advanced models like Random Forest and Gradient Boosting to improve predictions.
Explore additional features such as weather data to further understand flight delay causes.
