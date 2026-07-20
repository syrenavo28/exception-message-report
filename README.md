# 📊 SAP Exception Message Report Automation

<p align="center">

<img src="https://img.shields.io/badge/Language-Excel%20VBA-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white">

<img src="https://img.shields.io/badge/System-SAP-0FAAFF?style=for-the-badge&logo=sap&logoColor=white">

<img src="https://img.shields.io/badge/Domain-Supply%20Chain-orange?style=for-the-badge">

<img src="https://img.shields.io/badge/Automation-Workflow-success?style=for-the-badge">

<img src="https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge">

</p>

> ### 🚀 Automates SAP MRP exception message reporting by consolidating multiple SAP exports into one centralized report, allowing procurement teams to quickly prioritize buyer actions through automated business rules and color-coded priorities.

---

> [!IMPORTANT]
>
> **Confidentiality Notice**
>
> All datasets, screenshots, material numbers, supplier names, purchase orders, and business records shown in this repository have been **anonymized, modified, or synthetically generated** for demonstration purposes. No confidential or proprietary information from **Phillips & Temro Industries** is included.

---

# 📖 Overview

This project is an **Excel VBA automation tool** developed during my Supply Chain internship at **Phillips & Temro Industries**.

The tool streamlines SAP procurement planning by importing multiple SAP reports, consolidating exception message data into a single report, and automatically prioritizing buyer actions based on predefined business rules.

Instead of reviewing hundreds of exception messages manually across separate spreadsheets, buyers receive one centralized report highlighting the materials requiring immediate attention.

---

# 🎯 Business Objective

## Problem

Every week, buyers must review SAP-generated exception messages to determine which purchase orders require action.

Without automation:

- Buyers manually review multiple SAP exports
- Critical exception messages can be overlooked
- Each buyer maintains separate reports
- There is no centralized view of procurement priorities
- The review process is repetitive and time-consuming

---

## Solution

This VBA automation:

- 📥 Imports SAP export files
- 🔄 Consolidates data into one report
- 🔍 Matches materials automatically
- 🚦 Assigns priority levels based on business rules
- 🎨 Applies automatic color coding
- 📊 Generates a centralized report for the purchasing team

---

# ⚙️ Workflow

```text
          SAP Export Reports
        (MD07 + ZMMR500)
                │
                ▼
        Excel VBA Automation
                │
     ┌──────────┼──────────┐
     │          │          │
     ▼          ▼          ▼
 Match Data  Apply Rules  Color Priority
     │          │          │
     └──────────┼──────────┘
                ▼
    Centralized Exception Report
                │
                ▼
      Buyers Prioritize Actions
```

---

# ✨ Features

- ✅ Imports multiple SAP reports automatically
- ✅ Centralizes exception messages into one report
- ✅ Supports SAP exception codes (10, 15, 20, 30)
- ✅ Automatic priority assignment
- ✅ Color-coded buyer actions
- ✅ Auto-sorts highest priority items
- ✅ Dynamic summary by purchasing group
- ✅ Buyer notes persist after refresh
- ✅ Automated report generation with one click

---

# 🧠 How It Works

The VBA macro reads SAP export files, matches records by **material number**, applies predefined business rules, and generates a centralized exception report.

Each material is automatically categorized into a priority level and color-coded so buyers can immediately identify the most urgent purchasing actions.

---

# 🛠 Technology Stack

| Technology | Purpose |
|------------|---------|
| 📗 Excel VBA | Workflow automation |
| 💼 SAP ERP | Enterprise Resource Planning |
| 📦 SAP MD07 | Material planning data |
| 📄 SAP ZMMR500 | Exception message report |
| 📊 Microsoft Excel | Reporting & dashboard |

---

# 📂 Repository Structure

```text
SAP-Exception-Report/
│
├── Exception_Report.xlsm
├── README.md
│
├── images/
│   ├── report_overview.png
│   ├── summary_dashboard.png
│   ├── charts.png
│   └── workflow.png
│
└── sample-data/
```

---

# 📈 Business Impact

This automation transforms a repetitive procurement reporting process into a standardized workflow by:

- ⏱ Reducing manual report preparation
- 📊 Improving visibility across buyers
- ⚡ Enabling faster prioritization of critical purchasing actions
- 🤝 Providing one centralized report for the procurement team
- 📋 Standardizing weekly exception message reviews

---

# 📸 Project Snapshots

## 📄 Exception Report

![Exception Report](images/report_overview.png)

---

## 📊 Summary Dashboard

![Summary Dashboard](images/summary_dashboard.png)

---

## 📈 Charts

![Charts](images/charts.png)

---

# 🚀 Future Improvements

- 🔗 Direct SAP data integration
- 📊 Interactive Power BI dashboard
- 📧 Automatic email alerts for critical exception messages
- 📅 Historical trend analysis
- ⚡ Power Query integration
- 🗄 SQL database support

---

# 👩‍💻 Author

**Syrena Vo**
📫 Feel free to connect or explore my other projects!
