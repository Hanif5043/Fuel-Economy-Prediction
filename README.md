# Fuel Economy Prediction Project

## Overview
This project predicts the fuel economy (`city08`) of vehicles using EPA data. It preprocesses the data, engineers features, and trains multiple models, including:
- Linear Regression
- Random Forest
- XGBoost

## Dataset
The dataset includes fuel economy data for 2019 model-year vehicles from the U.S. EPA. Key features include:
- `barrels08`: Annual fuel consumption.
- `city08`: Fuel efficiency (city driving).
- `highway08`: Fuel efficiency (highway driving).
- `cylinders` and `displ`.

Source: [FuelEconomy.gov](https://www.fueleconomy.gov/feg/epadata/vehicles.csv).

## Requirements
Install the required Python libraries:
```bash
pip install pandas matplotlib seaborn scikit-learn xgboost pyarrow

