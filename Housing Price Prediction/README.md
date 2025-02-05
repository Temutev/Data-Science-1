## Problem Statement:
Consider a real estate company has a data set of the prices in the region of Delhi. It wishes to use the data to optimise the sale prices of the properties, based on important factors such as area, bedrooms, parking, etc.

## Essentially the company wants:
- To identify the variables affecting house prices, e.g. area, number of rooms, bathrooms, etc.
- To create a linear model that quantitatively relates house prices with variables such as the number of rooms, area, number of bathrooms, etc.
- To know the accuracy of the model, i.e. how well these variables predict house prices.

## Solution
- Data Preparation
  - categorical to numeric conversion
  - create dummy variable 
- Derived Variables
- Rescaling the features
  - Normalization
  - standardization
- Split data into train and test dataset
- Build multiple linear regression model
  - Check the variable significance using p-value and VIF
    - Manual way (removing column by column by checking it's p-value and VIF value)
    - Automated way (through Recursive Feature elimination function/utility)
- Model Evaluation
  - Measures like R-square, adjusted R-square
 
