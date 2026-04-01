# Predicting Crop Production in Malaysia (WIA1006)

## Project Overview
This repository contains a Machine Learning project focused on predicting agricultural production yields in Malaysia. The goal is to determine how environmental factors—such as temperature, humidity, and wind speed—influence the harvest of different crop types across various districts.

The project is divided into two main stages: a dedicated data preprocessing pipeline and a model training and evaluation phase.

## Repository Structure
* **`Crop_Data_Preprocessing.ipynb`**: Handles the initial data cleaning, merging of agricultural and weather datasets, normalisation of features, and preparation of the final dataset.
* **`Crop_Prediction_Model.ipynb`**: Focuses on building, training, and comparing Machine Learning models (such as Linear Regression and Random Forest) and evaluating their predictive performance.

## Key Features
* **Data Integration:** Merging public sector agricultural data with historical climate records.
* **Data Preprocessing:** Cleaning missing values, handling categorical encoding for crop types, and feature scaling.
* **Model Comparison:** Implementation of different regression algorithms to find the most accurate predictor.
* **Performance Metrics:** Evaluation using R-squared ($R^2$), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

## Technologies Used
* **Language:** Python
* **Libraries:** `Pandas`, `NumPy`, `Scikit-learn`, `Matplotlib`, `Seaborn`, `Fastparquet`
* **Environment:** Google Colab / Jupyter Notebook

## Setup & Usage
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/JoecheleLim/Malaysia-Crop-Weather-Analysis.git](https://github.com/JoecheleLim/Malaysia-Crop-Weather-Analysis.git)
   ```
2. **Install Dependencies:**

   Run the following command to install the necessary Python packages:
```bash
pip install pandas scikit-learn matplotlib seaborn fastparquet
```
3. **Execution Order:**
* First, run `Crop_Data_Preprocessing.ipynb` to prepare the data.
* Then, run `Crop_Prediction_Model.ipynb` to train the models and view the results.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
