# 🧠 Personality Prediction using Machine Learning

An end-to-end Machine Learning project that predicts whether a person is an **Introvert** or **Extrovert** based on behavioral and social interaction patterns.

The project demonstrates a complete ML workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison of multiple classification algorithms.

---

## 📌 Project Overview

Understanding personality traits can help in areas such as psychology, recruitment, education, and personalized recommendation systems. This project uses supervised machine learning techniques to classify individuals as **Introverts** or **Extroverts** using various behavioral indicators.

---

## 🎯 Objective

Develop a classification model capable of predicting a person's personality type based on behavioral and social features while comparing the performance of multiple machine learning algorithms.

---

## 📂 Dataset

The dataset contains **2,900 records** with **8 features** describing different behavioral characteristics.

### Features

- Time Spent Alone
- Social Event Attendance
- Going Outside
- Friends Circle Size
- Post Frequency
- Stage Fear
- Drained After Socializing
- Personality (Target Variable)

**Target Variable**

- Extrovert
- Introvert

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔄 Machine Learning Workflow

### 1. Data Loading

- Imported the required Python libraries.
- Loaded the dataset into a Pandas DataFrame.
- Inspected the dataset structure and basic statistics.

---

### 2. Data Preprocessing

#### Missing Value Handling

Numeric features:
- Mean Imputation using `SimpleImputer(strategy="mean")`

Categorical/Binary features:
- Converted **Yes/No** values into **1/0**
- Filled missing values using **Most Frequent Imputation**

After preprocessing, the dataset contained no missing values.

---

### 3. Feature Engineering

- Label Encoding for the target variable
- Feature Standardization using `StandardScaler`

---

### 4. Exploratory Data Analysis (EDA)

The following visualizations were created:

- Feature Histograms
- Boxplots
- Correlation Heatmap

### Key Insights

- Introverts generally spend more time alone.
- Extroverts tend to attend more social events.
- Moderate feature correlations were observed.
- No severe multicollinearity was detected.

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented:

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

---

## 📊 Model Evaluation

Each model was evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix
- ROC Curve
- AUC Score

Finally, all models were compared to identify the best-performing classifier.

---

## 📈 Project Pipeline

```
Data Collection
        │
        ▼
Data Preprocessing
        │
        ▼
Missing Value Handling
        │
        ▼
Feature Encoding
        │
        ▼
Feature Scaling
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Performance Comparison
```



---

## 📌 Results

The project successfully:

- Cleaned and preprocessed the dataset
- Performed exploratory data analysis
- Standardized the features
- Trained multiple classification models
- Evaluated model performance using multiple metrics
- Compared classifiers to identify the best-performing model

---

## 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Cross-validation for improved model robustness
- Feature importance analysis
- Model deployment using Streamlit or Flask
- Docker containerization
- CI/CD pipeline integration

---

## 💻 Installation

Clone the repository:

```bash
git clone https://github.com/Harshavardhannadiveedi/Personality_prediction_Using_ML.git
```

Navigate to the project directory:

```bash
cd Personality_prediction_Using_ML
```


Run the notebook or Python script.

---

## ⭐ Acknowledgements

Thanks to the dataset contributors and the open-source Python community for providing the libraries used in this project.

---

## 📬 Connect With Me

If you found this project useful, consider giving it a ⭐ on GitHub.

Feel free to connect with me for discussions on **Machine Learning**, **Data Science**, and **Artificial Intelligence**.

---

### ⭐ If you like this project, don't forget to star the repository!
