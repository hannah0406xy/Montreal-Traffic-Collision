# 🚗 Montreal Traffic Collision Analysis

## 📌 Project Overview  
This project focuses on **analyzing traffic accidents in Montreal** to enhance road safety and minimize accidents. Our goal is to:  
- Identify **high-risk zones** within the city.  
- Predict the **severity of traffic accidents** based on various factors.  
- Provide **actionable insights** for preventative measures and policy recommendations.  

By leveraging **machine learning models and spatial analysis**, we empower Montreal’s traffic authorities with insights to inform **road safety policies** and **urban planning**.

---

## 📊 Data Description  
The dataset is sourced from **Société de l'assurance automobile du Québec (SAAQ)** and contains:  
- **Accident location data** (geographic coordinates, road category, lighting conditions).  
- **Environmental conditions** (weather, surface conditions, speed limits).  
- **Vehicle and victim information** (number of vehicles involved, accident type).  
- **Temporal patterns** (time of day, seasonal variations).  

We handled **missing data** using **rolling window imputation** and applied techniques such as **target encoding** to improve model performance.

---

## 🔎 Exploratory Data Analysis (EDA)  
- **Traffic Collision Patterns**  
  - Analyzed accident frequency based on **time of day, road conditions, and location**.  
  - Identified **high-risk intersections** and accident-prone zones.  

- **Feature Selection & Engineering**  
  - Used **ANOVA, Chi-Square tests**, and **Random Forest feature importance**.  
  - Applied **SMOTE** to address class imbalance in accident severity prediction.  

- **Clustering & Visualization**  
  - Mapped **accident severity hotspots** across Montreal.  
  - Conducted **spatial analysis** of severe and fatal accidents.

---

## 🤖 Machine Learning Models  
We approached this as a **multi-class classification problem** and evaluated multiple models:

| Model                | Accuracy | F1 Score |
|----------------------|----------|----------|
| **Logistic Regression** | 87%  | 0.85 |
| **Random Forest**       | 92%  | 0.91 |
| **XGBoost**            | **95%** | **0.95** |

🏆 **Final Model: XGBoost**  
- Achieved **95% accuracy** in predicting accident severity.  
- Incorporated **geospatial features** to improve risk assessment.  

---

## 📈 Business Value & Impact  
This analysis provides **data-driven recommendations** for:  
✅ **Emergency Response Optimization** – Faster deployment in high-risk zones.  
✅ **Infrastructure Investment Prioritization** – Upgrading roads in accident-prone areas.  
✅ **Policy & Public Safety Campaigns** – Targeted interventions for accident prevention.  
✅ **Insurance Risk-Based Pricing** – Dynamic pricing based on localized risk factors.  

---

## 🔮 Future Work  
🚀 **Real-Time Data Integration**: Incorporate live traffic, weather, and road condition feeds.  
🛑 **Enhanced Fraud Detection**: Use AI to validate insurance claims against severity predictions.  
📍 **IoT & Smart City Applications**: Leverage **connected traffic sensors** for proactive risk management.  

---

## 🛠 Tech Stack  
- **Programming:** Python
- **Data Processing:** Pandas, NumPy  
- **Machine Learning:** Scikit-learn, XGBoost, Random Forest  
- **Data Visualization:** Matplotlib, Seaborn, Tableau  

## 📢 Contributors 
👩‍💻 **Xinyi Wang**  
👨‍💻 **JaeYoon Lee**  
👩‍💻 **Shuxi Chen**   
👩‍💻 **Yifei Liu**  

📬 For inquiries, feel free to reach out!  

🚀 **Let's make Montreal's roads safer with data-driven insights!**  
