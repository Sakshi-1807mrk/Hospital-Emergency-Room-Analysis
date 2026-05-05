#  Hospital Emergency Room Analysis 
# Advanced Excel End to End Data Analytics Projects
# Domain : Healthcare


This project focuses on analyzing hospital emergency room operations. The goal is to understand patient flow, waiting time patterns, and overall service efficiency,better decision-making.

The dashboard helps stakeholders monitor monthly trends for the given years and identify operational gaps and inefficient services delivery in emergency care.

![ER Dashboard](https://raw.githubusercontent.com/Sakshi-1807mrk/Hospital-Emergency-Room-Analysis/main/HealthCare%20ER%20Dashboard.png)
---

## 1) Dataset
* Source: Kaggle
* Size: ~50,000 records
* Fields: 12 columns
  
  The dataset includes:

* Patient demographics (age, gender, race) , Admission details , Department referrals , Wait time , Satisfaction score
* Each row represents a single patient visit.

---

## 2) Tools Used

* **Excel** (Primary analysis & dashboard)
* **Power Query** (Data cleaning & transformation )
* **Power Pivot** (Data modeling & relationships)

---

## 3) Project Workflow

  Raw Dataset → Power Query (Cleaning) → Power Pivot (Modeling) → Calculated Columns → Pivot Tables → Dashboard → Insights → Business Recommendations
  
## 4) Findings and Recommendation

* Average wait time is around **35 minutes**, indicating slight delays.Set service-level benchmarks and continuously monitor delay metrics to ensure patients are attended within acceptable time limits.
* Admission split is roughly **50% admitted / 50% not admitted** . Analyze peak patient inflow periods sorting the urgent cases and allocate medical staff accordingly .
* Majority of cases fall under **general treatment (no department referral)** . Attention must be given to standardize department referral procedures
  
---

## 5) Project Structure

```
├── data/         # Raw dataset   
├── visuals/      # Dashboard screenshots  
├── reports/      # Documentation & insights  
```

---

## 6) Who can use this Dashboard

* Hospital Management – to monitor overall performance and make decisions
* Emergency Room (ER) Staff – to manage patient flow and reduce delays
* Doctors & Nurses – to understand workload and patient trends
* Operations Team – to improve efficiency and resource allocation
* Healthcare Analysts – to study patterns and generate insights
* Quality & Compliance Teams – to track service standards and patient satisfaction
