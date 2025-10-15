# Sydney Housing Price vs. Crime Analysis

Explores the relationship between suburban crime rates and average housing prices across Sydney suburbs.

## Quick look
- Data sources: suburb-level house prices, suburb metadata, crime counts
- Model: Linear Regression on standardized features
- Key metrics (from notebook):
  - **MSE ≈ 0.8228**, **RMSE ≈ 0.9071**
  - **R² ≈ 0.1605** (limited features → modest explanatory power)

## Data
- `SuburbData2022.csv`
- `SydneyHousePrices.csv`
- `sydney_suburbs.csv`

## Method
1. Merge price, location, and crime data
2. Standardize features; EDA + correlation inspection
3. Linear Regression to estimate relationship
4. Error analysis and outlier checks

## Results & interpretation
- Negative correlation between crime and price visible in EDA
- Low R² suggests more features are needed (income, distance to CBD, transport, schools)
- Coefficients printed in notebook (standardized scale)

jupyter lab
# open the notebook and run all
