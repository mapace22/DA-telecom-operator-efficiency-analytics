# 📞 CallMeMaybe: Operational Efficiency & Telecom Analytics

## 🎯 Project Objective
The goal of this project was to identify and quantify operational ineffectiveness within the **CallMeMaybe** virtual telephony service. By integrating call logs and client data, I developed a data-driven framework to classify operator performance based on key metrics like missed calls, waiting times (AWT), and call duration (ACD).

## 🛠️ Technical Pipeline & Methodology
The project followed a robust data science workflow:

1.  **Data Integration & Engineering:** Unified disparate datasets and engineered the `wait_time` and `is_ineffective` features based on business logic.
2.  **Exploratory Data Analysis (EDA):** Identified critical systemic issues, such as a **52.73% missed call rate**, far exceeding industry standards.
3.  **Statistical Validation:** Performed **Mann-Whitney U tests** (non-parametric) to validate if the differences in performance between operator segments were statistically significant.
4.  **Business Intelligence:** Designed and deployed a three-level interactive dashboard in **Tableau** for real-time monitoring.



## 📊 Key Findings & Metrics
My analysis revealed significant disparities in operator activity and systemic bottlenecks:

* **Average Call Duration (ACD):** 26.0 minutes (Industry benchmark: 3-6 min).
* **Average Waiting Time (AWT):** 100.61 seconds (Ideal: <30 sec).
* **Workload Imbalance:** A Pareto analysis (80/20) showed that a small percentage of operators handle the majority of the volume, while many remain underutilized.

### Statistical Highlights:
* Applied segment classification using **percentiles** to set fair performance thresholds.
* Validated the "Ineffective" label through hypothesis testing, ensuring recommendations are backed by data, not just intuition.

## 📈 Interactive Dashboard
The solution features a professional **Tableau Dashboard** structured for different stakeholders:
* **Executive Level:** Top-level KPIs for quick decision-making.
* **Tactical Level:** Pareto charts and individual operator rankings for supervisors.
* **Granular Level:** Scatter plots and trend lines to identify correlations between wait times and duration.

## 📁 Enlaces del Proyecto
### 🌐 Dashboard en Vivo
🔗 **[View Live Dashboard on Tableau Public](https://public.tableau.com/views/proyecto_final_telecom/DashboardTelecomcontrolsobreoperadoresineficaces?:language=es-ES&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

### 📂 Documentación y Datos
[**Carpeta de Google Drive**]
https://drive.google.com/drive/folders/1vbRrGZHt6WKWrc_Y1ii4uYfKO9xac-wC?usp=sharing


## 💡 Strategic Recommendations
1.  **Immediate Deployment:** Use the dashboard to redistribute workloads and reduce the current 52% missed call rate.
2.  **Training Programs:** Targeted coaching for operators with high AWT/ACD metrics to align them with industry standards.
3.  **Incentive Structures:** Implement a performance-based bonus system using the efficiency ranking developed in this analysis.

## 📂 Project Structure
* `proyecto_15_telecom.ipynb`: Full Python pipeline (Preprocessing + Stats).
* `Informe_Ejecutivo_CallMeMaybe.pdf`: Comprehensive business report for stakeholders.
* `data/`: Original and processed datasets (`telecom_final_dataset.csv`).
* `readme.txt`: Technical instructions and dashboard links.

## 🚀 Tech Stack
* **Visualization:** Tableau Public.
* **Data Processing:** Python (Pandas, NumPy).
* **Statistics:** SciPy (Mann-Whitney U Test).
* **Documentation:** Google Drive / PDF Reporting.

---
**Author:** Marcel Andrés Palma Céspedes  
**Role:** Data Scientist / Business Intelligence Analyst  
**Date:** 08/18/2025
