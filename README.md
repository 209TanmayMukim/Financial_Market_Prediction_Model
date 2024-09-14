# Financial Market Prediction Model

## Project Overview
This project involves developing a predictive model for financial markets using historical data on prices and volumes of various assets. The model was built using Linear Regression and fine-tuned with feature engineering, regularization, and cross-validation techniques to improve accuracy.

## Dataset
The dataset includes the following features:
- Commodities: Natural Gas Price, Crude Oil Price, Gold Price, etc.
- Cryptocurrencies: Bitcoin Price, Ethereum Price, etc.
- Stocks and Indices: S&P 500 Price, Nasdaq 100 Price, Berkshire Price, etc.

The data was preprocessed by handling missing values, outliers, and performing feature scaling. The final dataset was split into training and testing sets using an 80-20 split.

## Model Development
The model was trained using a Linear Regression approach. Key steps included:
- Feature engineering and selection.
- Hyperparameter tuning using Ridge regularization.
- Cross-validation to ensure model generalization.
- Model evaluation using MAE, MSE, and RMSE.

The most significant feature influencing predictions was the `Nasdaq_100_Price`.

## Results
- **MAE on Testing Data**: 0.1657
- **MSE on Testing Data**: 0.04498
- **RMSE on Testing Data**: 0.2121

Cross-validation showed consistent model performance:
- **Mean Cross-Validation Score (MSE)**: 0.04589
- **Standard Deviation of Cross-Validation Scores (MSE)**: 0.00576

## Conclusion
This model provides robust predictions for financial asset prices and can be further enhanced by integrating more complex machine learning models or additional financial indicators.

## Repository Content
- `Tanmay Laxmikant Mukim_Jupiter Notebook_ML Internship.ipynb`: The Jupyter Notebook containing the entire workflow, from data preprocessing to model evaluation.
- `README.md`: This summary of the project.

## How to Run
1. Clone this repository: 
   ```bash
   git clone https://github.com/209TanmayMukim/Financial_Market_Prediction_Model.git
