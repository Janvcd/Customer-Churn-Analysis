## **Employee Churn Analysis**  

📌 Project Overview
This project analyzes **employee churn** using **machine learning and data visualization techniques**. The notebook processes HR data to **identify key factors driving attrition**, leveraging **Google Cloud BigQuery, Pandas, Seaborn, and SHAP analysis** to generate insights.  

---

📂 Files in This Repository**  
- **`Pilot_Analysis_Employee_Churn.ipynb`** → Main Python notebook for data analysis.  
- **`tbl_hr_data.csv`** → HR dataset containing employee details and churn information.  
- **`tbl_new_employees.csv`** → New employee dataset for comparison.  

---

⚙️ Key Features & Workflow  
1️⃣ *Data Extraction & Preprocessing* 
   - Retrieves data from **Google Cloud BigQuery.  
   - Cleans missing values and encodes categorical features.  

2️⃣ *Exploratory Data Analysis (EDA)* 
   - Visualizes churn trends using heatmaps, bar charts, and box plots.  
   - Attrition by Department, Salary, & Tenure insights.  

3️⃣ *Predictive Modeling (Random Forest / XGBoost)  
   - Trains a model to predict employee churn likelihood.  
   - Uses SHAP (SHapley Additive Explanations) to identify key drivers of churn.  

4️⃣ *Google Looker Studio Integration*
   - Exports processed data for visualization in Looker Studio.  
   - Provides real-time interactive dashboards & insights.  

---

## 📌 Installation & Dependencies
Before running the notebook, ensure the following libraries are installed:  

```bash
pip install pandas numpy seaborn matplotlib scikit-learn shap xgboost google-cloud-bigquery
```

For Google Cloud integration, authenticate using:  

```python
from google.colab import auth
auth.authenticate_user()
```

---

📊 Key Insights
- **Departments with the highest churn**: HR, Accounting, and Technical.  
- **Job satisfaction, tenure, and salary impact attrition** the most.  
- **Looker Studio heatmap visualizations** highlight retention challenges.  

---

🔗 Further Enhancements 
✅ Implement **deep learning models** for churn prediction.  
✅ Use **NLP sentiment analysis** on employee reviews.  
✅ Build a **real-time HR dashboard** with Google Cloud Functions.  
