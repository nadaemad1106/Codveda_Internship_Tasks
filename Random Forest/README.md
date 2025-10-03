# 🧠 Sentiment Classification using Random Forest

This project builds a **machine learning model** to classify text into **Positive, Negative, or Neutral sentiment** using **TF-IDF + Random Forest with SMOTE balancing**.

---

## 🚀 Project Workflow

1. **Data Preprocessing**
   - Clean text and drop missing values
   - Auto-map noisy sentiment labels to `{Positive, Negative, Neutral}`

2. **Feature Extraction**
   - Convert text using **TF-IDF Vectorization** (max 8000 features)

3. **Class Balancing**
   - Apply **SMOTE oversampling** to handle imbalance

4. **Model Training & Tuning**
   - Train **Random Forest Classifier**
   - Optimize using **GridSearchCV**

5. **Model Evaluation**
   - **Cross-validation (F1 Macro)**
   - **Classification Report & Confusion Matrix**
   - **Feature Importance Analysis**

---

## 📊 Final Results

| Metric | Value |
|--------|-------|
| **Accuracy** | 0.97 |
| **Cross-Validation F1 (Macro)** | 0.95 |

| Class     | Precision | Recall | F1-score |
|-----------|-----------|--------|----------|
| Negative  | 1.00      | 0.98   | 0.99     |
| Neutral   | 0.92      | 0.98   | 0.95     |
| Positive  | 0.98      | 0.94   | 0.96     |

✅ **Consistent and well-balanced performance across all sentiment classes**  
✅ **No signs of overfitting**

---

## 🛠 Tech Stack

- Python  
- Scikit-Learn  
- Pandas  
- Imbalanced-Learn (SMOTE)  
- Matplotlib / Seaborn  
