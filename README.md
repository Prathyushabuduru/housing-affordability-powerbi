# Housing Affordability Analysis — U.S. Census ACS Data Visualization

An interactive Power BI dashboard analyzing the relationship between household income distribution and housing affordability across U.S. metropolitan and micropolitan statistical areas.

## Overview

This project explores how income levels relate to housing characteristics — tenure type, housing costs, and cost burden — across different regions of the United States. The goal is to surface affordability pressures that can support housing policy and planning decisions for social service organizations and regional planners.

## Data Sources

- **ACS S1901** — American Community Survey, 1-Year Estimates: *Income in the Past 12 Months*
- **ACS DP04** — American Community Survey, 5-Year Estimates: *Selected Housing Characteristics*

Both datasets are publicly available through the [U.S. Census Bureau](https://data.census.gov).

## What the Dashboard Includes

- A unified data model integrating multiple public Census Bureau sources, combining quantitative (median income, housing costs, cost burden %) and categorical (tenure type, geographic area) variables
- A 3-page interactive Power BI report featuring:
  - KPI cards for key affordability metrics
  - Scatter and clustered bar charts comparing income and housing costs
  - A geographic map visual for regional comparison
  - Custom box-and-whisker analysis
  - Cross-filtering slicers to explore trends by region
- Findings framed around **housing cost burden** — households spending over 30% of income on housing — to support policy-relevant insights

## Research Questions

- How do income distributions differ across metro and micro areas?
- Which housing characteristics are most closely associated with income levels?
- Do lower-income households face greater housing cost burdens in certain regions?
- How do housing characteristics differ between renters and owners by income level?
- What regional differences emerge when comparing income and housing characteristics?

## Tools & Tech Stack

Power BI · Data Modeling · U.S. Census ACS Data (S1901, DP04)

## Files in This Repo

| File | Description |
|---|---|
| `Housing_Affordability_Dashboard.pbix` | Power BI file — open in Power BI Desktop to explore interactively |
| `Housing_Affordability_Project.pdf` | Written project deliverable covering research goals, dataset justification, and variable descriptions |

## Screenshots

<img width="644" height="375" alt="image" src="https://github.com/user-attachments/assets/8d62c70c-3e90-4fd6-b776-070bf2d5bebb" />


## References

Doran, G. T. (1981). There's a S.M.A.R.T. way to write management's goals and objectives. *Management Review, 70*(11), 35.

U.S. Census Bureau. (2024). *American Community Survey 1-Year Estimates: Income in the Past 12 Months (S1901)*. https://data.census.gov

U.S. Census Bureau. (2023). *American Community Survey 5-Year Estimates: Selected Housing Characteristics (DP04)*. https://data.census.gov
