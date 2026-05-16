# Healthcare Data Analyst Project — OCD Patient Analysis
**End-to-End Data Pipeline: CSV Dataset → SQL (MySQL) → Excel → Power BI**

---

## 🎯 Project Objective

This project analyzes OCD (Obsessive-Compulsive Disorder) patient data to uncover patterns across demographics, diagnosis trends, and symptom types. The goal is to translate raw clinical data into clear, actionable insights through SQL-based analysis and interactive dashboards.

---

## 📊 Executive Summary Dashboard

This view provides a high-level overview of OCD patient distribution across gender, ethnicity, diagnosis timelines, and symptom categories.

**Key Metric:** Analyzed a dataset of OCD patients, measuring Y-BOCS obsession severity scores across multiple demographic and clinical dimensions.

---

## 📈 Key Insights

- **Gender Split:** Female and male patients are nearly equally represented. Average Y-BOCS obsession scores show minimal difference between genders, suggesting symptom severity is not strongly gender-dependent in this dataset.

- **Ethnicity Patterns:** Patient counts and average obsession scores vary across ethnic groups, identifying communities that present with higher symptom severity — useful for targeted clinical outreach.

- **Diagnosis Trends (MoM):** Month-over-month diagnosis counts reveal periods of increased OCD reporting, which can inform staffing, resource planning, and awareness campaign timing.

- **Obsession & Compulsion Types:** Certain obsession and compulsion categories are significantly more prevalent. The most common types also carry higher average Y-BOCS scores, meaning frequency and severity align — making them priority areas for treatment focus.

---

## 🔍 Analytical Outputs

Using SQL aggregations and Power BI visuals, the project delivers:

- A **demographic breakdown** of OCD prevalence by gender and ethnicity
- A **monthly diagnosis trend** to identify peaks in patient intake
- A **ranked list of obsession and compulsion types** by patient count and average severity score
- An **Excel dashboard** for offline exploration and summary reporting

---

## 🛠️ Technology Stack

| Tool | Purpose |
|------|---------|
| **MySQL** | Data extraction, grouping, and aggregation queries |
| **Microsoft Excel** | Pivot-based dashboard and data summary |
| **Power BI** | Interactive filtering, DAX measures, and visual reporting |

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `ocd_patient_dataset.csv` | Raw OCD patient dataset |
| `health.sql` | SQL queries for all five analyses |
| `health.xlsx` | Excel dashboard |
| `health.pbix` | Power BI interactive report |
| `excel dashboard.png` | Screenshot of Excel dashboard |
| `bi dashboard.png` | Screenshot of Power BI dashboard |

---

## 📸 Dashboards

### Power BI Dashboard
![Power BI Dashboard](bi%20dashboard.png)

### Excel Dashboard
![Excel Dashboard](excel%20dashboard.png)

---

## 👩‍💻 Author

**Anchal Tiwari** — [GitHub Profile](https://github.com/Anchal1811)
