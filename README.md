# Tesla Stock Price Prediction

## Project Overview
This project involves predicting Tesla stock prices using a Random Forest Regressor model. It includes data preprocessing, feature engineering, model training, and visualization of predictions.

## Dataset
The dataset used for this analysis is sourced from [Kaggle.com](https://www.kaggle.com/datasets/rpaguirre/tesla-stock-price)..

## Project Steps
1. **Data Preparation**:
   - Read the CSV file into a DataFrame.
   - Created new columns for High-Low Percentage (`HL_Perc`) and Close-Open Percentage (`CO_Perc`).
   - Defined the label column `PriceNextMonth` for future price prediction.

2. **Feature Engineering**:
   - Scaled the features for better model performance.
   - Split the data into training and testing sets.

3. **Model Building**:
   - Developed a Random Forest Regressor model.
   - Trained the model using the training data.
   - Evaluated the model with testing data to calculate confidence value.

4. **Prediction and Visualization**:
   - Used the model to predict future stock prices.
   - Visualized the actual and forecasted stock prices using matplotlib.

## Technologies Used
- **Python**: pandas, numpy, matplotlib, scikit-learn

## How to Run
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/Tesla-Stock-Price-Prediction.git
   cd Tesla-Stock-Price-Prediction
