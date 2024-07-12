# House Price Prediction in Bengaluru

## Overview
This project aims to predict the prices of houses in Bengaluru based on various features such as area type, location, size, and more. With the lingering impact of demonetization, the enforcement of the Real Estate (Regulation and Development) Act (RERA), and the lack of trust in property developers in the city, understanding property prices has become crucial for potential home buyers.

## Features
The dataset consists of the following features:

- **Area_type**: Describes the type of area.
- **Availability**: Indicates when the property can be possessed or when it is ready (categorical and time-series).
- **Location**: The location of the property in Bengaluru.
- **Price**: The value of the property in lakhs (INR).
- **Size**: The number of bedrooms (BHK) ranging from 1 to 10 or more.
- **Society**: The society to which the property belongs.
- **Total_sqft**: The size of the property in square feet.
- **Bath**: The number of bathrooms.
- **Balcony**: The number of balconies.

## Problem Statement
Given the 9 features (categorical and continuous), the goal is to build a model to predict the prices of houses in Bengaluru.

## Files
- **Notebook.ipynb**: This Jupyter notebook contains the complete code for data preprocessing, exploratory data analysis, model building, and evaluation.

## Steps to Run the Project
1. Ensure you have Python installed on your system.
2. Install the required libraries using:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook Notebook.ipynb
   ```
4. Run all the cells to see the data analysis, model building, and prediction steps.

## Conclusion
This project provides a comprehensive analysis of the factors affecting house prices in Bengaluru and builds a predictive model to help potential home buyers make informed decisions.
