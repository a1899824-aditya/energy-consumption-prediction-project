# 🔋 Energy Use Prediction

This project applies machine learning models to predict energy consumption of appliances based on weather and environmental sensor data, replicating methods from the Candanedo et al. (2017) study.

---

## 📄 Dataset Source
Candanedo, L. M., Feldheim, V., & Deramaix, D. (2017). Data from appliances energy prediction study. *UCI Machine Learning Repository*  
[PDF Overview](https://github.com/a1899824-aditya/energy-use-prediction/blob/main/2017_Candanedo_energy%20use%20prediction%20(2).pdf)

---

## 🛠 Tools & Libraries
- Python  
- pandas, NumPy  
- scikit-learn  
- matplotlib, seaborn  
- Linear Regression, Random Forest Regressor

---

## 📊 Project Features
- Data preprocessing and feature engineering  
- Multicollinearity check using correlation heatmap  
- Regression modeling (linear and ensemble methods)  
- Model evaluation using MAE, MSE, RMSE, R²  
- Cross-validation and feature importance ranking

---

## 📁 Files
- `assign1a.ipynb`: Main notebook  
- `2017_Candanedo_energy use prediction.pdf`: Paper overview

---

## 📈 Results
- Best model: Random Forest  
- R²: ~0.57  
- MAE: ~85.4  
- RMSE: ~106.2  

---

## 👤 Author
Aditya Nediyirippil  
GitHub: [a1899824-aditya](https://github.com/a1899824-aditya)

---

## ✅ Future Work
- Test additional regressors (Gradient Boosting, XGBoost)  
- Hyperparameter tuning with GridSearchCV  
- Deploy as dashboard using Streamlit or Flask
