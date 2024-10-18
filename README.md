# AirBnB Data Analysis
This project is a data analysis of Airbnb listings in New York City, focusing on exploring the dataset to uncover trends and insights. The analysis was conducted using Python and the Pandas library for data manipulation and cleaning, along with Seaborn and Matplotlib for visualization.

## Project Overview
The goal of this project was to explore the Airbnb dataset to better understand various patterns while using pandas fro data analysis. I used data cleaning techniques, feature engineering, and visualization tools to conduct this analysis.

## Dataset
The dataset used for this project contains Airbnb listings in New York City. It includes information about room types, neighborhood groups, prices, reviews, and other listing details.

## Key Steps
### Data Loading and Cleaning

Loaded the dataset using Pandas.<br/>
Cleaned null values and dropped duplicate rows to ensure data quality.<br/>

## Exploratory Data Analysis (EDA)
Analyzed the price distribution across different neighborhood groups and room types using visualizations.<br/>
Engineered features to compare prices by neighborhood group with room type as a distinguishing factor (hue set to room type).<br/>
Explored the relationship between the number of reviews and price.<br/>
Used a pairplot to investigate correlations between integer-type columns.
## Geospatial Analysis

Visualized room types by mapping them against longitude and latitude to understand geographic distribution across the city.
## Correlation Analysis

Generated a correlation heatmap for key integer-type columns to observe potential relationships between features.<br/>
## Findings
Price vs. Neighborhood and Room Type: There were notable price variations across different neighborhood groups and room types.
Room Type by Location: Certain room types were more concentrated in specific geographic areas.
Key Insight: The most important factor influencing price was found to be the number of beds available in the listing.
##Technologies Used
Pandas: For data loading, cleaning, and manipulation.
Seaborn & Matplotlib: For visualizing price distributions, feature correlations, and geographic data.

Jupyter Notebook: As the development environment.
## Future Work
Deep dive into more granular price predictors.
Incorporate additional variables for improved price modeling.
Explore machine learning techniques for price prediction.
## Conclusion
This analysis provides a basic overview of the Airbnb dataset in NYC. It explores how key features like neighborhood group, room type, and number of beds relate to various aspects of the listings. Future extensions can further refine the insights and improve predictions using more advanced models.

