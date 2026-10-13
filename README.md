# Automobile Data Analysis

**Author:** MARISON EMILE

## Project Overview

This project explores an automobile dataset to identify relationships between vehicle characteristics and price. The analysis was performed using Python, Pandas, NumPy, and Matplotlib in Google Colab.

## Project Objectives

* Load and inspect the automobile dataset.
* Clean missing and invalid values.
* Analyze automobile price distributions.
* Explore relationships between price and vehicle characteristics.
* Present findings using descriptive statistics and visualizations.

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab

## Dataset and Data Cleaning

The original dataset contained 205 rows and 26 columns. After removing four records with missing prices and handling the remaining missing values, the cleaned dataset contained 201 rows and 26 columns.

Missing-value markers represented by `?` were converted to missing values. Numerical missing values were handled using median imputation, while missing values in the `num-of-doors` column were filled using the mode.

## Key Findings

* The automobile price distribution is right-skewed, with most vehicles concentrated in lower price ranges.
* Engine size has a strong positive correlation with price (**0.8723**).
* Horsepower has a strong positive correlation with price (**0.8105**).
* Highway MPG and city MPG have negative correlations with price (**-0.7047** and **-0.6866**, respectively).
* Hardtops and convertibles have the highest average prices among the body styles analyzed.
* Diesel vehicles have a higher average price than gasoline-powered vehicles in this dataset.
* The most expensive vehicle in the cleaned dataset is a Mercedes-Benz hardtop priced at **45,400**.

## Skills Demonstrated

* Data cleaning and preprocessing
* Missing-value handling
* Descriptive statistics
* Correlation analysis
* Data grouping and aggregation with Pandas
* Data visualization
* Analytical interpretation and reporting

## Conclusion

The analysis suggests that engine size, horsepower, fuel efficiency, body style, and fuel type are useful characteristics to explore when analyzing automobile prices. These findings describe relationships within the dataset and do not establish causation.

## Project File

[View the Jupyter Notebook](Automobile_Data_Analysis_MARISON_EMILE.ipynb)

