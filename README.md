# 🏥 JEEVANTA
## Healthcare Intelligence, Designed Around the Patient.

<p align="center">
  <strong>An end-to-end Healthcare Analytics & Business Intelligence solution built with Power BI</strong>
</p>

<p align="center">
  <a href="https://app.powerbi.com/view?r=eyJrIjoiMGNkMjQwMWMtZmZlYi00NDgxLTgwNzItNzhjYmE4NWEyNzlkIiwidCI6ImVmNjMyMmZhLTUwOTAtNDhlNi05ZTY0LTU3MDVlY2I5N2JjNyIsImMiOjEwfQ%3D%3D">
    <img src="https://img.shields.io/badge/▶%20EXPLORE%20LIVE%20DASHBOARD-00A896?style=for-the-badge&logo=powerbi&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://drive.google.com/file/d/195Bpxt8euYp0pSErA4oCC6oIoDixmEcB/view?usp=drive_link">
    <img src="https://img.shields.io/badge/📄%20VIEW%20DASHBOARD%20PREVIEW-1677B8?style=for-the-badge"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Healthcare%20Analytics-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/SQL-Data%20Analysis-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/DAX-Analytics-00A65A?style=flat-square"/>
  <img src="https://img.shields.io/badge/Power%20Query-ETL-742774?style=flat-square"/>
  <img src="https://img.shields.io/badge/SVG-Custom%20Visuals-FF6B6B?style=flat-square"/>
  <img src="https://img.shields.io/badge/Status-Completed-22A447?style=flat-square"/>
</p>

---

# 🩺 The Idea

**Jeevanta** is a healthcare analytics project designed to transform hospital data into a connected, interactive decision-support experience.

Healthcare organizations generate information across multiple areas — patients, admissions, clinical activity, doctors, resources, pharmacy and billing. When these areas are analyzed separately, it becomes difficult to understand the bigger operational picture.

Jeevanta brings these perspectives together through a six-page Power BI dashboard.

> **The idea is simple: turn complex healthcare data into information that is easier to understand, explore and act upon.**

---

# 🎯 Business Problem

Hospitals generate large volumes of operational, patient and financial data. The challenge is not simply collecting this information, but converting it into useful insights for decision-making.

### Key business questions addressed by Jeevanta

- How is the hospital performing overall?
- What are the major patient and admission patterns?
- What does the patient population look like?
- How are clinical activities distributed?
- How are doctors, departments and hospital resources being utilized?
- What patterns exist in billing and financial activity?
- What is happening within pharmacy and medicine inventory?
- Can hospital information be explored at an individual patient level?

### Business Objective

Build an interactive healthcare analytics solution that provides a **centralized view of hospital performance, patient information, clinical activity, resources, pharmacy and financial operations.**

### Intended Business Value

Jeevanta can support healthcare stakeholders by helping them:

- Monitor hospital KPIs
- Understand patient and admission patterns
- Identify operational areas requiring attention
- Monitor resource utilization
- Analyze pharmacy inventory
- Review financial and billing activity
- Explore patient-level information through drill-through

> **Business Goal: Turn fragmented healthcare data into clear, connected hospital intelligence.**

---

# 📂 Dataset

Jeevanta uses a structured healthcare dataset containing information across multiple hospital domains.

### Major Data Domains

| Domain | Information |
|---|---|
| 👤 Patients | Patient demographics and profile information |
| 🏥 Admissions | Admission, department, ward and bed information |
| 🩺 Clinical | Diagnosis and diagnostic information |
| 👨‍⚕️ Doctors | Doctor and department information |
| 💊 Pharmacy | Prescription and medicine-related information |
| 💰 Billing | Billing and financial information |
| 🛏️ Resources | Ward, bed and resource information |
| 🛡️ Insurance | Insurance-related financial information |

The raw data was prepared and transformed before being incorporated into the Power BI analytical model.

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| 📊 **Power BI** | Dashboard development, visualization, interaction|
| 🗄️ **SQL** | Data exploration, querying and analytical preparation |
| 🧮 **DAX** | Measures, KPIs and dynamic calculations |
| 🔄 **Power Query** | Data cleaning and transformation |
| 🎨 **SVG** | Custom healthcare-themed dashboard components |
| 🐙 **GitHub** | Version control and project documentation |

---

# 🧩 Data Model

Jeevanta uses a structured analytical data model connecting healthcare transactions with reusable dimensions.

### Core Fact Tables

```text
Fact_Admission
Fact_Billing
Fact_Billing_Detail
Fact_Patient_Diagnostic
Fact_Prescription
