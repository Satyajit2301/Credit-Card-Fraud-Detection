# 💳 Credit Card Fraud Detection using Logistic Regression

This project applies a supervised ML approach to detect fraudulent credit card transactions on a severely imbalanced dataset from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

## 📁 Dataset Details

- 284,807 total transactions
- Only 492 (~0.17%) are fraudulent
- Features are anonymized and transformed using PCA

## 🧪 ML Approach

- Used Logistic Regression with `max_iter=8000`
- Trained model using an 80-20 train-test split
- Evaluated model on accuracy metric

## 📊 Results

- **Training Accuracy**: 99.4%
- **Testing Accuracy**: 99.4%

While the model achieves high accuracy, due to class imbalance, precision, recall, or F1-score should be used for better evaluation.

## 🔍 Improvements

- Apply SMOTE for oversampling
- Use confusion matrix, precision, recall, F1
- Try more robust classifiers: Random Forest, XGBoost

## 💡 Libraries Used

- pandas, numpy
- scikit-learn

---

This project is a basic proof-of-concept. For production-grade fraud detection, more advanced models and real-world sampling techniques are essential.

