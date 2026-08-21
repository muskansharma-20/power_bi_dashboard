# VAERS Pharmacovigilance & Safety Dashboard

An interactive Power BI dashboard analyzing vaccine safety reports from the Vaccine Adverse Event Reporting System (VAERS). The dashboard explores reporting trends, vaccine characteristics, adverse events, patient demographics, and serious outcomes to provide a comprehensive view of reported vaccine safety events.

## 📊 Dashboard Overview

The dashboard is organized into five analytical pages:

### 1. Pharmacovigilance & Safety Reports Overview
Provides an executive-level overview of the VAERS dataset, including:
- Total reports
- Serious outcome reports
- Unique vaccines
- Reports received over time
- Serious vs. non-serious reports
- Serious outcome profile

### 2. Vaccine Analysis
Analyzes reported vaccines and their characteristics, including:
- Top vaccines by report count
- Vaccine manufacturers
- Vaccine types
- Dose series
- Route of administration
- Vaccination site
- Manufacturer and vaccine-type patterns

### 3. Adverse Event & Symptom Analysis
Examines reported adverse events and symptoms, including:
- Top reported adverse events
- Serious vs. non-serious reports by adverse event
- Adverse event distribution
- Serious adverse events
- Symptom-level analysis

### 4. Patient Demographics
Explores demographic characteristics of reported cases:
- Age-group distribution
- Sex distribution
- Age and sex patterns
- Demographic differences in reported events

### 5. Serious Outcome Analysis
Focuses on serious outcomes reported in VAERS:
- Serious outcomes by age group
- Serious outcomes by sex
- Serious outcomes by vaccine type
- Serious outcome patterns by vaccine manufacturer
- Hospitalization, disability, life-threatening events, death, and ER visits

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Transformation**
- **Data Visualization**
- **Pharmacovigilance Analytics**
- **Microsoft Excel / CSV data processing**

## 🔍 Key Analytical Areas

The dashboard demonstrates analysis of:

- Vaccine safety reporting trends
- Adverse event and symptom frequencies
- Serious and non-serious reporting patterns
- Vaccine and manufacturer reporting profiles
- Patient age and sex distributions
- Serious clinical outcomes
- Vaccine dose series and administration routes

## 📈 Key Features

- Interactive dashboard navigation
- KPI cards for high-level safety metrics
- Dynamic slicers and filters
- Distinct VAERS report counting
- DAX-based measures
- Age-group categorization and sorting
- Serious outcome analysis
- Cross-filtering between vaccine, demographic, and safety dimensions
- Multiple visualization types including line charts, bar charts, donut charts, treemaps, and matrix/heatmap-style analysis

## 🧮 Data & Methodology

The dashboard uses VAERS report-level data and associated vaccine, symptom, and serious-outcome information.

Data preparation included:
- Data cleaning and transformation using Power Query
- Restructuring symptom data into a long format for analysis
- Creation of calculated columns and DAX measures
- Data modeling using relationships between report, vaccine, symptom, and outcome tables
- Distinct report counting using `VAERS_ID`
- Creation of age-group categories for demographic analysis

## ⚠️ Important Disclaimer

VAERS is a spontaneous reporting system. A report submitted to VAERS does not necessarily mean that a vaccine caused the reported adverse event.

The analyses presented in this dashboard describe **reported events and reporting patterns** and should not be interpreted as establishing causality, incidence, or vaccine safety risk.

## 📁 Project Files

- `VAERS_Pharmacovigilance_Safety_Dashboard.pbix` — Power BI dashboard
- `Screenshots/` — Dashboard page screenshots

## 🖥️ Dashboard Preview

### Pharmacovigilance & Safety Reports Overview

![Safety Overview](Screenshots/page-1-safety-overview.png)

### Vaccine Analysis

![Vaccine Analysis](Screenshots/page-2-vaccine-analysis.png)

### Adverse Event & Symptom Analysis

![Adverse Event Analysis](Screenshots/page-3-adverse-event-analysis.png)

### Patient Demographics

![Patient Demographics](Screenshots/page-4-patient-demographics.png)

### Serious Outcome Analysis

![Serious Outcome Analysis](Screenshots/page-5-serious-outcome-analysis.png)

## 👩‍💻 Author

**Muskan Sharma**

M.Pharm | Pharmacovigilance | Clinical Data & Healthcare Analytics
