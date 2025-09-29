# House_Price_Prediction-With-Regression-models


This project predicts house prices using different **regression models**.  
It’s designed for **beginners in Machine Learning**, showing step-by-step workflow:
- Data exploration
- Preprocessing
- Model training
- Evaluation
- Feature importance

---

## 📂 Dataset
The dataset contains housing features like:

- `Square_Footage`  
- `Num_Bedrooms`  
- `Num_Bathrooms`  
- `Year_Built`  
- `Lot_Size`  
- `Garage_Size`  
- `Neighborhood_Quality`  
- **Target** → `House_Price`

> Example file: `house_price_regression_dataset.csv`

---

## ⚙️ Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/house-price-regression.git
cd house-price-regression
pip install -r requirements.txt
Requirements
pandas

numpy

scikit-learn

xgboost

matplotlib, seaborn (for visualization)

🧭 Project Workflow
1. Exploratory Data Analysis (EDA)
Shape, columns, data types

Missing values, duplicates

Summary statistics

Correlation heatmap

2. Preprocessing
Train/test split

Feature scaling (for Linear Regression)

(Imputation if missing values exist)

3. Models
Linear Regression → Baseline

Random Forest Regressor → Handles non-linearity

XGBoost Regressor → Gradient boosting for higher accuracy

4. Evaluation
Metrics used:

RMSE (Root Mean Squared Error)

R² (Coefficient of Determination)
