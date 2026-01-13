# Customer Purchase Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting customer purchase behavior using multiple classification algorithms. The goal is to analyze customer demographics and behavioral data to determine whether a customer is likely to make a purchase.

---

## 📂 Models Implemented
The following classification models were evaluated:

- Logistic Regression  
- Decision Tree Classifier  
- K-Nearest Neighbors (KNN)  
- Random Forest Classifier  

---

## 📊 Model Performance Summary

### 🔹 Logistic Regression
- **Accuracy:** 83.67%  
- **Precision:** 87.62%  
- **Recall:** 71.88%  
- **F1 Score:** 78.97%  

Logistic Regression demonstrated reasonable performance with high precision, indicating effective identification of likely purchasers. However, its lower recall shows that it missed a significant number of actual buyers, limiting its overall effectiveness.

---

### 🔹 Decision Tree Classifier
- **Accuracy:** 89.67%  
- **Precision:** 91.45%  
- **Recall:** 83.59%  
- **F1 Score:** 87.35%  

The Decision Tree model achieved a balanced performance across all metrics. It effectively captured both potential and actual buyers, making it a strong improvement over Logistic Regression.

---

### 🔹 K-Nearest Neighbors (KNN)
- **Performance:** Moderate to High  

The KNN model produced competitive results when trained on scaled features. While it outperformed Logistic Regression, its consistency was slightly lower than tree-based models, particularly when handling complex decision boundaries.

---

### 🔹 Random Forest Classifier
- **Accuracy:** 95.33%  
- **Precision:** 99.14%  
- **Recall:** 89.84%  
- **F1 Score:** 94.26%  

The Random Forest model outperformed all other classifiers. It demonstrated excellent predictive capability, achieving high precision and recall. The strong F1 score highlights its robustness and reliability.

---

## ✅ Conclusion
Among all evaluated models, **Random Forest** emerged as the best performer for predicting customer
