# 🩺 Obesity Level Prediction — EDA & Machine Learning
This project focuses on predicting obesity levels based on lifestyle, eating habits, and demographic information.
We perform a complete end-to-end workflow from data exploration to model tuning, comparing performance before and after optimization.

## 📌 Project Steps
### 1. Exploratory Data Analysis (EDA)
Checked dataset structure, types, and missing values

Identified categorical and numerical features

Conducted univariate, bivariate, and multivariate visual analysis

Created correlation heatmaps and distribution plots for deeper insights

### 2. Data Preprocessing
Encoded categorical variables

Scaled numerical features for model compatibility

Applied train-test split for evaluation integrity

### 3. Model Training
Trained multiple baseline models on default parameters

Compared initial results to identify promising candidates

### 4. Hyperparameter Tuning
Applied GridSearchCV for each model with carefully chosen parameter grids

Compared tuned vs un-tuned models for performance improvements

Evaluated using accuracy, F1-score, precision, recall

### 5. Insights & Observations
Lifestyle and eating habits strongly impact obesity classification

Tree-based algorithms showed the most consistent results

Hyperparameter tuning improved class-wise metrics, even if accuracy gains were minimal

Balanced model evaluation required checking more than just accuracy due to class distribution

## 📊 Performance Summary
The notebook contains both untuned and tuned model results for easy comparison.
Performance metrics are printed and discussed inline, highlighting where tuning made a difference.

## 🛠 Tools & Libraries
Data Handling: pandas, numpy

Visualization: matplotlib, seaborn

Machine Learning: scikit-learn, XGBoost, CatBoost, LightGBM
