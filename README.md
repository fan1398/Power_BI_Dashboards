# Data Jobs Dashboard | Power BI Portfolio Project

**Independent business intelligence project | Power BI Desktop • Power Query • DAX • Data Modeling • GitHub • Visual Studio Code**

## Project Overview

This project explores data-related job postings and helps users compare employment opportunities, in-demand skills, job titles, and compensation. I developed and documented the Power BI report as a hands-on demonstration of business intelligence (BI) development, data preparation, analytical modeling, and interactive reporting.

The report uses a 2024 data-job-postings dataset. Although the example domain is workforce analytics, the same BI workflow—transforming source data into reliable metrics and decision-oriented visualizations—can be applied to healthcare quality, utilization, operations, and financial reporting.

## Report Contents

The uploaded `.pbix` project contains **three report pages**, with interactive visuals including KPI cards, slicers, bar charts, donut charts, a matrix, a gauge, and a scatter plot. The project focuses on:

- Job-posting activity and comparisons by job attributes
- In-demand technical skills and skill frequency
- Compensation comparisons across job categories
- Interactive exploration using user-selected filters

### Dashboard previews

![Dashboard page 1](Images/Page%201.jpg)
![Dashboard page 2](Images/Page%202.jpg)
![Dashboard page 3](Images/Page%203.jpg)

## Business Intelligence Skills Demonstrated

| Skill / technology | Application in this project |
| --- | --- |
| **Power BI Desktop** | Developed a multi-page interactive BI report and arranged visuals for analytical exploration. |
| **Power Query / ETL** | Prepared and transformed source data as described in the project development notes. |
| **Data modeling** | Worked with related job and skill tables, applying relational modeling / star-schema concepts. |
| **DAX (Data Analysis Expressions)** | Created reusable measures and calculations to aggregate and analyze job and skills data. |
| **DAX query view** | Used `EVALUATE`, `SUMMARIZECOLUMNS`, and `COUNTROWS` while inspecting and testing measures. |
| **KPI and metric design** | Presented high-level job and skills metrics for quick comparison and interpretation. |
| **Data visualization** | Used bar, donut, scatter, gauge, card, and matrix visuals suited to different analytical questions. |
| **Interactive reporting** | Added slicers to let viewers refine the data displayed. |
| **Visual Studio Code** | Used as part of the development and GitHub documentation workflow. |
| **Git / GitHub portfolio** | Organized and shared report files and project documentation for review. |

### Example of DAX logic from the project

The Power BI file includes a measure that counts job–skill records:

```dax
Skill Count = COUNTROWS(skills_job_dim)
```

Its stored DAX queries also use `SUMMARIZECOLUMNS` to return aggregated measure results. DAX measures are sensitive to filter context, enabling interactive reporting when combined with appropriate model relationships and report slicers.

## Analytical Development Workflow

1. **Understand the data:** Review job titles, job-posting records, compensation fields, and skill associations.
2. **Prepare the data:** Apply Power Query transformations and assess column types, completeness, and consistency.
3. **Model related tables:** Connect job-related and skill-related data to support reusable calculations and filtering.
4. **Develop DAX metrics:** Define measures for analytical summaries and explore their results with DAX queries.
5. **Build visual analytics:** Develop charts, KPIs, matrices, and slicers across the report pages.
6. **Document and share:** Maintain a clear project README and share the `.pbix` report using GitHub and a Visual Studio Code workflow.

## Relevance to Healthcare Enterprise Analytics

The BI practices showcased here are transferable to the work of an enterprise healthcare analytics team:

- Converting large datasets into understandable KPI reports for decision-makers
- Establishing consistent data definitions and reusable measures
- Transforming and joining information from multiple related data tables
- Building interactive dashboards for performance analysis and exploration
- Communicating patterns, outliers, and trends clearly to nontechnical stakeholders

My separate professional background includes healthcare claims, Medicaid/Medi-Cal, utilization, quality performance, SQL-based data preparation, financial reporting, and hospital decision support. Those capabilities are documented in my professional resume.

## Open the Report

- [Download the Power BI report file](Data_Jobs_Dashboard_H.pbix)
- Open the `.pbix` file in **Microsoft Power BI Desktop** to explore the interactive report.

**Important:** Storing a `.pbix` file on GitHub lets others download it; it does **not**, by itself, host a live Power BI dashboard in a browser. 

## Tools and Technologies

`Power BI Desktop` · `Power Query` · `DAX` · `Relational Data Modeling` · `Data Visualization` · `DAX Query View` · `Visual Studio Code` · `GitHub` 

## Notes

This portfolio showcases technical learning and independent BI development. The source data and file dependencies must be available for refresh; users may need to update local file paths under **Transform data → Data source settings** if opening the `.pbix` file on another computer.


