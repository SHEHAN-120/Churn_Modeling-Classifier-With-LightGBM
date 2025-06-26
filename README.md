# LightGBM Classifier - Customer Churn Prediction

This project demonstrates a full machine learning pipeline using the **LightGBM classifier** to predict customer churn. The dataset used is a cleaned version of a telecom churn modeling dataset, and the project was implemented in **Google Colab**.

## 📊 Dataset Overview

The dataset contains various customer details such as credit score, age, balance, tenure, and geography. The target variable is whether the customer has exited the service.

## 🧠 Machine Learning Workflow

The pipeline includes the following steps:

### 1. 📌 Data Preprocessing
- Handled **categorical variables** using appropriate encoding techniques (e.g., OneHotEncoder, LabelEncoder).
- Checked and handled missing values.
- Normalized/Standardized numerical features for optimal performance.

### 2. ⚙️ Model Building & Training
- Implemented **LightGBM Classifier**, known for its speed and efficiency with large datasets.
- Used training/testing data split to validate the model effectively.

### 3. 🧪 Model Evaluation
- Evaluated performance using:
  - **Confusion Matrix**
  - **Accuracy**

## 📈 Key Highlights

- ✅ Built in Google Colab for reproducibility and sharing.
- ✅ GridSearchCV for optimized hyperparameters.
- ✅ Confusion matrix visualized for clear classification insights.
- ✅ Followed machine learning best practices throughout.

## 🧰 Tools Used:

- Python
- pandas
- lightgbm
- matplotlib
- scikit-learn

