# 📊 Credentially BI Tech Assignment

## 🔍 Overview
This project analyzes delays and trends in the reference-checking process at Credentially. The dashboard focuses on optimizing the submission and review time of candidate references — a critical bottleneck in the hiring pipeline.

---

## 📊 Dashboard Link  

[![Reference Turnaround Dashboard](https://public.tableau.com/thumb/views/ReferenceTurnaroundDashboard/ReferenceTurnaroundDashboard)](https://public.tableau.com/shared/48SF67FP5?:display_count=n&:origin=viz_share_link)

👉 **[Click here to view the full interactive dashboard](https://public.tableau.com/shared/48SF67FP5?:display_count=n&:origin=viz_share_link)**

---

## ✅ Key Metrics (Last 6 Months)

| Metric                     | Value |
|----------------------------|-------|
| **Avg. Time to Submit**    | 0.7 day |
| **Avg. Time to Review**    | 232 days |
| **Outstanding References** | 48 |

---

## 📌 Components Included

- **Dynamic Filters**: Date Range, Assigned To, Job Position Status, Ref Status, Role  
- **KPI Tiles**: Core metrics on submission and review turnaround
- **Trend Line**: Reference requests over time
- **Bar Chart**: Avg. review time by job role
- **Excel-Style Table**: Detailed view of delayed references

---

## 📊 Example Insight

> 📈 **Insight:** While references are typically submitted within a day, the average review time lags behind at 232 days — highlighting a major opportunity to streamline internal approvals.

---

## ⚙️ Tools Used

- Tableau Public (Interactive BI)
- Semantic model data (CSV format)
- Calculated fields: `Time to Submit`, `Time to Review`, `Outstanding Reference Flag`

---

## 📁 Data Handling

- Handled missing values in `Completed Date` and `Approved Date`
- Created calculated fields to track turnaround metrics
- Filtered by real-time parameters for interactive exploration

---

## 🧠 Suggested Business Impact

- Add automated follow-ups after 3 days of inactivity
- Flag references pending review > 14 days
- Prioritize roles with highest delay (e.g., “Black Tea”, “Black Night” at 46-day avg. review)

---

📬 For any further explanation or walkthroughs, feel free to reach out!
