# Malaysia Crop Production & Weather Analysis

## Overview
This repository contains an exploratory data analysis (EDA) and data preprocessing pipeline for studying agricultural yields in Malaysia. The project integrates district-level crop production data with historical weather metrics to understand how environmental conditions affect different crop species.

## Dataset Information
- **Crop Production Data:** Sourced from `data.gov.my`, containing historical records of cassava, groundnuts, sweet corn, banana, and other crops across various Malaysian states and districts.
- **Weather Data:** Sourced from Kaggle, including hourly observations of temperature, humidity, and wind speed in Malaysia.

## Features
- **Data Cleansing:** Handles missing values, removes duplicates, and filters out zero-production outliers.
- **Feature Engineering:** Aggregates hourly weather data into seasonal averages (temperature, max humidity, and average wind speed) corresponding to harvest cycles.
- **Data Integration:** Merges disparate datasets using temporal (Year) and spatial (District/Place) keys.
- **Visualisation:** Includes distribution histograms for key features like production and temperature.

## Dependencies
The following Python libraries are required:
- `pandas`
- `matplotlib`
- `seaborn`
- `numpy`
- `scikit-learn`
- `fastparquet`

## How to Run
1. Open the `.ipynb` notebook in Google Colab or a local Jupyter environment.
2. Ensure you have access to the `full_weather.csv` file.
3. Run the "Package Installation & setup" cell to install the necessary libraries.
4. Execute the cells sequentially to perform data cleaning, merging, and visualisation.

## Future Work
- Implementation of regression models (Linear Regression, Random Forest) to predict production yields based on weather features.
- Analysis of specific state-level agricultural trends.
