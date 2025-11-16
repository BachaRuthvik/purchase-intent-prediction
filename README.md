# Customer Purchase Intent Prediction  
**Author:** Ruthvik Bacha  
**Program:** MS in Business Analytics & Information Systems, University of South Florida  
**Duration:** Feb–Apr 2024  

---

## 📘 Overview
This project predicts **whether an online shopper will make a purchase** based on behavioral data from an e-commerce platform.  
Using the **UCI Online Shoppers Purchase Intention dataset**, the model provides actionable insights into session-level patterns that drive conversions.

---

## 🎯 Business Objective
E-commerce firms often face low conversion rates and poor personalization.  
This model aims to:
- Identify high-intent users in real time.
- Improve marketing efficiency via targeted recommendations.
- Increase revenue through predictive personalization.

---

## Methodology

1. **Data Understanding**  
   - Source: UCI Machine Learning Repository  
   - 12,330 records, 18 features  
   - Target: `Revenue` (True/False)

2. **Preprocessing**  
   - Handled missing values  
   - Encoded categorical features  
   - Addressed class imbalance with SMOTE  

3. **Feature Engineering**  
   - Derived session-level interaction metrics  
   - Standardized continuous variables  

4. **Modeling**  
   - Algorithms: Logistic Regression, Random Forest, XGBoost, Gradient Boosting  
   - Validation: 80/20 train-test split, F1-score focus  

5. **Results**  
   - **Best Model:** Gradient Boost  
   - **F1-score:** 0.90  
   - **Confusion Matrix:**  
     - TP: 424 | FP: 246 | FN: 151 | TN: 2878  

6. **Insights**  
   - Session duration and cart actions are top predictors.  
   - Customers spending >5 minutes and visiting >3 product pages have 3× higher purchase probability.

---

## 🧩 Tools & Libraries
| Category | Tools |
|-----------|--------|
| Data Prep | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Modeling | Scikit-learn, XGBoost |
| Evaluation | Cross-validation, ROC-AUC |
| IDE | Jupyter Notebook |

---

## 📊 Results Visualization
- `f1_scores.png` — Model performance comparison  
- `confusion_matrix.png` — Classification summary  
- `feature_importance.png` — Top drivers of purchase intent  

---

## 🔮 Future Scope
- Integrate with recommendation systems for real-time targeting  
- Use reinforcement learning for adaptive personalization  
- Extend dataset size for generalization testing  

---

## 🧾 References
- [UCI Machine Learning Repository – Online Shoppers Purchase Intention Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset)  

---

## 👤 Contact
**Ruthvik Bacha**  
📧 [ruthvikbacha@gmail.com](mailto:ruthvikbacha@gmail.com)  
📞 (656) 210-0386  
[LinkedIn](https://linkedin.com/in/ruthvikbacha) • [GitHub](https://github.com/BachaRuthvik)

---

