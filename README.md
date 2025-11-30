Diamond Price Prediction – Machine Learning Project
📌 Project Overview

This project focuses on predicting the price of diamonds based on various attributes such as carat, cut, color, clarity, depth, and table. The goal is to compare multiple machine learning models and identify the one that provides the most accurate price predictions.

📂 Dataset

The dataset includes the following key features:

Carat – weight of the diamond

Cut – quality of the diamond cut

Color – color grading

Clarity – clarity level

Depth – total depth percentage

Table – width of the top of the diamond

Price – target variable

Dataset was cleaned, processed, and encoded before training the models.

🧹 Steps Performed
1. Data Preprocessing

Handling missing values

Label encoding for categorical features

Outlier removal

Train-test split

Feature scaling (where required)

2. Exploratory Data Analysis (EDA)

Visualizing price distribution

Relationship between carat and price

Heatmap of correlations

Boxplots to detect outliers

3. Model Building

The following machine learning models were trained and evaluated:

Linear Regression

Random Forest Regressor

K-Nearest Neighbors (KNN)

Decision Tree Regressor (optional)

📊 Model Performance
Model	Accuracy
Linear Regression	90.54%
Random Forest	98.19%
KNN	97.24%
📝 Conclusions
Random Forest – Accuracy: 98.19%

The Random Forest model is the best performer. Its high accuracy shows that it successfully captures complex and non-linear relationships in the data. It is the recommended model for predicting diamond prices.

KNN – Accuracy: 97.24%

The KNN model performs strongly and predicts prices with good accuracy. Slightly behind Random Forest, it may improve further with optimal k value tuning and feature scaling.

Linear Regression – Accuracy: 90.54%

Linear Regression delivers decent but lower accuracy compared to other models. The model’s assumptions of linearity may not fully match the dataset’s complexity, making it less suitable for precise predictions.

🛠️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook

🚀 How to Run the Project

Clone the repository

Install required libraries

pip install -r requirements.txt


Open the notebook

Run all cells to train the models

📌 Future Enhancements

Hyperparameter tuning for Random Forest & KNN

Deployment as a web app using Streamlit

Adding more advanced models like XGBoost or LightGBM

👤 Author

Radha Pacharkar
Data Analyst & Machine Learning Enthusiast
