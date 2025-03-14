# Energy Consumption Prediction using XGBoost

## Project Overview
This project focuses on predicting energy consumption using the **AEP Hourly Consumption Dataset**, which is a subset of the **US Energy Consumption Dataset**. The model was built using **XGBoost**, a powerful gradient boosting algorithm. This project was inspired by **Rob Mulla's tutorials**, and due credit is given for the learning experience.

## Dataset
- **Source:** US Energy Consumption Dataset
- **Subset Used:** AEP (American Electric Power) hourly consumption
- **File Used:** `AEP_hourly.csv`
- **Description:** Contains hourly electricity consumption data for AEP, recorded over several years.

## Project Workflow
1. **Data Preprocessing**
   - Handled missing values (if any)
   - Feature engineering (e.g., time-based features)
   - Data normalization and transformation

2. **Exploratory Data Analysis (EDA)**
   - Visualized consumption trends
   - Identified seasonality and patterns

3. **Modeling with XGBoost**
   - Split data into train & test sets
   - Trained an **XGBoost regressor** to predict hourly energy consumption
   - Tuned hyperparameters for optimal performance

4. **Evaluation**
   - Used metrics like RMSE and MAE to evaluate the model
   - Compared predictions with actual energy consumption trends

## Results & Learning Experience
- **XGBoost performed well** in capturing the time-series trends of energy consumption.
- Feature engineering significantly improved model performance.
- Gained valuable insights into **energy consumption patterns**.
- Learned about **time-series forecasting with machine learning**.

## Conclusion & Future Improvements
- While the model performed well, **there are still significant errors** that could be reduced by adding more relevant features.
- Incorporating external factors such as **weather conditions, holidays, and economic indicators** may improve prediction accuracy.
- Experimenting with other time-series models like **LSTM or ARIMA** could provide better performance.

## How to Run the Project
### 1. Install Dependencies
```bash
pip install pandas numpy xgboost matplotlib scikit-learn
```

### 2. Run the Notebook
- Open the `XG_boost.ipynb` file in **Jupyter Notebook or VS Code**
- Run the cells step by step to see the data preprocessing, training, and evaluation

## Acknowledgments
Special thanks to **Rob Mulla** for his tutorials on machine learning and time-series forecasting, which provided valuable guidance for this project.


