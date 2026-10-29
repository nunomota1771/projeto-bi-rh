# Rotatividade de colaboradores — Power BI

## 🇵🇹 Português

Dashboard do Power BI para analisar a rotatividade de colaboradores, o bem-estar no trabalho e os perfis de risco, com o conjunto de dados IBM HR Analytics.

### Objetivos

- Acompanhar a rotatividade e os principais segmentos de risco.
- Analisar a distribuição dos colaboradores por departamento, género, escolaridade, salário e antiguidade.
- Explorar indicadores de bem-estar, envolvimento, satisfação no trabalho, satisfação com o ambiente e equilíbrio entre vida profissional e pessoal.
- Apoiar a análise exploratória de RH através de filtros interativos.

### Páginas do dashboard

- **Visão geral** — colaboradores ativos, distribuição por género, departamentos, escolaridade e salário.
- **Bem-estar organizacional** — bem-estar, envolvimento, satisfação no trabalho, satisfação com o ambiente e equilíbrio entre vida profissional e pessoal.
- **Rotatividade e riscos** — taxa de rotatividade, escalões de idade e antiguidade, salário, horas extraordinárias e perfis de risco.
- **Pontuação de risco** — detalhe dos colaboradores classificados por nível de risco.

### Pré-visualização do dashboard

![Visão geral](images/overview.png)

![Bem-estar organizacional](images/happiness.png)

![Rotatividade e riscos](images/attrition-risks.png)

![Detalhe do risco](images/risk-detail.png)

### Conteúdo do repositório

- `data/Employee_Attrition_Dataset.csv` — conjunto de dados original, separado por ponto e vírgula.
- `data/Data_Normalization.xlsx` — dados normalizados para o modelo.
- `data/Survey.xlsx` — dados de inquérito de apoio.
- `images/` — capturas de ecrã do relatório Power BI.
- `powerbi/IBM_HR_Attrition.pbix` — ficheiro do relatório Power BI.
- `docs/analysis.md` — notas de análise e principais métricas.

O ficheiro PBIX tem cerca de 4 MB, abaixo do limite normal de 100 MB por ficheiro do GitHub. Não é necessário usar Git LFS.

### Principais métricas

Com base no conjunto de dados de colaboradores:

| Métrica | Valor |
|---|---:|
| Colaboradores | 1 470 |
| Taxa de rotatividade | 16,12% |
| Idade média | 36,92 |
| Rendimento mensal médio | 6 502,93 |
| Rotatividade entre colaboradores com horas extraordinárias | 30,53% |

Estas são estatísticas descritivas do conjunto de dados educativo. Os valores do dashboard podem variar quando se aplicam filtros.

### Como utilizar

1. Abre `powerbi/IBM_HR_Attrition.pbix` no Power BI Desktop.
2. Se o modelo pedir uma origem de dados, seleciona os ficheiros da pasta `data/`.
3. Mantém o delimitador do CSV como ponto e vírgula (`;`).
4. Usa a navegação e os filtros do dashboard para explorar o relatório.

### Privacidade e utilização responsável

Este é um projeto educativo que utiliza um conjunto de dados público e sintético sobre RH. Não contém credenciais, chaves de API nem dados privados de empresas. Não uses esta análise para tomar decisões reais sobre emprego.

### Estrutura do repositório

```text
.
├── data/
│   ├── Employee_Attrition_Dataset.csv
│   ├── Data_Normalization.xlsx
│   └── Survey.xlsx
├── docs/
│   └── analysis.md
├── images/
│   ├── cover.png
│   ├── overview.png
│   ├── happiness.png
│   ├── attrition-risks.png
│   └── risk-detail.png
├── powerbi/
│   └── IBM_HR_Attrition.pbix
├── .gitignore
└── README.md
```

---

## 🇬🇧 English

# IBM HR Attrition — Power BI

Power BI dashboard for analysing employee attrition, workforce happiness and employee risk using the IBM HR Analytics dataset.

## Objectives

- Monitor employee attrition and the main risk segments.
- Analyse workforce distribution by department, gender, education, salary and tenure.
- Explore happiness, satisfaction and work-life balance indicators.
- Support HR-oriented exploratory analysis through interactive filters.

## Dashboard pages

- **Overview** — active employees, gender distribution, departments, education and salary.
- **Organizational Happiness** — happiness, job involvement, job satisfaction, environment satisfaction and work-life balance.
- **Attrition & Risks** — attrition rate, age and tenure bands, salary, overtime and risk profiles.
- **Risk Score** — detailed view of employees classified by risk level.

## Dashboard preview

![Overview](images/overview.png)

![Organizational happiness](images/happiness.png)

![Attrition and risks](images/attrition-risks.png)

![Risk detail](images/risk-detail.png)

## Repository contents

- `data/Employee_Attrition_Dataset.csv` — original semicolon-delimited dataset.
- `data/Data_Normalization.xlsx` — normalized data prepared for the model.
- `data/Survey.xlsx` — supporting survey data.
- `images/` — screenshots of the Power BI report.
- `powerbi/IBM_HR_Attrition.pbix` — Power BI report file.
- `docs/analysis.md` — analysis notes and headline metrics.

The PBIX file is approximately 4 MB, below GitHub's regular 100 MB per-file limit, so Git LFS is not required.

## Headline metrics

Based on the supplied employee dataset:

| Metric | Value |
|---|---:|
| Employees | 1,470 |
| Attrition rate | 16.12% |
| Average age | 36.92 |
| Average monthly income | 6,502.93 |
| Attrition among employees working overtime | 30.53% |

These are descriptive statistics from the educational dataset. Dashboard values may vary when filters are applied.

## How to use

1. Open `powerbi/IBM_HR_Attrition.pbix` in Power BI Desktop.
2. If the model requests a data source, use the files in `data/`.
3. Keep the CSV delimiter set to semicolon (`;`).
4. Use the dashboard navigation and slicers to explore the report.

## Privacy and responsible use

This is an educational project using a public synthetic HR dataset. It does not contain credentials, API keys or private company data. Do not use the analysis to make real employment decisions.

## Structure

```text
.
├── data/
│   ├── Employee_Attrition_Dataset.csv
│   ├── Data_Normalization.xlsx
│   └── Survey.xlsx
├── docs/
│   └── analysis.md
├── images/
│   ├── cover.png
│   ├── overview.png
│   ├── happiness.png
│   ├── attrition-risks.png
│   └── risk-detail.png
├── powerbi/
│   └── IBM_HR_Attrition.pbix
├── .gitignore
└── README.md
```
