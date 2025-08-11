# ✈️ Flight Delay Prediction using Random Forest

## 📖 Project Overview
This project demonstrates how to predict **flight delays** using a **Random Forest Classifier**.  
The workflow covers:
- Data Loading & Cleaning  
- Exploratory Data Analysis (EDA)  
- Feature Encoding  
- Model Building  
- Hyperparameter Tuning (GridSearchCV)  
- Model Evaluation & Visualization  
- Model Saving for Future Use  

---

## 📊 Dataset
The dataset consists of:
- **10,000 sampled flight records** from `Airlines.csv`  
- **Features**:
  - Airline  
  - Flight  
  - AirportFrom  
  - AirportTo  
  - DayOfWeek  
  - Time  
  - Length  
- **Target**:
  - Delay (`0` = Not Delayed, `1` = Delayed)  

---

## 📂 Project Structure
- **data/** → Raw dataset (`Airlines.csv`)  
- **outputs/**  
  - **eda/** → Plots generated during EDA  
  - **models/** → Saved Random Forest model (`randomForest.pkl`)  
  - **results/** → Evaluation metrics & plots  
- **notebooks/** → Jupyter Notebooks (if applicable)  
- **README.md** → Project documentation  

---

## 📊 Outputs
- **EDA Plots** → `outputs/eda/`  
  - Delay class distribution pie chart  
  - Distribution plots for numerical features by delay status  
  - Correlation heatmap  
  - Delays by time of day  
- **Model Evaluation** → `outputs/results/`  
  - Confusion Matrix (default & best threshold)  
  - ROC Curve  
  - Probability distribution plots  
- **Saved Model** → `outputs/models/randomForest.pkl`  

---

## 🛠 Technologies Used
- **Python 3.x**  
- **Pandas, NumPy** – Data manipulation  
- **Matplotlib, Seaborn** – Visualization  
- **Scikit-learn** – Machine Learning model & evaluation  
- **Joblib** – Model persistence  

---
