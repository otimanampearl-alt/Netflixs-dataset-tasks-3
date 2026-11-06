# Task 3 – Country-Wise Content Analysis Dashboard

## Project Overview

This project analyses the country information in a Netflix titles dataset and presents the distribution of Netflix content across countries in an Excel dashboard.

The aim is to identify the countries most represented in the catalogue, compare their title counts, and make it easier to explore country-level patterns using PivotTables, ranking charts, and interactive slicers.

## Task Instructions

**Task 3 (Medium) – Country-Wise Content Analysis Dashboard**

**Description:** Create an interactive dashboard showing Netflix content availability across different countries.

### Task Workflow

1. Build country-wise PivotTables.
2. Create ranking visualizations.
3. Design interactive filters.
4. Highlight top content-producing countries.
5. Present geographical insights.

### Key Features

- Country analysis
- Interactive dashboard
- Ranking charts
- Slicers and filters

### Skills Practised

- Advanced PivotTables
- Excel slicers
- Dashboard interactivity
- Business insight presentation

## Dataset

- **Source:** Netflix titles dataset supplied for the internship task
- **Records:** 8,790 titles
- **Fields used:** `show_id`, `type`, and `country`

The country field can contain more than one country for a title. As a result, the number of country-title associations can be greater than the number of unique titles. Records with missing country information are represented as **Not Given** in the analysis.

## Tools Used

- Microsoft Excel
- PivotTables
- PivotCharts / ranking charts
- Slicers

## Analysis and Dashboard

The workbook contains three worksheets:

| Worksheet | Purpose |
|---|---|
| `Dataset` | Contains the Netflix titles dataset used for the analysis. |
| `Pivot Table` | Contains the country-level summaries and supporting PivotTables. |
| `Dashboards` | Presents the ranking visualizations and interactive dashboard. |

The dashboard workbook includes three ranking charts and slicer controls connected to the analysis. The PivotTables allow country representation and content-type patterns to be explored.

## Key Findings

The leading countries by number of title associations in the country ranking are:

| Rank | Country | Title associations |
|---:|---|---:|
| 1 | United States | 3,240 |
| 2 | India | 1,057 |
| 3 | United Kingdom | 638 |
| 4 | Pakistan | 421 |
| 5 | Canada | 271 |

Other countries appearing in the analysis include Japan (259), South Korea (214), France (213), and Spain (182). The dataset also contains 287 records labelled **Not Given** in the country field.

**Important interpretation note:** These are counts of title-country associations, not unique titles assigned to mutually exclusive countries. A title associated with multiple countries contributes to more than one country's count. Therefore, country counts should not be summed to calculate the number of unique Netflix titles. The 287 “Not Given” records indicate missing country information and are not a country.

## The Three Basic Data Analyst Questions

### 1. What did I analyse, and what question was I trying to answer?

I analysed the country field in the Netflix titles dataset to understand how Netflix content is represented across different countries. The main question was: **Which countries have the highest number of title associations in the dataset, and how does the content distribution vary across countries?**

### 2. What specific finding did the analysis reveal?

The United States had the highest representation, with 3,240 title associations. India followed with 1,057, then the United Kingdom with 638. This shows that the United States had substantially more title associations than the other leading countries in this dataset.

### 3. What action could the findings support?

The findings could help content and strategy teams identify markets with strong catalogue representation and markets with comparatively lower representation. They could use this as a starting point for further research into local content partnerships, regional catalogue gaps, and opportunities to broaden country representation. Before making investment decisions, they would also need to consider audience demand, viewing performance, licensing costs, and other market information. Catalogue counts alone do not establish popularity or profitability.

## Conclusion

This task demonstrates how Excel PivotTables, ranking charts, and slicers can turn country-level dataset information into an interactive dashboard. The analysis highlights the countries with the highest representation and provides a starting point for further geographical and content strategy research.

---

**Project file:** `Netflix_Country_Wise_Content_Analysis_Dashboard.xlsx`
