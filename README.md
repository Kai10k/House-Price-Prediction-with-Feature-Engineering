# House Price Prediction with Feature Engineering

## Project Overview
This project builds a machine learning model to predict house prices based on various property features. The goal is to analyze housing data, engineer meaningful features, and train regression models to estimate property values accurately.

## Dataset
The dataset contains information about residential homes, including features such as:
- Lot size
- Overall quality of the house
- Year built
- Living area size
- Number of bathrooms
- Garage capacity

Target variable:
- **SalePrice** – the final sale price of the house.

## Objectives
- Perform data cleaning and preprocessing
- Conduct Exploratory Data Analysis (EDA)
- Apply feature engineering techniques
- Train machine learning models for price prediction
- Evaluate model performance and identify important features

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

### 1. Data Loading
Load the housing dataset and inspect its structure.

### 2. Data Cleaning
Handle missing values and remove unnecessary columns.

### 3. Exploratory Data Analysis
Analyze relationships between variables and house prices using visualizations.

### 4. Feature Engineering
Create new meaningful features such as:
- House age
- Total area
- Total bathrooms

### 5. Data Preparation
Convert categorical variables into numerical values using encoding.

### 6. Model Training
Train regression models including:
- Linear Regression
- Random Forest Regressor

### 7. Model Evaluation
Evaluate models using Root Mean Squared Error (RMSE).

### 8. Feature Importance
Identify which features have the greatest impact on house prices.

## Key Insights
- Larger living areas strongly increase house price.
- Overall quality rating is one of the most influential features.
- Newer houses tend to sell for higher prices.
- Garage capacity also affects property value.

## Results
Random Forest provided better prediction performance compared to Linear Regression, demonstrating the ability to capture complex relationships in the dataset.

## Future Improvements
- Hyperparameter tuning
- Use advanced models like Gradient Boosting or XGBoost
- Deploy model using a web application
- Create interactive dashboards

## Author
Data Science Project – House Price Prediction
