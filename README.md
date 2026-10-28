# IBM Employee Attrition — Power BI Dashboard

A Power BI project analysing employee attrition patterns using the IBM HR Analytics Employee Attrition & Performance dataset.

## Project goals

- Understand the overall employee attrition rate.
- Identify workforce segments with higher turnover risk.
- Explore the relationship between overtime, travel, job role, satisfaction and attrition.
- Provide an interactive dashboard for HR-oriented exploratory analysis.

## Included assets

- `powerbi/ProjetoGrupo1_v1.7.pbix` — Power BI report.
- `data/Employee_Attrition_Dataset.csv` — source dataset in semicolon-delimited CSV format.
- `data/Survey_PP_Table.xlsx` — supporting survey table supplied with the project.
- `docs/analysis.md` — dataset profile and reproducible headline metrics.

> The PBIX file is approximately 4.0 MB, below GitHub's regular 100 MB per-file limit, so Git LFS is not required for this project.

## Dataset profile

The CSV contains 1,470 employee records and 38 fields, including age, department, job role, business travel, overtime, satisfaction scores, compensation and tenure variables. It is commonly known as the IBM HR Analytics Employee Attrition & Performance dataset and is used here for educational analysis.

## Headline metrics from the supplied CSV

| Metric | Value |
|---|---:|
| Employees | 1,470 |
| Attrition rate | 16.12% |
| Average age | 36.92 |
| Average monthly income | 6,502.93 |
| Attrition among employees working overtime | 30.53% |

The report contains additional breakdowns and interactive views. These figures are calculated from the supplied CSV and may differ from a specific Power BI page if report filters are active.

## How to use

1. Open the PBIX file in Power BI Desktop.
2. If Power BI asks for a source path, point the query to `data/Employee_Attrition_Dataset.csv`.
3. Keep the CSV delimiter set to semicolon (`;`) if changing the source.
4. Review the report pages and use slicers to explore departments, job roles, travel, overtime, satisfaction and demographics.

## Privacy and licensing

No credentials, API keys or private business data are included. The employee records are treated as a public educational dataset; do not use this project to make real employment decisions.

## Repository structure

```text
.
├── data/
│   ├── Employee_Attrition_Dataset.csv
│   └── Survey_PP_Table.xlsx
├── docs/
│   └── analysis.md
├── powerbi/
│   └── ProjetoGrupo1_v1.7.pbix
├── .gitignore
└── README.md
```
