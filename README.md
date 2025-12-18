# Heartwise-ML
A reusable Machine Learning workflow template implemented in Python. This project demonstrates the full ML lifecycle—from Exploratory Data Analysis (EDA) and cleaning of clinical patient data to model selection—specifically applied to predicting heart disease presence based on key medical metrics.

# Heart Disease Classification Project

## 📌 Project Overview
This project is a comprehensive Machine Learning template designed to predict the presence of heart disease in patients based on 5 clinical characteristics. It follows a structured, reusable workflow suitable for any classification task.

The goal is to build a trustworthy model that can assist healthcare providers in early detection, potentially improving patient outcomes.

## 📊 Dataset Description
The dataset (`heart_disease.csv`) includes records for approximately 300 medical patients.
- **Target Variable**: `heart_disease` (1 = Disease Present, 0 = No Disease)
- **Predictor Variables**: 
  - `age`
  - `sex` (Male/Female)
  - `max_heart_rate`
  - `angina_level` (Typical/Atypical)
  - `non_anginal_pain`

## 🛠️ Machine Learning Workflow
1. **Problem Definition**: Establishing the motivation for using ML in cardiovascular health.
2. **Data Preparation (EDA)**:
   - **Data Cleaning**: Removed anomalous values (e.g., negative heart rates).
   - **Missing Data**: Handled missing entries in `age` and `angina_level` using median imputation and row removal.
   - **Transformation**: Encoded categorical variables like `sex` and `angina_level` into numerical formats.
   - **Visualization**: Analyzed distributions using Histograms, Boxplots, and Correlation Heatmaps.
3. **Model Selection**: Evaluated the suitability of **Logistic Regression** as a baseline, with considerations for Decision Trees and Random Forests.
4. **Model Evaluation**: Defined key performance metrics including **Accuracy, Precision, Recall, and F1 Score** to ensure clinical reliability.

## 🚀 How to Use
1. Clone this repository.
2. Ensure you have `pandas`, `numpy`, `matplotlib`, and `seaborn` installed.
3. Run the Jupyter Notebook (`.ipynb`) to see the full analysis and results.

## 📂 Deliverables
- `Heartwise-ML.ipynb`: Full Python source code and analysis.
- `Heartwise-ML.html`: Exported version of the notebook for quick viewing.
- `heart_disease.csv`: The raw dataset used for training.
