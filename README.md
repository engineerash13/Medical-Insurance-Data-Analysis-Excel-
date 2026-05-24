# Medical Insurance Data Analysis (Excel)

A structured Excel-based data analysis project examining US medical insurance charges across 1,338 policyholders. The workbook is organized into 9 question-driven analysis sheets covering statistics, gender impact, smoking costs, BMI classification, geographic trends, and advanced correlation — plus a summary dashboard.

**Author:** Ashwin Suryawanshi | **Tool:** Microsoft Excel

---

## Files in This Repository

| File | Description |
|------|-------------|
| `Medical_Insurance_Data_Analysis.xlsx` | Excel workbook — 11 sheets (raw data + 9 analysis sheets + dashboard) |
| `MEDICAL_INSURANCE_DATA_ANALYSIS.pptx` | Presentation — key findings, charts, and business recommendations |

---

## Tools & Technologies

- **Microsoft Excel** — PivotTables, CORREL function, BMI classification formulas, charts
- **PowerPoint** — findings presentation

---

## Dataset

**Source:** US Medical Insurance Costs dataset  
**Size:** 1,338 records × 7 columns

| Column | Type | Description |
|--------|------|-------------|
| `Age` | Numeric | Age of the policyholder |
| `Sex` | Categorical | Male / Female |
| `Bmi` | Numeric | Body Mass Index |
| `Children` | Numeric | Number of dependents covered |
| `Smoker` | Categorical | Yes / No |
| `Region` | Categorical | northeast, northwest, southeast, southwest |
| `Charges` | Numeric | Individual medical insurance charge (USD) |

---

## Analysis Sheets (9 Questions)

| Sheet | Analysis Theme | Key Technique |
|-------|---------------|---------------|
| **Q1** | Basic Statistics & Data Understanding | Descriptive stats — avg charges by region, summary metrics |
| **Q2** | Gender Analysis | Average medical charges by gender; PivotTable by Sex × Region |
| **Q3** | Impact of Smoking on Costs | Average charges — smokers vs non-smokers by region |
| **Q4** | Dependents Analysis | How number of children affects insurance charges |
| **Q5** | Geographical Insights | Average BMI and charges by region — 4-region comparison |
| **Q6** | Cost Distribution Analysis | Sum of charges distribution across segments |
| **Q7** | BMI Classification | Categorized into Underweight (<18.5), Normal (18.5–24.9), Overweight (25+); charges per category |
| **Q8** | Advanced Correlation Analysis | CORREL function — correlation between Age/BMI/Children and Charges |
| **Q9** | Smoking and Region Interaction | Sum of charges — smoker status × region cross-analysis |

---

## Key Insights

| Finding | Detail |
|---------|--------|
| Smoking impact | Smokers pay significantly more — highest charges across all regions |
| Age correlation | Positive correlation between age and insurance charges |
| BMI correlation | Moderate positive correlation — overweight policyholders pay more |
| Regional variation | Southeast region has highest average charges; Northwest is lowest |
| Gender difference | Males have slightly higher average charges than females |
| Dependents | Charges vary non-linearly with number of children — 3 dependents peaks highest |
| BMI classification | Overweight policyholders (BMI >25) carry disproportionately higher charges |
| Smoking × Region | Southwest smokers show the highest combined charge burden |

---

## Workbook Structure

```
Medical_Insurance_Data_Analysis.xlsx
├── DATA SHEET     → Raw 1,338 row dataset
├── Q1             → Basic Statistics & Data Understanding
├── Q2             → Gender Analysis
├── Q3             → Impact of Smoking on Costs
├── Q4             → Dependents Analysis
├── Q5             → Geographical Insights
├── Q6             → Cost Distribution Analysis
├── Q7             → BMI Classification
├── Q8             → Advanced Correlation Analysis
├── Q9             → Smoking and Region Interaction
└── Dashboard      → Summary dashboard
```

---

## Suggested Repo Name

`Medical-Insurance-Cost-Analysis-Excel`

---

## Topics

`excel` `data-analysis` `medical-insurance` `pivot-tables` `correlation-analysis` `eda` `healthcare` `statistics`
