# 🗂️ Dataset Instructions

This folder is used to store the **Ames Housing Dataset** files required for the House Price Prediction project. The actual dataset files are not included in this repository due to size and licensing constraints.

## 📥 How to Download

1. Visit the official Kaggle competition page:  
   https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

2. Download and place the following files inside this `data/` folder:
   - `train.csv` — training data with features and target `SalePrice`
   - `test.csv` — test data without the target
   - `sample_submission.csv` — example format for predictions
   - `data_description.txt` — full column explanations

> ⚠️ These files are **ignored in version control** via `.gitignore`.

## 📊 Dataset Summary

The dataset includes 79 features describing residential homes in Ames, Iowa, such as:
- **LotArea**: Lot size (sq ft)
- **OverallQual**: Overall material/finish quality (1–10)
- **YearBuilt**: Original construction year
- **GrLivArea**: Above-ground living area (sq ft)
- **GarageCars**: Size of garage in car capacity
- **FullBath / HalfBath**: Bathrooms above grade
- **KitchenQual**: Kitchen quality
- **Neighborhood**: Physical location within Ames

The target variable is:
- **SalePrice**: Final selling price of the house (USD)

For full feature definitions, refer to `data_description.txt`.

