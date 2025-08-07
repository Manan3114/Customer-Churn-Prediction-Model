# Customer Churn Prediction using LightGBM

This project focuses on predicting customer churn using a machine learning pipeline built with LightGBM in Google Colab. The goal is to identify customers at high risk of leaving a service, enabling proactive retention strategies.

## 📌 Features

- 📊 *Exploratory Data Analysis (EDA)* to understand customer behavior and trends
- 🛠 *Feature Engineering* including handling missing values and categorical variables
- ⚙ *Model Training* using LightGBM with hyperparameter tuning
- 🧪 *K-Fold Cross-Validation* to ensure robust model evaluation
- 📈 *Model Evaluation* using ROC-AUC metric (Mean CV ROC-AUC: [0.7464])
- 🔍 *Feature Importance Analysis* for actionable business insights
- ☁ *Google Drive Integration* for model saving and project file management
- For training dataset , visit [Training data]([https://drive.google.com/file/d/1KcHtQx0R2PGl7c1yKdzL9te1aILh-HCc/view?usp=sharing]).


## 🚀 Getting Started

1. Open the churn_model_lightgbm.ipynb in Google Colab.
2. Mount Google Drive to save or load the trained model.
3. Run each section from data preprocessing to model evaluation.
4. Review final predictions and insights on churn probability.

## 📊 Results

- Achieved a mean ROC-AUC score of *[0.7464]* using K-Fold CV.
- Top churn predictors included:
- ContentDownloadsPerMonth
- UsagePerDollar
- AccountAge
- AverageViewingDuration
- SupportTicketsPerMonth
- MonthlyCharges
- ViewingHoursPerWeek
- UserRating
- TotalCharges
- WatchlistSize



## 📌 Dependencies

- Python 3.x
- LightGBM
- Scikit-learn
- Pandas, NumPy, Matplotlib, Seaborn

## 📫 Contact

For questions or feedback, please reach out via [GitHub Issues](https://github.com/manan3114/Customer-Churn-Prediction-Model/issues).
