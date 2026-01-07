# Credit Default Risk Modeling

## Overview
This project focuses on building and evaluating predictive models to assess **credit default risk** using customer demographic, financial, and behavioral data. The goal is to compare multiple classification approaches and identify a model that best supports **lending and underwriting decisions**, with particular attention to performance on an **imbalanced dataset**.

The analysis progresses from interpretable baseline models to more advanced ensemble methods, highlighting trade-offs between accuracy, recall, and overall risk discrimination.

---

## Dataset
- Credit card customer data with demographic, financial, and behavioral features  
- Binary target variable indicating default status  
- Class imbalance present (~22% default rate)

---

## Modeling Approach
The following classification models were implemented and benchmarked:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- XGBoost  

Models were evaluated using:
- ROC-AUC (primary ranking metric)  
- Precision, recall, and F1-score  
- Confusion matrices  
- Precision–Recall curves  

This evaluation framework supports both predictive performance assessment and financial risk interpretation.

---

## Key Results
- Ensemble models significantly outperformed baseline Logistic Regression.  
- ROC-AUC improved from **0.72 (Logistic Regression)** to **0.79 (Random Forest)**.  
- Recall increased from **24%** to approximately **35–36%**, improving identification of high-risk borrowers.  
- Overall accuracy remained stable at ~81%, reinforcing the importance of ROC-AUC and recall in imbalanced credit datasets.

**Recommended model:** Random Forest, based on superior ranking performance and balanced precision–recall behavior.

---

## Business Relevance
In credit risk applications, missed defaults (false negatives) can be costly. This project emphasizes:
- Evaluating models beyond accuracy  
- Understanding precision–recall trade-offs  
- Aligning model selection with business risk tolerance  

Threshold tuning and cost-sensitive learning are identified as next steps for deployment-oriented use.


---

## Tools & Technologies
- Python  
- pandas, NumPy  
- scikit-learn  
- XGBoost  
- Matplotlib / Seaborn  

---

## Future Improvements
- Threshold optimization based on business objectives  
- Cost-sensitive or class-weighted modeling  
- Model explainability using SHAP values  
- Probability calibration for deployment readiness  

---

## Author
**Cody Paquette**  
Data Science | Financial Analytics
