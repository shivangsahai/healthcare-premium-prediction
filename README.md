# 🔥 Insurance Premium Prediction using Customer Segmentation

An end-to-end machine learning project that predicts **insurance premiums** by combining **customer segmentation** with **segment-specific regression models** to deliver more accurate and business-relevant predictions.

---

## 🚀 Project Overview

Insurance pricing is highly sensitive to customer characteristics.  
Using a single global model often leads to poor generalization across diverse customer groups.

This project solves that problem by:
- Segmenting customers into meaningful groups
- Training **separate models per segment**
- Comparing model performance with and without key risk-related features
- Generating **business-ready premium outputs**

---

## 🎯 Problem Statement

> How can insurance premiums be predicted more accurately while accounting for heterogeneous customer behavior?

**Objective:**
- Predict insurance premiums
- Improve accuracy through segmentation
- Deliver interpretable, deployable results

---

## 🧠 Solution Approach

1. **Customer Segmentation**
   - Segmented customers into:
     - **Young**
     - **Rest**
   - Motivation: different risk and premium dynamics across age groups

2. **Modeling Strategy**
   - Built **separate regression models** for each segment
   - Trained models:
     - With GR feature
     - Without GR feature
   - Compared results to understand feature impact

3. **Evaluation & Outputs**
   - Segment-wise prediction analysis
   - Exported predictions to Excel for business consumption

---

## 🤖 Algorithms Used

- Linear / Statistical Regression
- Gradient Boosting
- XGBoost (for enhanced non-linear modeling)

Each algorithm was chosen based on:
- Predictive performance
- Stability
- Interpretability

---

## 📂 Project Structure

```text
notebooks/   → Data segmentation, feature engineering, model training  
dataset/     → Input datasets  
outputs/     → Premium prediction results (Excel files)  
requirements.txt → Project dependencies  
