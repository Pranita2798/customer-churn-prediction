# customer-churn-prediction
A beginner-friendly data analytics project to predict customer churn using Python and machine learning.
# 📊 Customer Churn Prediction

A beginner-to-intermediate level end-to-end machine learning project to predict telecom customer churn using Python. It includes data cleaning, exploratory data analysis (EDA), and classification models like Logistic Regression and Random Forest.

---

## 📁 Project Structure


---

## 💡 Objective

To analyze customer behavior and predict the likelihood of churn using historical account data. The project applies statistical insights and machine learning to identify patterns associated with churn.

---

## 🧰 Technologies Used

- **Python 3.10**
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📦 Dataset Details

- **Source**: [Kaggle - Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Rows**: 7,043
- **Target Variable**: `Churn` (Yes/No)
- **Features**: Demographic, account, and service usage information

---

## 🔍 Project Steps

### 🔹 1. Data Cleaning
- Removed missing/blank values
- Converted `TotalCharges` to numeric
- Removed unnecessary columns

### 🔹 2. Exploratory Data Analysis (EDA)
- Visualized churn distribution across gender, contract type, tenure, and charges
- Used Seaborn countplots and boxplots

### 🔹 3. Modeling
- Label encoded categorical columns
- Split data into train/test (80/20)
- Built two models:
  - Logistic Regression
  - Random Forest Classifier
- Evaluated performance using:
  - Accuracy Score
  - Classification Report
  - Confusion Matrix
  - Feature Importance (for Random Forest)

---

## 📈 Sample Visualizations

| Churn Distribution             | Churn by Contract Type         |
|-------------------------------|--------------------------------|
| ![Churn](images/churn_plot.png) | ![Contract](images/contract_type.png) |


---

## 🧪 How to Run the Project

```bash
# Clone this repository
git clone https://github.com/Pranita2798/customer-churn-prediction.git

# Navigate to the folder
cd customer-churn-prediction

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
