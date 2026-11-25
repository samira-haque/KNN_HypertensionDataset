# 🩺 Hypertension Prediction Using K-Nearest Neighbors (KNN)

## 📌 Project Overview

This project focuses on predicting hypertension using Machine Learning techniques, particularly the **K-Nearest Neighbors (KNN)** classification algorithm.

The project uses a hypertension dataset containing health-related attributes such as age, salt intake, stress score, blood pressure history, sleep duration, BMI, medication, family history, exercise level, and smoking status.

The main goal is to analyze these health-related factors and build a machine learning model that predicts whether an individual has hypertension.

## 🎯 Objectives

- Analyze the hypertension dataset.
- Perform data preprocessing and cleaning.
- Handle missing values.
- Convert categorical features into numerical format.
- Apply feature scaling.
- Build a KNN classification model.
- Find a suitable value of K.
- Evaluate model performance.
- Explore feature selection and stacking techniques.

## 📂 Dataset Information

- **Total Records:** 1,985
- **Total Columns:** 11
- **Target Variable:** `Has_Hypertension`

### Features

| Feature | Description |
|---|---|
| Age | Individual's age |
| Salt_Intake | Daily salt intake |
| Stress_Score | Stress level |
| BP_History | Blood pressure history |
| Sleep_Duration | Hours of sleep |
| BMI | Body Mass Index |
| Medication | Medication information |
| Family_History | Family history of hypertension |
| Exercise_Level | Physical activity level |
| Smoking_Status | Smoking habit |
| Has_Hypertension | Target variable (Yes/No) |

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

## ⚙️ Methodology

### 1. Data Loading
Load the hypertension dataset using Pandas.

### 2. Exploratory Data Analysis (EDA)
- Examine dataset structure.
- Identify missing values.
- Analyze target variable distribution.
- Explore health-related features.

### 3. Data Preprocessing
- Handle missing values.
- Apply One-Hot Encoding to categorical variables.
- Separate independent and dependent variables.
- Apply StandardScaler for feature scaling.

### 4. Model Training
- Split the dataset into training and testing sets.
- Train the K-Nearest Neighbors classifier.
- Experiment with different K values.

### 5. Model Evaluation
Evaluate the model using:
- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score
- ROC-AUC

### 6. Feature Selection & Stacking
Additional notebooks explore feature selection and stacking approaches to investigate model performance and improve classification.

## 📊 Initial Model Result

The baseline KNN model with K = 1 achieved approximately **78% accuracy** on the test dataset.

This result represents the initial model performance, not necessarily the best-performing model.

## 📁 Repository Structure

```text
KNN_HypertensionDataset/
│
├── 01-K Nearest Neighbors with Python.ipynb
├── Feature_Slection_Stacking.ipynb
├── Hypertension_KNN_Project (1).ipynb
├── KNN_Hypertension.ipynb
├── hypertension_dataset (1).csv
│
└── README.md
```

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/samira-haque/KNN_HypertensionDataset.git
```

2. Navigate to the project directory:

```bash
cd KNN_HypertensionDataset
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open any of the project notebooks and run the cells sequentially.

## 📌 Conclusion

This project demonstrates how machine learning can be applied to healthcare-related data for hypertension classification. By using KNN and exploring feature selection and stacking techniques, the project provides practical experience in data preprocessing, classification, and model evaluation.

**Disclaimer:** This project is developed for educational and research purposes only. It is not intended to replace professional medical diagnosis or advice.

## 👩‍💻 Author

**Samira Haque**

GitHub: [@samira-haque](https://github.com/samira-haque)
