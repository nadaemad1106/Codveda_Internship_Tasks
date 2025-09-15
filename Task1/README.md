# Task 1 - Data Preprocessing

### Overview
This task is the first step in the machine learning workflow. It focuses on cleaning and preparing the dataset for model training.

### Steps
* **Data Loading:** The dataset, `churn-bigml-20.csv`, was loaded and its initial structure was inspected.
* **Handling Missing Values:**
    * Categorical columns were filled with the mode.
    * Numerical columns were filled with the mean.
* **Encoding Categorical Features:** Categorical variables were converted into a numerical format using One-Hot Encoding.
* **Feature Scaling:** Numerical features were standardized using `StandardScaler` to ensure they have a mean of 0 and a standard deviation of 1.
* **Data Splitting:** The dataset was split into training (80%) and testing (20%) sets to prepare for model building.

### Tools Used
* Python
* pandas
* scikit-learn
