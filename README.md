# 🍷 Wine Quality Prediction

## 📌 Project Overview

In this project machine learning models are used to predict the quality of red and white wines based on their physicochemical characteristics. Chemical characteristics that affect wine quality ratings such as residual sugar acidity and alcohol content that are included in the dataset. 

## 📂 Dataset

The dataset used in this project is sourced from the **UCI Machine Learning Repository** and consists of:

- `winequality-red.csv` – Red wine data
- `winequality-white.csv` – White wine data

Each record contains:

- **Independent Variables**: Fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol
- **Dependent Variable**: Wine quality score (1–10)

## ⚙️ Technologies Used

- **Python** (pandas, numpy, scikit-learn, matplotlib, seaborn)
- **Machine Learning Models** (Random Forest, Logistic Regression, SVM, Decision Trees, etc.)
- **Power BI** for data visualization and dashboard creation

## 🚀 How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Wine-Quality-Prediction.git
   cd Wine-Quality-Prediction
   ```
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run Jupyter Notebook for EDA and Model Training**
   ```bash
   jupyter notebook
   ```
4. **Power BI Dashboard**
   - Open `wine_dashboard.pbix` in Power BI
   - Explore visualizations and insights

## 📊 Exploratory Data Analysis (EDA)

Key findings from data analysis:

- Alcohol content has a strong positive correlation with wine quality.
- Higher volatile acidity tends to reduce wine quality.
- Residual sugar impacts white wines more than red wines.

## 🏆 Model Performance

The best-performing model for prediction was **Random Forest Classifier**, achieving an accuracy of:

- **Red Wine**: 85%
- **White Wine**: 86%

Other models tested:

- Logistic Regression
- Decision Tree
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

## 📈 Power BI Dashboard

The Power BI dashboard includes:

- **KPI Cards** for average quality, alcohol content, and acidity
- **Histograms** to compare wine quality distribution
- **Stacked Bar & Line Charts** for trend analysis

## ✅ Conclusions & Recommendations

- Alcohol content is a key indicator of wine quality.
- Winemakers should control volatile acidity to improve quality.
- Further feature engineering and deep learning models may enhance predictions.

## 📝 License

This project is licensed under the **MIT License**.

---

Made by Bello Awwal

