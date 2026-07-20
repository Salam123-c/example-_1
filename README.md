# 📊 WFM Data Analyst Assessment — Multi-Client Contact Centre

&gt; **Hiring Assessment Submission** | Workforce Management Analytics  
&gt; **Status:** ✅ Completed | **Time:** 48 Hours | **Score:** Self-Evaluated

---

## 🎯 Business Problem

Service Level has **declined** while **call volume** and **shrinkage** increased.  
**Objective:** Clean data → Analyze KPIs → Build Dashboard → Provide Recommendations

---

## 📈 Key Results (Executive Summary)

| KPI | Company-Wide | Best LOB | Worst LOB |
|-----|-------------|----------|-----------|
| **Forecast Accuracy** | 41.4% | Telecom (45.2%) | Banking (33.1%) |
| **Service Level %** | 77.3% | Telecom (78.9%) | Banking (75.8%) |
| **Shrinkage %** | 13.5% | Retail (13.3%) | Telecom (13.8%) |
| **Occupancy %** | 76.8% | Banking (77.4%) | Healthcare (76.5%) |
| **Avg AHT** | 344.4s | Banking (336.4s) | Healthcare (352.0s) |
| **Avg CSAT** | 3.74/5 | Healthcare (3.76) | Retail (3.73) |
| **Avg QA Score** | 82.3 | Healthcare (82.7) | Banking (81.8%) |

---

## 🔧 What I Did (7 Tasks)

| # | Task | Status | Tools Used |
|---|------|--------|------------|
| 1 | **Data Cleaning** — 8 issues documented, 1,441 duplicates removed | ✅ | Excel, Python |
| 2 | **KPI Calculation** — Forecast Accuracy, Shrinkage, Occupancy, AHT, CSAT, QA | ✅ | Excel formulas |
| 3 | **Pivot Tables** — By LOB, Site, Month | ✅ | SUMIFS/AVERAGEIFS |
| 4 | **Executive Dashboard** — With slicers & KPI cards | ✅ | Excel, Python |
| 5 | **Top 5 Risks Identified** | ✅ | Business analysis |
| 6 | **10 Business Recommendations** | ✅ | Strategic consulting |
| 7 | **Assumptions Documented** | ✅ | Documentation |

---

## 🛠️ Tech Stack

![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 📸 Dashboard Preview

### Executive Dashboard — KPI Cards
![Dashboard KPI Cards](assets/dashboard-kpi.png)

### Monthly Forecast vs Actual Calls
![Forecast vs Actual](assets/forecast-vs-actual.png)

### Service Level Trend (Jun 1-14)
![SL Trend](assets/sl-trend.png)

### Shrinkage & Service Level by LOB
![LOB Analysis](assets/lob-analysis.png)

---

## 🚨 Top 5 Operational Risks

| Rank | Risk | Evidence | Business Impact |
|------|------|----------|---------------|
| 1 | **Forecast Accuracy Critically Low** | 41% accuracy, 33-45% range | Understaffing/overstaffing, payroll waste |
| 2 | **Service Level Below Target** | 77.3% vs 80% target, volatile | SLA penalties, client churn |
| 3 | **Rising Shrinkage** | 13.5% company-wide, 13.8% in Healthcare/Insurance | Erodes staffed capacity |
| 4 | **Data Quality Gaps** | 743 duplicates, 91 blank CSAT, 6 SL &gt; 100% | Reporting confidence risk |
| 5 | **LOB-Level Imbalance Hidden** | Company avg masks hot/cold spots | Burnout or idle cost |

---

## 💡 10 Business Recommendations

1. **Rebuild forecasting model** with LOB-level seasonality → Target 85% accuracy
2. **Forecast accuracy SLA** with named owner & monthly review
3. **Real-time intraday management** for Banking & Travel (lowest SL)
4. **Explicit SL floor** (70%) with escalation playbook
5. **Root cause shrinkage investigation** in Healthcare/Insurance/Telecom
6. **LOB-level shrinkage budget** in staffing model
7. **Fix data capture at source** — single dropdown for LOB, unique-key constraints
8. **Validation rules** — reject SL &gt; 100%, fix CSAT non-response
9. **LOB-level staffing targets** reviewed monthly
10. **Weekly Executive Dashboard review** cadence

---

## 📊 Data Cleaning Log

| # | Sheet | Issue | Records Affected | Action |
|---|-------|-------|-----------------|--------|
| 1 | Employees | LOB spelling variants | 45 | Standardized to 6 categories |
| 2 | Interval_Staffing | Service Level &gt; 100% | 6 | Capped at 100% |
| 3 | Shrinkage | Duplicate EmpID+Month | 743 | Averaged & collapsed |
| 4 | QA_CSAT | Duplicate EmpID+Month | 698 | Averaged & collapsed |
| 5 | QA_CSAT | Blank CSAT scores | 91 | Excluded from averages |

---

## 📁 Repository Structure
