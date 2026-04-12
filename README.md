# Customer Churn Prediction

## 1. Overview

This project aims to predict customer churn in a subscription-based business environment using machine learning techniques. Customer churn refers to customers who discontinue using a service, directly impacting revenue, customer lifetime value, and long-term business sustainability.

From a business perspective, retaining existing customers is more cost-effective than acquiring new ones. By identifying customers at risk of churning, organisations can implement targeted retention strategies such as personalized offers, improved customer support, and pricing adjustments.

This project approaches churn prediction as a binary classification problem, where the goal is to predict whether a customer will churn (Yes) or not (No).

---

## 2. Objectives

- Identify key drivers of customer churn  
- Build predictive models to classify churn risk  
- Evaluate model performance using appropriate metrics  
- Generate actionable business insights to reduce churn  

---

## 3. Data Understanding & Exploration

The dataset contains customer demographic, account, and service-related information. Key features include tenure, monthly charges, contract type, and service usage.

### 3.1 Key Observations

- Churn is not evenly distributed across customers  
- Certain features show strong relationships with churn behavior  
- Early indicators suggest behavioral and pricing factors influence churn  

---

## 3.2 Feature Relationships

### Tenure vs Churn
![Tenure vs Churn](tenure_vs_churn.png)

Customers who churn tend to have significantly lower tenure compared to those who stay. This indicates that customer attrition is more likely to occur early in the customer lifecycle.

From a business perspective, this highlights the importance of strengthening onboarding and early engagement strategies to improve retention.

---

### Monthly Charges vs Churn
![Monthly Charges vs Churn](monthly_charges_vs_churn.png)

Customers with higher monthly charges show a higher likelihood of churn. This suggests that pricing sensitivity plays a role in customer retention.

From a business standpoint, this may indicate a need to reassess pricing strategies, introduce bundled offerings, or provide targeted incentives for high-risk customers.

---

## 4. Data Preprocessing

The following steps were performed to prepare the data:

- Handling missing values  
- Encoding categorical variables  
- Feature scaling  
- Train-test split for model validation  

These steps ensure the dataset is structured appropriately for machine learning models.

---

## 5. Model Development

Multiple machine learning models were trained and evaluated:

- Logistic Regression  
- Decision Tree  
- Random Forest  

These models were selected to compare both simple and more complex approaches to classification.

---

## 6. Model Evaluation

### Confusion Matrix (Random Forest)
![Confusion Matrix](confusion_matrix.png)

The confusion matrix shows the model’s ability to correctly classify churn and non-churn customers.

- True Negatives: Customers correctly identified as not churning  
- True Positives: Customers correctly identified as churning  
- False Positives: Customers incorrectly flagged as churn  
- False Negatives: Customers who churned but were not identified  

---

### ROC Curve (Random Forest)
![ROC Curve](roc_curve.png)

The ROC curve evaluates the trade-off between true positive rate and false positive rate.

- The AUC score of approximately **0.82** indicates strong model performance  
- The model demonstrates good ability to distinguish between churn and non-churn customers  

---

## 7. Key Insights

- Churn is more likely among customers with **short tenure**  
- Customers with **higher monthly charges** are more at risk  
- Churn is influenced by identifiable patterns rather than random behavior  

These insights reinforce that churn can be proactively managed through targeted interventions.

---

## 8. Business Recommendations

Based on the findings, the following strategies are recommended:

- **Improve onboarding experience** to reduce early churn  
- **Introduce pricing strategies or bundles** for high-paying customers  
- **Target high-risk customers** using predictive outputs  
- **Implement retention campaigns** driven by model insights  

---

## 9. Conclusion

This project demonstrates how machine learning can be applied to predict customer churn and generate actionable business insights.

By combining data analysis with predictive modeling, organisations can shift from reactive to proactive customer retention strategies, ultimately improving customer lifetime value and operational efficiency.

---

## 10. Tools & Technologies

- Python  
- Pandas & NumPy  
- Scikit-learn  
- Matplotlib & Seaborn  
- Google Colab  
- GitHub  

---

## 11. Project Structure

```
customer-churn-prediction/
│
├── README.md
├── Maica_Erika_Catalan_Pillar_5_Capstone_Project.ipynb
├── tenure_vs_churn.png
├── monthly_charges_vs_churn.png
├── confusion_matrix.png
├── roc_curve.png
```

---

## 12. Author

**Maica Erika Catalan**  
Global Lead – Process Optimization & Innovation  
Automation & Analytics
