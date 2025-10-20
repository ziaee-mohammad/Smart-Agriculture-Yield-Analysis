# 🌾 Smart Agriculture Yield Analysis

A data-driven machine learning project focused on **optimizing crop yield** and supporting **smart agriculture**.  
The study integrates environmental, agronomic, and geospatial data to identify key factors affecting crop productivity and promote **sustainable food production**.

---

## 🔍 Overview
Agriculture plays a crucial role in global food security.  
This project leverages **data analytics and machine learning** to uncover insights from smart farming data — helping farmers make informed, data-backed decisions to improve yield, resource efficiency, and sustainability.

---

## 📊 Dataset
- **Total samples:** 500+ simulated farm records  
- **Features include:**
  - 🌱 *Soil & Environment:* soil_moisture, soil_pH, temperature, rainfall, humidity, sunlight_hours  
  - 🌾 *Agronomic Factors:* crop_type, fertilizer_type, irrigation_method, pesticide_usage, NDVI_index  
  - 🗺️ *Geospatial & Time:* region, latitude, longitude, sowing_date, harvest_date  
  - 🎯 *Target:* yield_kg_per_hectare  
- Data preprocessed and normalized for ML use.

---

## ⚙️ Workflow
1. **Data Preprocessing**
   - Missing value imputation  
   - Feature scaling and encoding  
   - Outlier handling and duration calculation  
2. **Exploratory Data Analysis (EDA)**
   - Crop yield trends by region & season  
   - Correlation heatmaps and feature importance  
3. **Model Development**
   - Linear Regression  
   - Random Forest Regressor  
   - XGBoost Regressor  
4. **Evaluation Metrics**
   - R², RMSE, MAE  
   - Residual plots and feature importances  

---

## 🧠 Key Insights
- NDVI and soil moisture strongly correlate with yield.  
- Smart irrigation and fertilizer selection significantly improve productivity.  
- Disease presence and high soil acidity decrease yield.  
- XGBoost achieved the **best overall performance** with lowest RMSE.  

---

## 🚀 Quick Start
```bash
git clone https://github.com/ziaee-mohammad/Smart-Agriculture-Yield-Analysis.git
cd Smart-Agriculture-Yield-Analysis
pip install -r requirements.txt
jupyter notebook Smart_Agriculture_Yield_Analysis.ipynb
```

---

## 🛠️ Tools & Libraries
- Python, Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn, XGBoost  
- Plotly (interactive visuals)  

---

## 🌍 Future Enhancements
- Integration with **IoT sensors** and real-time weather APIs  
- Inclusion of **satellite-based NDVI imagery**  
- SHAP & PDP interpretability dashboards  
- Deployment via **Streamlit** for live farm yield prediction  

---

## 🧾 Author
**Mohammad Ziaee**  
📍 Computer Engineer | Data Science & AI Enthusiast  
🔗 [GitHub Profile](https://github.com/ziaee-mohammad)
👉 Instagram: [@ziaee_mohammad](https://www.instagram.com/ziaee_mohammad/)

---

## 🏷️ Tags
`smart-agriculture` • `crop-yield-prediction` • `data-science` • `machine-learning` • `sustainability` • `precision-farming`
