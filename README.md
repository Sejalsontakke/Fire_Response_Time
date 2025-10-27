# Fire_Response_Time
# 🚒 Fire Response Time Analysis — 2019 Dataset

This project analyzes the **2019 Fire Response Time dataset** from Data.gov using various **Machine Learning techniques** to explore response trends, predict times, and evaluate performance metrics.

---

## 📊 Dataset
Source: [Data.gov — Fire Response Time Analysis](https://catalog.data.gov/dataset/2019-fire-response-time-analysis)

The dataset contains monthly response time intervals categorized by duration (e.g., "<1:00", "1:00 to 1:59", etc.).

---

## 🔍 Project Workflow
1. **Data Cleaning** – Removed missing values, standardized column names.
2. **Exploratory Data Analysis (EDA)** – Heatmaps, correlations, response time distributions.
3. **Regression Models**
   - Linear Regression  
   - Multiple Linear Regression  
   - Decision Tree Regressor  
   - Random Forest Regressor  
4. **Classification Models**
   - KNN Classifier  
   - Gradient Boosting Classifier  
   - Naive Bayes  
5. **Model Evaluation**
   - R² Score, RMSE  
   - Confusion Matrix  
   - Cross-validation results

---

## 🧠 Key Insights
- Average fire response time concentrated between **1–2 minutes**.  
- Regression models achieved **R² > 0.93**, indicating strong predictive performance.  
- Feature importance analysis highlighted that **monthly variation** significantly influences response time.  

---

## ⚙️ Tech Stack
- Python 3.10+
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 📈 Results
| Model | R² Score | RMSE | Cross-Val R² |
|-------|-----------|------|--------------|
| Linear Regression | 0.936 | 85.83 | 0.91 |
| Multiple Linear Regression | 1.000 | 0.00 | 0.99 |
| Decision Tree Regressor | ~0.93 | — | 0.91 |
| Random Forest Regressor | ~0.95 | — | 0.93 |

---

## 📷 Visuals
- Correlation Heatmap  
- Actual vs Predicted Response Time Scatter Plot  
- Feature Importance Chart  

---

## 🧩 Future Work
- Add **deep learning regression (ANN)** for time prediction.  
- Deploy model as a **Streamlit dashboard** for interactive visualization.  
- Include **real-time city-level data** from emergency services for validation.

---

## 📬 Author
👩‍💻 **Sejal Sontakke**  
CSE Student | Data Science & ML Enthusiast  

