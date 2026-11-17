🚗 Automobile Price Prediction

📌 Project Overview

The main objective of this project is to develop a Machine Learning model to predict automobile prices based on various independent features.

This project analyzes automobile data and identifies how different car features influence the selling price.

🎯 Project Objectives

- Perform Exploratory Data Analysis (EDA).
- Clean and preprocess the automobile dataset.
- Identify important features affecting car prices.
- Build multiple Machine Learning regression models.
- Compare model performance.
- Select the best-performing model for further evaluation.

📂 Dataset Description

The dataset contains automobile information, including:

- Symboling
- Normalized Losses
- Make
- Fuel Type
- Body Style
- Drive Wheels
- Engine Size
- Horsepower
- Curb Weight
- City MPG
- Highway MPG
- Price

Target Variable: "price"

🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- CatBoost
- Joblib

⚙️ Project Workflow

1. Data Collection
2. Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis
5. Data Preprocessing
6. Feature Selection
7. Train-Test Split
8. Feature Scaling
9. Model Building
10. Model Evaluation
11. Model Comparison
12. Best Model Selection

🤖 Machine Learning Models

The following regression algorithms were implemented:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. AdaBoost Regressor
5. Gradient Boosting Regressor
6. XGBoost Regressor
7. CatBoost Regressor

📊 Model Performance

Model| R² Score
Linear Regression| 88.31%
Decision Tree| 83.33%
Random Forest| 96.51%
AdaBoost| 93.30%
Gradient Boosting| 96.79%
XGBoost| 96.44%
CatBoost| 95.25%

Best Performing Model: Gradient Boosting Regressor

R² Score: 96.79%

📈 Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

📁 Project Structure

Auto-Price-Prediction/
│
├── AutoPricePrediction.ipynb
├── README.md
│
└── dataset/
    └── Automobile_data.csv

▶️ How to Run the Project

1. Clone this repository.
2. Install the required Python libraries.
3. Open Jupyter Notebook.
4. Open "AutoPricePrediction.ipynb".
5. Run all cells in execution order.

🏁 Conclusion

This project demonstrates how Machine Learning regression algorithms can be used to predict automobile prices.

Among the evaluated models, Gradient Boosting Regressor achieved the highest R² score of 96.79%.

The project helped develop practical knowledge of data analysis, data preprocessing, visualization and Machine Learning model evaluation.
