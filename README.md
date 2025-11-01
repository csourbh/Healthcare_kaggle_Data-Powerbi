# 🏥 Patient Wait List Analysis Dashboard (Power BI)

## 📘 Overview
This Power BI project provides an analytical overview of **patient wait list trends** across different **case types, time bands, and specialties** in a healthcare environment.  
It enables healthcare administrators and policymakers to **monitor patient load**, **identify delays**, and **improve operational efficiency** over time.

---

## 🎯 Objectives
- Track changes in **patient wait lists** across years (2018–2021).  
- Compare **current and previous year (PY)** patient volumes and waiting times.  
- Identify **case types** (Outpatient, Inpatient, Day Case) with the longest wait times.  
- Highlight **specialties** and **age groups** facing the longest waiting periods.  
- Enable **data-driven hospital planning and resource allocation**.

---

## 🧠 Key Insights

### 🔹 Overall Summary
| Metric | Value |
|--------|-------|
| **Latest Month Wait List** | **709K Patients** |
| **Previous Year (PY) Wait List** | **640K Patients** |
| **Average Median Wait (All Cases)** | **~11.7 Weeks** |
| **Total Records Analyzed** | 24,640,969 |

> ⏱️ The **latest month** saw a **~10.8% increase** in total wait-listed patients compared to the previous year.

---

### 🔹 Case Type Distribution
| Case Type | % Share | Observation |
|------------|----------|-------------|
| **Outpatient** | ~80% | Dominates the wait list volume |
| **Day Case** | ~12% | Moderate share |
| **Inpatient** | ~8% | Least proportion but longest waits |

> 🩺 Outpatient cases contribute the **majority of backlog**, requiring better scheduling and triage.

---

### 🔹 Time Band vs Age Profile
| Time Band | Avg Wait (Weeks) | Median Wait (Weeks) |
|------------|------------------|---------------------|
| 0–3 Months | 90.56 | 101 |
| 3–6 Months | 98.77 | 107 |
| 6–9 Months | 108.67 | 136 |
| 9–12 Months | 122.22 | 149 |
| 12–15 Months | 149.09 | 207 |
| 15–18 Months | 207.19 | 302 |
| 18+ Months | **302.46** | **Highest Delay** |

> 👶 **Children (0–15)** have shorter waits, while **Adults (65+)** face longer delays in most specialties.

---

### 🔹 Top 5 Specialties (Longest Average Wait)
| Specialty | Avg Wait (Weeks) |
|------------|------------------|
| **Paediatric Dermatology** | **167.89** |
| **Paediatric ENT** | 147.55 |
| **Paediatric Orthopaedics** | 114.50 |
| **Accident & Emergency** | 111.19 |
| **Paediatric Cardiology** | 101.77 |

> 🚨 Specialized pediatric services experience **severe bottlenecks**, needing **capacity expansion** and **process optimization**.

---

### 🔹 Monthly Trends (2018–2021)
| Year | Total Wait List | Observation |
|------|------------------|--------------|
| **2018** | ~5.86 Lakh | Stable baseline |
| **2019** | ~6.29 Lakh | Gradual increase |
| **2020** | ~6.13 Lakh | Slight dip (COVID period) |
| **2021** | **6.40–7.09 Lakh** | Noticeable post-pandemic surge |

> 📈 The trend shows a **consistent increase** post-2020, signaling **growing healthcare demand** and **delayed care backlogs**.

---

## 📊 Detailed Metrics Snapshot (Extracted from Power BI)
| Archive Date | Day Case | Inpatient | Outpatient | Total Patients |
|---------------|-----------|------------|--------------|----------------|
| Jan 2018 | 57,267 | 22,937 | 502,482 | 582,686 |
| Mar 2018 | 57,095 | 22,963 | 504,111 | 584,169 |
| Dec 2018 | 50,324 | 19,880 | 516,162 | 586,366 |
| Jun 2019 | 49,168 | 20,503 | 560,251 | 629,922 |
| Dec 2020 | 51,500 | 20,800 | 606,000 | 678,300 |
| Mar 2021 | — | — | — | **709,000** |

> 🧾 Over **24 million records** analyzed, capturing trends across **case types and time bands**.

---

## 💡 Business & Operational Recommendations
1. 🕒 **Prioritize long-wait cases** (15+ months) via fast-track clinics or weekend schedules.  
2. 👶 **Increase pediatric specialty capacity**, especially Dermatology & ENT.  
3. 📊 Implement **monthly monitoring dashboards** to proactively identify growing backlogs.  
4. ⚙️ Optimize **Outpatient scheduling** — it represents 80% of patient load.  
5. 🧍 Introduce **age-prioritized appointment strategies** for senior patients (65+).  
6. 💻 Deploy **digital patient management systems** to automate wait tracking and reduce manual delays.  

---

## 🛠️ Tools & Technologies
- **Power BI Desktop** – Data modeling & visualization  
- **Excel / CSV Data Source** – Source data files  
- **DAX & Power Query** – Data cleaning and transformation  
- **Visualizations:** Line charts, KPI cards, slicers, bar charts, and filters  

---

## 📂 Dashboard Features
- 📊 KPI Cards showing **Total Wait List, Year-over-Year Change, Average Wait Times**  
- 📈 **Monthly Trends** for each case type (Outpatient, Day Case, Inpatient)  
- 👨‍⚕️ **Top 5 Specialties** with longest waiting periods  
- 🕐 **Time Band vs. Age Profile Matrix**  
- 📅 Filter options by **Year, Specialty, and Case Type**  
- 🧾 Detailed data table for historic performance  

---

## 📸 Dashboard Snapshot
*(Add visuals here — for example: `![Dashboard Overview](images/waitlist_dashboard.png)`)*

---

## 👤 Author
**Sourbh Choudhary**  
💼 QA Automation Engineer | Power BI Developer | Data Analyst  
📧 [csourbh9@gmail.com](mailto:csourbh9@gmail.com)  
🔗 [LinkedIn](#) | [GitHub](#)

---

## 🏁 Summary
This Power BI dashboard enables a **data-driven understanding of patient wait times** and helps **healthcare management** identify critical operational inefficiencies.  
It demonstrates skills in **data storytelling, DAX modeling, and healthcare analytics**, making it a strong portfolio project for roles in **Business Intelligence and Data Analysis**.
