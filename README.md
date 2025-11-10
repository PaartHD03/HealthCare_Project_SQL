# 🏥 Healthcare Data Analysis – SQL + Power BI Dashboard  

### 📘 **Project Overview**  
This project demonstrates how raw healthcare data can be transformed into meaningful insights using **SQL for data analysis** and **Power BI for visualization**.  
The goal was to identify patient trends, hospital performance, and key health metrics from a structured healthcare dataset.

---

### ⚙️ **Tech Stack**
- **SQL** – Data cleaning, querying, and aggregation  
- **Power BI** – Data visualization and dashboard design  
- **Power Query** – Data transformation and conditional logic  
- **CSV Dataset** – Healthcare data (patient demographics, diagnosis, billing)

---

### 🧩 **Dataset Details**
**File:** `Health_care_sql.csv`  
Contains patient demographics, medical condition, test results, hospital details, and billing information.  

| Column | Description |
|--------|--------------|
| `Patient_ID` | Unique identifier for each patient |
| `Age` | Patient’s age |
| `Gender` | Male / Female |
| `Medical_Condition` | Diagnosis or health issue |
| `Hospital` | Hospital/Branch name |
| `Test_Result` | Positive / Negative |
| `Billing_Amount` | Revenue generated |
| `Duration` | Number of days admitted (cleaned in Power BI) |

---

### 🔍 **SQL Analysis**
All data exploration and cleaning steps were performed using SQL before importing into Power BI.  
Key operations included:
- Filtering invalid or missing data  
- Aggregating total patients and revenue by hospital  
- Grouping by medical condition and gender  
- Exporting cleaned results to CSV for visualization  

📄 SQL queries used: [`queries.sql`](./queries.sql)  
📑 Question list: [`Healthcare_questions.pdf`](./Healthcare_questions.pdf)

---

### 🧠 **Power BI Workflow**
Once the dataset was cleaned in SQL:
1. **Loaded CSV into Power BI**
2. **Replaced negative durations with zero**
3. **Created conditional columns** using IF–ELSE logic for test results
4. **Built visuals** to show:
   - Total patients
   - Age & gender distribution  
   - Medical conditions  
   - Revenue per hospital  

---

### 📊 **Dashboard Insights**
Key Metrics:
- **Total Patients:** 300  
- **Average Age:** 52.2  
- **Total Revenue:** ₹7.47M  
- **Most Common Condition:** Hypertension  
- **Gender Split:** ~52% Male / 48% Female  

🖼️ Dashboard Pages:
1. Overview Dashboard (Main)
2. Conditional Logic View (Power Query)
3. SQL Query Reference  

---

### 🚀 **Key Learnings**
- Combining **SQL querying** with **Power BI visualization** for an end-to-end analytics workflow  
- Using **conditional columns** and **data transformations** to clean inconsistent data  
- Designing **interactive dashboards** for healthcare insights  

---

### 🌐 **Project Links**
🔗 **Power BI Dashboard Preview:** [Coming Soon]  
📂 **GitHub Repository:** [github.com/PaartHD03/HealthCare_Project_SQL](https://github.com/PaartHD03/HealthCare_Project_SQL)

---

### 💬 **Feedback**
Suggestions and improvements are always welcome!  
If you liked this project, consider ⭐ starring the repo or connecting with me on [LinkedIn](https://www.linkedin.com/in/paarth-doshi/).

---

**#PowerBI #SQL #DataAnalytics #Healthcare #DataVisualization #PortfolioProject #Python #BusinessIntelligence**
