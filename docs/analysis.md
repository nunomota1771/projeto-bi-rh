# Analysis notes

## Source data

The supplied CSV is semicolon-delimited and contains 1,470 rows with 38 columns. The main target field is `Attrition`, with values `Yes` and `No`.

## Reproducible headline metrics

Calculated from `data/Employee_Attrition_Dataset.csv`:

- Employees: 1,470
- Attrition rate: 16.12%
- Average age: 36.92
- Average monthly income: 6,502.93
- Attrition among employees working overtime: 30.53%

Higher observed attrition segments in this sample include:

- Sales Representatives: 39.76%
- Laboratory Technicians: 23.94%
- Human Resources: 23.08%
- Employees travelling frequently: 24.91%

These are descriptive sample statistics, not causal findings.

## Power BI content

The PBIX package includes report definitions, custom visuals and static resources for an interactive HR dashboard. The report focuses on attrition, satisfaction, diversity and workforce-risk views.
