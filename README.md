# Customer Churn Prediction

A machine learning project that predicts customer churn for a telecom company using Logistic Regression, with actionable business insights.

## 📊 Project Overview
This project analyzes customer data from a telecom company to predict whether a customer will churn (leave the company) or not. Beyond just prediction, it identifies key factors driving churn to help the business take proactive retention actions.

## 🛠️ Tech Stack
- Python
- Pandas (data cleaning & preprocessing)
- Scikit-learn (model building & evaluation)

## 🔍 Process
1. **Data Cleaning**: Fixed data type issues in TotalCharges column, handled missing values
2. **Feature Engineering**: Encoded 15+ categorical variables using one-hot encoding
3. **Model Training**: Built a Logistic Regression model on 80/20 train-test split
4. **Evaluation**: Achieved **82% accuracy**, with detailed Precision/Recall analysis
5. **Feature Importance**: Identified top drivers of customer churn

## 📈 Results
- **Accuracy**: 82%
- **Precision (Churn)**: 69%
- **Recall (Churn)**: 60%

## 💡 Key Business Insights
The analysis revealed that customers are most likely to churn if they:
- Use **Fiber Optic internet service**
- Are on **Paperless Billing**
- Pay via **Electronic Check**
- Subscribe to **Streaming Movies**

### Business Recommendation
The company should focus retention efforts on Fiber Optic customers using Electronic Check payments, as this segment shows the highest churn risk. Offering incentives for auto-pay methods could help reduce churn in this group.

## 🚀 Future Improvements
- Compare performance with Random Forest and XGBoost
- Address class imbalance using SMOTE
- Deploy model as a simple web app for business users
