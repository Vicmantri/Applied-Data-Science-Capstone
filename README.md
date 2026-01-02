# Applied-Data-Science-Capstone

# 🚀 SpaceX Launch Analysis — End‑to‑End Data Science Project  
*A full data engineering, analytics, visualization, and machine learning pipeline.*

## 📌 Project Overview  
This repository contains a complete data science workflow analyzing SpaceX Falcon 9 launch performance. The project includes data collection, wrangling, exploratory analysis, geospatial mapping, interactive dashboards, and predictive modeling to determine the likelihood of launch success.

The goal is to understand SpaceX launch behavior, uncover key performance drivers, and build a model that predicts mission success using historical data.

---

# 📂 Repository Structure

### **1. Data Collection**
- **`jupyter-labs-spacex-data-collection-api.ipynb`**  
  Collects SpaceX launch data using REST API calls.  
  - Retrieves launch, rocket, payload, and launchpad data  
  - Normalizes nested JSON  
  - Produces structured datasets for downstream processing  

- **`jupyter-labs-webscraping.ipynb`**  
  Scrapes Wikipedia launch tables to supplement missing fields.  
  - Extracts HTML tables  
  - Cleans and standardizes scraped data  
  - Merges with API dataset  

---

### **2. Data Wrangling**
- **`labs-jupyter-spacex-Data wrangling.ipynb`**  
  Cleans, transforms, and merges all collected data.  
  - Handles missing values  
  - Encodes categorical fields  
  - Engineers new features  
  - Produces a final analysis‑ready dataset  

---

### **3. Exploratory Data Analysis**
- **`edadataviz.ipynb`**  
  Visual EDA using Matplotlib and Seaborn.  
  - Launch success trends  
  - Payload vs. outcome relationships  
  - Orbit distribution  
  - Booster landing performance  

- **`jupyter-labs-eda-sql-coursera_sqllite.ipynb`**  
  SQL‑based EDA using SQLite.  
  - Launch counts  
  - Success rates  
  - Payload statistics  
  - Booster version analysis  

---

### **4. Geospatial Analysis**
- **`lab_jupyter_launch_site_location.ipynb`**  
  Interactive mapping using Folium.  
  - Launch site markers  
  - Distance lines  
  - Safety radius circles  
  - Popups and tooltips  

---

### **5. Interactive Dashboard**
- **`spacex-dash-app.py`**  
  A Plotly Dash web application for interactive analytics.  
  - Launch site dropdown  
  - Payload range slider  
  - Success pie chart  
  - Payload vs. outcome scatter plot  

---

### **6. Machine Learning**
- **`SpaceX_Machine Learning Prediction_Part_5.ipynb`**  
  Classification modeling to predict launch success.  
  - Logistic Regression, KNN, SVM, Decision Tree  
  - Hyperparameter tuning with GridSearchCV  
  - Model evaluation and selection  

---

# 🧠 Methodology Summary

### **Data Collection**
- REST API calls to SpaceX API  
- Web scraping from Wikipedia  
- JSON normalization and HTML table extraction  

### **Data Wrangling**
- Cleaning, merging, encoding, feature engineering  
- Preparing a unified dataset for analysis and modeling  

### **Exploratory Analysis**
- Visualizations to uncover trends and relationships  
- SQL queries for structured insights  

### **Geospatial Analytics**
- Folium maps to visualize launch site geography and distances  

### **Interactive Dashboard**
- User‑driven exploration of launch success patterns  

### **Predictive Modeling**
- Multiple classifiers trained and tuned  
- Best model selected based on accuracy and balanced metrics  

---

# 📈 Key Results

- Launch success rates have improved significantly over time.  
- Payload mass shows no strong negative impact on success.  
- Certain launch sites consistently outperform others.  
- Booster reusability has increased mission reliability.  
- The best classification model predicts launch success with strong accuracy.  

---

# ▶️ How to Run the Project

1. Clone the repository  
2. Install required Python libraries  
3. Run notebooks in Jupyter or VS Code  
4. Launch the Dash app with:  
   ```
   python spacex-dash-app.py
   ```

---

# 📜 License  
This project is for educational and analytical purposes as part of the IBM Applied Data Science Capstone.
