Task 1: Bank Marketing (Term Deposit Prediction)

Tools:
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SHAP

• Loaded dataset and explored features
• Encoded categorical variables
• Scaled numerical data
• Trained Logistic Regression and Random Forest
• Evaluated using Confusion Matrix, F1-Score, ROC Curve
• Applied SHAP for explainability

Results:
• Random Forest performed better
• Good ROC AUC score achieved

Insights:
• Duration is most important feature
• Campaign outcome affects subscription
• Most customers do not subscribe

Task 2: Customer Segmentation (K-Means)

Tools:
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

• Loaded dataset and performed EDA
• Encoded Gender feature
• Standardized features
• Applied K-Means clustering
• Used Elbow Method to find optimal clusters
• Visualized clusters using PCA

Results:
• Optimal clusters = 5
• Clear customer segmentation achieved

Insights:
• High income high spending = premium customers
• Low income high spending = impulsive buyers
• Segmentation helps targeted marketing


Task 3: Energy Consumption Forecasting

Tools:
Python, Pandas, NumPy, Scikit-learn, Statsmodels, Prophet, XGBoost

• Loaded and cleaned dataset
• Converted and processed datetime values
• Resampled data to hourly frequency
• Created time-based features
• Split data into train and test sets

Models Used
• ARIMA
• Prophet
• XGBoost

Evaluation
• MAE
• RMSE
• Model comparison

Results
• XGBoost performed best
• Prophet captured trends better than ARIMA
• ARIMA had lower accuracy

Insights
• Energy usage depends on time patterns
• Feature engineering improves performance
• ML models outperform ARIMA in this dataset
