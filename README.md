# 🇸🇦 Saudi Vision 2030 Project Analysis | Tableau Dashboard



## 📊 Project Overview
The **Saudi Vision 2030 Project Analysis Dashboard** is an interactive Tableau solution designed to monitor, evaluate, and visualize the progress of key initiatives under Saudi Arabia’s **Vision 2030** framework.

This dashboard empowers policymakers and analysts with **real-time, data-driven insights** into project performance, financial health, and risk exposure — enabling smarter governance and strategic alignment with national objectives.

---

## 🎯 Objectives
- Build a **centralized, interactive dashboard** to consolidate project and financial data.
- Provide **real-time visibility** into project status, spending trends, and risk factors.
- Enable **data-driven decision-making** for government stakeholders.
- Improve **transparency and accountability** across all Vision 2030 initiatives.

---

## 🧩 Problem Statement
Managing hundreds of large-scale projects across diverse sectors poses challenges:
- Manual data consolidation causes **delays and inconsistencies**.
- Lack of unified reporting limits **governance visibility**.
- Risk management is **fragmented across multiple agencies**.

This Tableau project addresses these challenges by integrating all data sources into a **single, interactive reporting system** that supports continuous monitoring and proactive intervention.

---

## 🗂️ Dataset Description
The dataset consists of **five interconnected tables** representing project and performance data:

| Table Name | Description |
|-------------|-------------|
| `projects` | Core details such as sector, region, budget, progress, and risks |
| `milestones` | Key project milestones (planned, forecasted, and actual completion dates) |
| `finance_monthly` | Planned vs. actual expenditures and earned value metrics |
| `issuesrisks` | Detailed risk and issue records (severity, category, owner) |
| `agencies` | Agency-level KPIs such as customer satisfaction, efficiency, and digital maturity |

---

## 🧼 Data Preparation (Power Query)
Before Tableau visualization, a **comprehensive ETL process** was performed using **Power Query**:
1. Removed duplicate and inconsistent records.
2. Standardized column names and data types.
3. Handled missing values using imputation/exclusion methods.
4. Established relationships via `ProjectID` and `AgencyID`.
5. Converted date columns for time-series analysis.
6. Derived key calculated fields such as:
   - **Progress %**
   - **Budget Utilization**
   - **Risk Rating**

---

## 📈 Key Insights

### 🔹 Project Portfolio Summary
- **66.7% of projects** are on schedule; one-third need closer monitoring.  
- **Average progress:** 45.7% — most projects are midway.  
- **Budget utilization:** 38.1% — sufficient reserves, but delayed projects risk future budget pressure.

### 🔹 Sector-Wise Project Health
- **Transport:** Balanced — 2 on track, 2 at risk.  
- **ICT:** 3 projects — all at risk 🚨  
- **Culture:** 2 at risk, 1 delayed.  
- **Energy:** 2 at risk.  
- **Health:** Mixed — 1 on track, 1 at risk.  
- **Utilities:** 1 delayed.  
➡️ *ICT and Energy sectors require urgent intervention.*

### 🔹 Regional Progress
| Region | Average Progress |
|---------|------------------|
| Tabuk | **55%** |
| NEOM | **52%** |
| Mecca | 49% |
| AlUla | 47.5% |
| Eastern | 46% |
| Riyadh | 40.7% |
| Medina | 34% |
| Makkah | **30% (lowest)** |

Regions such as **Tabuk and NEOM** are top performers, while **Makkah and Medina** need additional support and oversight.

---

## 💰 Financial Performance Insights
- **Actual spend:** 99.15% of planned — nearly on target.
- **YTD actual spend:** SAR **1,013M** (5.93% of total budget).
- **Variance:** -0.85% — slightly under budget, acceptable if timelines remain intact.
- **Budget Allocation by Pillar:**
  - 🏗️ Thriving Economy — **74.09%**
  - 🕌 Vibrant Society — **25.91%**

---

## ⚠️ Risk Analysis
- **High Risk Areas:** Supply Chain, Schedule, Right of Way, Permitting  
- **Medium Risks:** Utilities, Finance, Environmental, Cooling Systems  
- **Low Risks:** Safety, Vendor, Scope  
➡️ *Immediate focus should be on mitigating high-likelihood, high-impact risks.*

---

## 🧠 Recommendations
1. **Prioritize high-risk projects** for immediate review and corrective action.  
2. **Reallocate underused budgets** to faster-moving initiatives.  
3. **Enforce stricter schedule monitoring** to reduce project delays.  
4. **Empower agencies** through training and process optimization.  
5. **Maintain real-time data updates** in Tableau for continuous governance visibility.

---

## 🛠️ Tools & Technologies
| Tool | Purpose |
|------|----------|
| **Tableau** | Dashboard design, data visualization |
| **Power Query (Excel/Power BI)** | Data cleaning and transformation |
| **Microsoft Excel** | Data review and structure setup |

---

## 🌐 Dashboard Preview
*(Add a screenshot or Tableau Public link here)*  
🔗 [View Interactive Dashboard on Tableau Public](#)

---

## 📢 Impact
This project demonstrates how **data analytics and visualization** can support Saudi Arabia’s Vision 2030 by improving:
- Project transparency  
- Financial accountability  
- Risk management efficiency  
- Policy decision-making  


