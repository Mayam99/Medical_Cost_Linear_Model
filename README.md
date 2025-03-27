# Insurance Cost Prediction - Linear Regression

A simple linear regression model to predict medical insurance costs.

## What's Included
- Data cleaning & preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Linear regression model
- Model evaluation metrics

## Dataset
Used the [Insurance Dataset from Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance) with these columns:
- `age`: Age of patient
- `sex`: Gender
- `bmi`: Body Mass Index
- `children`: Number of children/dependents
- `smoker`: Smoking status
- `region`: Geographic region
- `charges`: Medical costs (target variable)

## Steps Performed
1. Loaded and cleaned the data
2. Converted categorical features (sex, smoker, region) to numerical
3. Added new features:
   - `age_squared` (age²)
   - `bmi_category` (underweight/normal/overweight/obese)
4. Split data into training (80%) and testing (20%) sets
5. Scaled numerical features
6. Trained a linear regression model
7. Evaluated using:
   - R² Score: 0.78
   - RMSE: 5890
   - MAE: 4210
