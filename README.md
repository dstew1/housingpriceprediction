# housingpriceprediction
🏠 Housing Price Prediction with XGBoost, Ridge &amp; LightGBM

A complete machine learning workflow to predict house prices using data from the [Kaggle Housing Competition](https://www.kaggle.com/competitions/home-data-for-ml-course).

## 🔍 Project Overview

This project:

- Preprocesses and engineers features
- Handles missing data
- Trains Ridge Regression, XGBoost, and LightGBM models
- Compares log-RMSE scores across models
- Tunes hyperparameters for XGBoost using manual search
- Blends predictions for improved accuracy

## 📁 Files

- `housing_price_estimate.py` — main training and evaluation script
- `housing_price_estimate.pynb` — ^ notebook format 
- `requirements.txt` — libraries used in this project

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/dstew/housing-price-prediction.git
   cd housing-price-prediction

2. Install requirements:
    ```bash
    pip install -r requirements.txt
    
3. Download the dataset from Kaggle and place train.csv, test.csv, and sample_submission.csv in the project root.

4. Run the script:
   ```bash
   python housing_price_estimate.py
  
## ✅ Results

Model	log-RMSE  

Ridge	0.1476  

XGBoost	0.1248  

LightGBM	0.1310

## 📈 Feature Importance (XGBoost)
A bar plot is displayed in the notebook showing the top 15 features impacting price.
   
  
