# Mobile Price Classification & Web Deployment Assignment

## a. Problem Statement
To build, evaluate, and deploy five machine learning classification models using the Mobile Price Classification dataset via an interactive Streamlit web application.

## b. Dataset Description
- **Source:** Kaggle (Mobile Price Classification Dataset by Abhishek Sharma)
- **Total Instances:** 2,000 rows (Satisfies requirement of >= 500)
- **Total Features:** 20 columns (Satisfies requirement of >= 12)
- **Target Variable:** price_range (Multi-class: 0, 1, 2, 3)

## c. GitHub Repository Link
https://github.com/2026aj05670-wq/mobile_price_app.git

## d. Models Used & Performance Comparison
| ML Model Name | Accuracy | AUC | Precision | Recall | F1 | MCC |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Logistic Regression** |  0.7325 | 0.9214 | 0.7356 | 0.7325 | 0.7338 | 0.6426 |
| **Decision Tree** | 0.8325 | 0.8888 | 0.8337 | 0.8325 | 0.8316 | 0.7769 |
| **KNN** | 0.9425 | 0.9904 | 0.9430 | 0.9425 | 0.9426 | 0.9233 |
| **Naive Bayes** | 0.7975 | 0.9582 | 0.8061 | 0.7975 | 0.7994 | 0.7313 |
| **Support Vector Machine** | 0.9650 | 0.9984 | 0.9655 | 0.9650 | 0.9650 | 0.9534 |

### Observations on Model Performance
- **Logistic Regression:** Stable linear separation across price tier boundaries.
- **Decision Tree:** Splits key specifications like RAM and battery capacity into non-linear branches.
- **KNN:** Evaluates distance similarities accurately using neighboring specifications.
- **Naive Bayes:** Computes fast probabilistic classifications based on feature independence.
- **Support Vector Machine:** Maximizes hyper-plane margins effectively for multi-class prediction.
- **Overall Winner:** State which model scored highest across your evaluation metrics.
