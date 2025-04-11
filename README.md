# Stock Market Prediction

A machine learning project aimed at predicting stock prices using historical data. This project applies supervised learning algorithms to forecast future stock prices and analyze model performance.

---

##  Dataset

- **File Used**: `Stocks data.csv`
- **Source**: Custom dataset containing historical stock price data
- **Columns Included**:
  - `Date`
  - `Open`
  - `High`
  - `Low`
  - `Close`
  - `Volume`

---

##  Methodology

###  Data Preprocessing
- Removed missing/null values
- Converted date strings to datetime objects
- Normalized/standardized numerical columns

###  Feature Engineering
- Added daily returns
- Created lag variables (e.g., previous day’s close)
- Calculated moving averages

###  Model Building
Trained the following regression models:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**

###  Evaluation Metrics
- Root Mean Squared Error (RMSE)
- R² Score
- Visual comparison of predicted vs. actual values

---

##  Results Summary

- **Best Performing Model**: Random Forest Regressor  
- **Highlights**:
  - Captures nonlinear patterns well
  - Outperforms linear model in short-term trend prediction

>  Exact RMSE and R² values can be found in the notebook and presentation file.

---

##  Presentation Report

A detailed walkthrough of the project, model performance, and interpretation is available in:



---

##  How to Run This Project

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Python Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

###  Steps

1. Clone the repo:
   ```bash
   git clone https://github.com/pawarprerna/Stockmarket-prediction.git
   cd Stockmarket-prediction
