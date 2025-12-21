# 🏥 Hospital Emergency Room Analytics

## 📊 Power BI Report Project

---

## 📌 Project Overview

Ce projet présente un **rapport interactif Power BI** pour analyser les **opérations et la performance des urgences (ER)**.

Il permet aux parties prenantes hospitalières de suivre et d’améliorer :

* 👥 Patient flow
* ⏱️ Waiting times
* 📈 Admission rates
* ⚠️ Operational bottlenecks

Grâce à des **KPIs clairs** et des visualisations intuitives.

## 🔗 Original dataset & challenge source

https://github.com/datavitalyzer/OBaz-DA4U-PowerBI-ReportSample-Emergency-Admissions


---

## 🎯 Business Objectives

* 📊 Suivre les performances de l’ER dans le temps
* 🕒 Identifier les heures de pointe et les départements les plus fréquentés
* ✅ Analyser le taux d’admission et de non-admission
* ⏳ Évaluer la qualité du service via les KPIs de temps d’attente
* 📌 Supporter les décisions opérationnelles basées sur les données

---

## 📈 Key KPIs & Insights

* 🧮 **Total ER Visits**
* ⏱️ **Average Waiting Time**
* ✅ **Admission vs Non-Admission Rate**
* 🚀 **% of Patients Seen Within 30 Minutes**
* 🏥 **Top Departments by Patient Volume**
* 🕒 **Peak Hours & Busiest Days**

---

## 🛠️ Tools & Technologies

* 💻 **Power BI Desktop**
* 🧹 **Power Query** – Data cleaning & transformation
* 📐 **DAX** – Measures, KPIs & time intelligence
* 🌐 **Git & GitHub** – Version control & portfolio hosting

---

## 📁 Dataset Description

* 🗂️ Source: Hospital Emergency Room CSV dataset
* 🔒 Data is anonymized for educational purposes

### Main Fields

* 📅 `Date`
* 🏢 `Department`
* ⏱️ `Waiting time (minutes)`
* 👤 `Gender`
* ✅ `patient_admin_flag` (TRUE / FALSE)
* 🆔 Patient identifier

---

## 🧱 Data Modeling

* ⭐ Star schema design
* 📌 Fact table: ER visits
* 🗓️ Dimension table: Calendar (Date, Year, Month),DimMonth
* 🔗 One-to-many relationship between Calendar and Fact table
* 🔗 One-to-many relationship between DimMonth and Calender
* 🗓️ Correct month sorting using Month Number

---

## 📊 Dashboard Structure

### 🔹 Page 1 — Overview

* 🎛️ Slicers: Year, Month, Department
* 📋 Patient-level table
* 🌡️ Heatmap (Day × Hour)

- 🧍‍♂️ **Total Patients**: Total number of emergency visits recorded (**9.19K**).
- 🏥 **Admitted Patients**: Number of patients who required hospitalization (**4.61K**).
- 🩺 **Non-Admitted Patients**: Number of patients who received treatment without being hospitalized (**4.59K**).
- ⏱️ **Average Waiting Time**: Average time before patient care begins (**35 minutes**).



### 🔹 Page 2 — Admission & Performance Analysis

### 📈 Patient Volume & Referrals

- 👥 **Number of Patients by Month**: Tracks the total monthly influx of patients, highlighting peak periods such as **August with 1,021 patients**.
- 🔁 **Number of Referred Patients**: Monitors the volume of patients referred to specialists or other departments, revealing **seasonal fluctuations in referral rates**.

---

### ⚙️ Service Quality & Efficiency

- ⏳ **Average Waiting Time by Month (minutes)**: A key operational efficiency metric that tracks monthly variations in wait times, with a peak observed in **February at 26.6 minutes**.
- ⭐ **Average Satisfaction Score by Month**: Measures patient experience on a numerical scale, enabling direct comparison between **service speed (waiting time)** and **patient satisfaction**.


### 🔹 Page 3 — Admission & Performance Analysis

### 🎯 Performance & Patient Distribution Insights

- ⏱️ **Target Response Time**: The dashboard tracks the **percentage of patients seen within 30 minutes**, showing that **59.27%** of patients meet this operational efficiency target.

- 🏥 **Admission Rates**: A near-equal split is observed in the **percentage of patients by admission status**, with **50.10% admitted** versus **49.90% not admitted**.

- 👩‍🦰👨‍🦱 **Patient Demographics**: The **Total Patients by Gender** donut chart shows a distribution of **51.19% Female** and **48.81% Male**, indicating a balanced gender mix.

- 🏢 **Department Workload**: The **Top N Patients by Department** bar chart highlights that the majority of cases are **Unreferred (5.4K)**, followed by **General Practice** and **Orthopedics**.

### 🔹 Page 4 — Performance Analysis

### 🏥 Clinical Outcomes & Patient Profile

- ⏱️ **Wait Time Efficiency**: Displays the percentage of patients seen within the 30-minute target, with **59.27% of cases meeting or exceeding the target**.

- 🛏️ **Admission Status**: Shows a near-even distribution between **admitted patients (50.10%)** and **non-admitted patients (49.90%)**.

- 👩‍⚕️👨‍⚕️ **Gender Distribution**: Presents a balanced patient demographic, with **51.19% Female** and **48.81% Male**.

- 🏢 **Departmental Workload**: Identifies **Unreferred cases (5.4K)** as the largest patient source, followed by **General Practice (1.8K)**.


---

## 🚀 How to Use the Dashboard

1. 📥 Download the the project from this repository
2. 💻 Open the `.pbix` file in **Power BI Desktop**
3. 🎛️ Filter by Year, Month, or Department using slicers
4. 📊 Explore trends and KPIs interactively

---

## 💡 Business Value

This dashboard enables hospital managers to:

* 😊 Improve patient experience
* ⏳ Reduce waiting times
* 👥 Optimize staff allocation
* ⚠️ Detect performance issues early
* 📈 Make faster, data-driven decisions

---

## 📷 Report Preview

![Report Preview](report_screenshots)
> Note: All icons used in this dashboard are embedded within icones folder.

---

## 📌 Project Status

* ✅ Completed
* 🔄 Open for future improvements (forecasting, alerts, benchmarking)

---

## 👤 Author

**Yasmine EN-NACHATI**
Aspiring Data Analyst | Business Intelligence
📍 Portfolio Project – Power BI

---

## 📬 Contact

Feel free to connect with me on LinkedIn or GitHub for feedback or collaboration.


