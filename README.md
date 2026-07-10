# 📉 Customer Churn Prediction using Machine Learning

Predicting customer churn is one of the most valuable applications of machine learning for businesses. This project builds a classification model to identify customers who are likely to leave, enabling companies to take proactive retention measures.

---

## 📌 Project Overview

Customer churn directly impacts business revenue and growth. This project analyzes customer and pricing data, performs extensive exploratory data analysis (EDA), engineers meaningful features, and develops a Machine Learning model to predict whether a customer is likely to churn.

The project follows a complete end-to-end data science workflow:

- Data Exploration
- Data Cleaning
- Feature Engineering
- Model Building
- Model Evaluation
- Business Insights

---

## 🎯 Problem Statement

Businesses lose significant revenue when customers stop using their services. Identifying customers who are at risk of leaving allows organizations to:

- Improve customer retention
- Reduce revenue loss
- Design targeted marketing campaigns
- Increase customer lifetime value

The objective of this project is to build a predictive classification model that accurately identifies customers likely to churn.

---

## 📂 Dataset

The project uses two datasets:

- **Client Data**
- **Price Data**

These datasets contain customer demographics, subscription details, energy pricing information, and churn labels.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── EDA.ipynb
├── Feature Engineering.ipynb
├── Modeling.ipynb
├── client_data.csv
├── price_data.csv
├── clean_data_after_eda.csv
├── data_for_predictions.csv
├── README.md
```

---

## 📊 Exploratory Data Analysis

The EDA phase includes:

- Data inspection
- Missing value analysis
- Descriptive statistics
- Distribution analysis
- Correlation analysis
- Feature visualization
- Churn distribution analysis

Several visualizations were created to understand customer behaviour and identify important patterns.

---

## ⚙️ Feature Engineering

Feature engineering involved:

- Date feature transformation
- Price trend analysis
- Off-peak price difference calculation
- Feature selection
- Data preprocessing
- Preparing the final dataset for machine learning

These engineered features improve the predictive capability of the model.

---

## 🤖 Machine Learning Model

The project uses a:

### Random Forest Classifier

Reasons for choosing Random Forest:

- Handles non-linear relationships
- Works well with mixed feature types
- Robust against overfitting
- Provides feature importance
- Strong baseline performance for classification problems

---

## 📈 Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- Confusion Matrix

Since customer churn datasets are typically imbalanced, Precision and Recall were considered more informative than Accuracy alone.

---

## 📌 Workflow

```
Client Data + Price Data
          │
          ▼
Data Cleaning
          │
          ▼
Exploratory Data Analysis
          │
          ▼
Feature Engineering
          │
          ▼
Train-Test Split
          │
          ▼
Random Forest Classifier
          │
          ▼
Prediction
          │
          ▼
Performance Evaluation
```

---

## 💡 Key Insights

- Customer churn prediction is an imbalanced classification problem.
- Accuracy alone can be misleading.
- Precision and Recall provide a better understanding of model performance.
- Feature engineering significantly contributes to improving predictive performance.
- Pricing behaviour plays an important role in customer churn.

---

## 📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Classification Modeling
- Random Forest
- Model Evaluation
- Business Insight Generation
- Python Programming

---

## 📷 Sample Workflow

```
Raw Data
   │
   ▼
EDA
   │
   ▼
Feature Engineering
   │
   ▼
Random Forest Model
   │
   ▼
Customer Churn Prediction
```

---

## 👩‍💻 Author

**Meghana D A**

**Data Scientist | Machine Learning | Python | SQL | Power BI | Data Analytics**

---

## ⭐ If you found this project useful

Please consider giving this repository a **⭐ Star**.
It helps others discover the project and supports my work.

