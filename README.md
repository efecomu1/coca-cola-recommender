# Coca-Cola Recommender System (ACSE Campaign)

This project develops a two-stage recommender system for ACSE Supermarket's Coca-Cola promotional campaign. It was built as part of the "AI & ML at Scale" course at Emory University.

## 📌 Objective
- Target competitors’ CSD customers without cannibalizing ACSE private-label sales.
- Recommend Coca-Cola SKUs based on behavioral patterns and co-occurrence metrics.

## 🧠 Methodology
- **Stage 1**: Filter eligible customers using logistic regression based on features like spend, frequency, churn, and brand overlap.
- **Stage 2**: Use collaborative filtering and product-level logistic regression to recommend high-affinity Coca-Cola SKUs.

## 🧪 Model Highlights
- Held-out accuracy: 80%
- Recall for actual buyers: 77%
- Precision filters and lift-based product relevance

## 🛠️ Tools & Tech
- Python (Pandas, Scikit-learn, XGBoost)
- Stratified decile sampling & effect size validation
- Logistic Regression, k-NN, Naive Bayes, Association Rule Mining

## 📄 Files
- `recommender_system_final.ipynb`: Final modeling notebook
- `report/`: Full write-up and business recommendations
