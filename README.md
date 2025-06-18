# Climate-Change-Modeling
# 🌍 Climate Change Analysis using Machine Learning

## 📌 Objective

Analyze global climate trends and predict:

* 🌡️ Average Temperature
* ⛈️ Extreme Weather Events (High/Low)

## 📁 Dataset

* Features: CO2 Emissions, Rainfall, Population, Forest Area, etc.
* No missing values
* One-hot encoding + feature scaling applied

## ⚙️ Models Used

### Regression (Target: Avg Temperature)

* Linear Regression → R²: -0.01
* Random Forest → R²: -0.10
* Gradient Boosting → R²: -0.12

### Classification (Target: Extreme Weather Events)

* Logistic Regression → Accuracy: 50.5%
* Random Forest → Accuracy: 46.5%

## 📦 Output Files

* `climate_feature_engineered.csv` (Final dataset)
* `Climate_Change_Project_PPT.pptx` (Presentation)

## ✅ Conclusion

* Classification gave better results
* Logistic Regression performed best among all models

## 🔭 Future Work

* Improve features (e.g. trend-based)
* Use advanced models like LSTM
* Handle data imbalance with SMOTE
