# BCR-ML

# 🎗 Predicting Early Breast Cancer Recurrence With Machine Learning

**Authors**: Gracie Abrahams, Gretchen Callahan, Dalia Karim, Tyler Madison  
**Advisor**: Dr. Mehdi Owrang, Computer Science Department, American University  
**Presented at**: 2025 Mathias Student Research Conference

---

## 🧠 Overview

This project addresses a critical gap in breast cancer research: the limited focus on **recurrence prediction**, especially **early recurrence (within 5 years)**. While many machine learning (ML) applications in oncology focus on diagnosis or prognosis, **early recurrence remains underexplored—despite its major implications for treatment planning, follow-up care, and patient survival**.

Using the METABRIC Breast Cancer dataset, we developed and evaluated ML models to identify which clinical and molecular features most strongly predict early recurrence. We emphasize **explainable AI (XAI)**—making ML models **transparent and understandable for both physicians and patients**—so that these tools can be used meaningfully in real-world healthcare settings.

---

## 🎯 Research Goals

- Address the **lack of early breast cancer recurrence research**
- Provide **interpretable, transparent machine learning models**
- Highlight the **limitations of current datasets** and the need for more comprehensive recurrence data
- Support **targeted doctor follow-ups and early intervention strategies**
- Make **recurrence risk understandable and actionable for patients**

---

## 🔍 Key Contributions

- Identified key predictors of early recurrence: **Luminal B tumor subtype**, **radiotherapy**, **tumor size**, and **3-year relapse-free status**
- Developed ML models (Random Forest, Multi-Layer Perceptron) with accuracies up to **79%**
- Applied **feature selection techniques** to optimize model interpretability and performance
- Prioritized **explainable AI** to communicate model outcomes clearly to healthcare providers and patients
- Highlighted **data limitations** in current research and proposed future directions

---

## 🧪 Methodology

**Dataset**: METABRIC Breast Cancer Dataset (filtered to include only patients with recurrence status within 60 months)

**Feature Selection Techniques**:
- Pearson Correlation
- Chi-Square Test
- SelectKBest
- Recursive Feature Elimination

**Modeling Techniques**:
- Random Forest Classifier
- Multi-Layer Perceptron (MLP)

**Evaluation Metrics**:
- Accuracy
- Precision
- Recall
- F1 Score

---

## 💬 Why Explainability Matters

One of our core goals is to show that **machine learning doesn't have to be a black box**. By using explainable models, we aim to:
- Help doctors make more informed follow-up decisions
- Help patients understand their recurrence risk in a transparent and accessible way
- Improve clinical trust and real-world applicability of AI tools

---

## 📁 Repository Contents

/poster → PDF of the research poster
📁 /code → ML code and feature selection scripts
📁 /data → Processed or sample dataset
README.md → You're here!



