# 🍔 Obesity Prediction with Decision Tree (CART & C5.0)

## 📌 Repository Description  
This repository contains my project on **obesity level prediction** using **Decision Tree models (CART & C5.0)**.  
The goal is to classify individuals into different obesity categories based on features such as **age, gender, dietary habits, and physical activity**.  

This project reflects my continued exploration of interpretable machine learning applied to health and lifestyle datasets.

---

## 🚀 Project Overview  
Obesity is a major health challenge worldwide, influenced by lifestyle and eating habits. Early detection of obesity levels helps in promoting better health interventions.  

In this project, I:  
- Preprocessed and explored the obesity dataset  
- Built and compared **Decision Tree (CART & C5.0) models**  
- Evaluated results using accuracy, confusion matrix, and classification report  
- Identified the most important features influencing obesity classification  

---

📈 Results & Observations
✅ Model Performance

Accuracy: ~96%

The Decision Tree model achieved high accuracy, showing strong predictive power on this dataset.

📊 Confusion Matrix

The majority of instances were classified correctly across obesity categories.

A few misclassifications occurred between adjacent categories (e.g., overweight vs. obese).

🧾 Classification Report

Precision, Recall, and F1-scores were strong across all classes.

The model performed especially well for underweight and obese classes.

Slight overlap observed in the normal vs. overweight categories due to lifestyle similarities.

🔑 Top Features Influencing Obesity

FAF (Physical Activity Frequency)

FCVC (Vegetable Consumption Frequency)

NCP (Number of Main Meals)

TUE (Technology Use per Day)

Age

🔎 Interpretation

The Decision Tree model provides transparent and interpretable decision rules, making it easy to understand why predictions were made.

Features related to eating habits (vegetables, meals per day) and activity patterns (exercise, technology use) were key determinants of obesity.

The model’s 96% accuracy demonstrates its effectiveness, though additional testing on unseen datasets is recommended to confirm generalization.

Future improvements:

Try ensemble methods (Random Forest, Gradient Boosting)

Perform cross-validation for more robust evaluation

Investigate class imbalance handling to improve fairness

✨ Personal Note

This project was exciting because obesity prediction combines lifestyle data with health insights.
I enjoyed interpreting how decision tree splits mirrored real-world health patterns.
Working on this strengthened my skills in building transparent, explainable AI models for healthcare applications.



