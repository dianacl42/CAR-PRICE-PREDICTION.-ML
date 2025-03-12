 Car Price Prediction Project

 🚗 Project Overview
What really determines the price of a car? This project leverages machine learning to predict car prices in the American market. The goal is to help a Chinese automobile company identify the key factors influencing car prices, allowing them to design competitive vehicles and develop data-driven marketing strategies.

 📊 Dataset Information
The dataset used in this project contains detailed specifications of various cars, such as:
- Model & Brand – Identifying the make and version of the car.
- Engine Size & Horsepower – Key performance indicators.
- Fuel Type – Whether the car runs on petrol, diesel, or another fuel type.
- Other Technical Features – Including drive type, dimensions, and more.

This dataset was sourced externally and preprocessed for better analysis.

 🎯 Project Goals
This project aims to:
- Identify the most significant factors affecting car prices.
- Build and compare different machine learning regression models.
- Select the most accurate model based on performance metrics.
- Optimize the best model using hyperparameter tuning for better predictions.

 🛠️ Tools & Technologies
This project utilizes the following tools and libraries:
- Python – Primary programming language.
- Jupyter Notebook – Interactive environment for coding.
- Pandas & NumPy – Data manipulation and preprocessing.
- Matplotlib & Seaborn – Data visualization.
- Scikit-learn – Machine learning model implementation.

🔧 Step-by-Step Implementation
 1️⃣ Data Preparation
- Loaded the dataset using Pandas.
- Displayed sample data to understand the structure and attributes.

2️⃣ Data Preprocessing
- Handled missing values through removal or imputation.
- Converted categorical data into numerical format.
- Split the dataset into **training (80%)** and **testing (20%)** subsets.
3️⃣ Model Development
Five regression models were implemented and compared:
- Linear Regression – A simple baseline model.
- Decision Tree Regressor – A non-linear approach to capture complex patterns.
- Random Forest Regressor – An ensemble technique improving accuracy.
- Gradient Boosting Regressor – A boosting method to reduce error.
- Support Vector Regressor (SVR) – A margin-based regression technique.

 4️⃣ Model Evaluation
Each model was evaluated based on:
- R² Score – Measures how well the model explains price variations.
- Mean Squared Error (MSE) – Captures prediction error magnitude.
- Mean Absolute Error (MAE) – Measures average deviation from actual prices.

 5️⃣ Feature Importance Analysis
- Used the Random Forest Regressor to determine which features had the greatest impact on car prices.
- Visualized the top 10 most influential factors using bar plots.

 6️⃣ Model Optimization
- Applied GridSearchCV to fine-tune hyperparameters of the best model.
- Re-evaluated performance to measure improvements.

🏆 Key Findings
The Random Forest Regressor emerged as the best-performing model, achieving the highest R² Score and lowest error rates. The most influential factors affecting car prices included:
- Engine Size – Larger engines generally lead to higher prices.
- Horsepower – More powerful cars tend to be more expensive.
- Car Brand & Model – Premium brands command higher prices.

📂 Project Files
Here’s how the project is structured:
- 📜 Car_Price_Prediction.ipynb – Contains all the machine learning code.
- 📄 README.md – Project documentation.
- 📂 Dataset Folder – Contains the dataset (if stored locally).

🔍 Conclusion
This project provided valuable insights into car pricing trends in the American market. The optimized **Random Forest model** enables accurate price predictions, which can help manufacturers:
- Design cars tailored to specific price segments.
- Develop data-driven pricing and marketing strategies.

Project by 
Dayana K J


