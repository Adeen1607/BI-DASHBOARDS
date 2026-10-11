# Business Intelligence Dashboard Portfolio

A collection of business-intelligence case studies focused on dashboard design, KPI reporting, visual analysis, and data storytelling. The projects use public or study-purpose datasets and do not contain confidential employer or client information.

## Portfolio Contents

### Online Sales Performance Dashboard

**Business objective:** Provide a concise view of sales activity and help users examine performance across the dimensions available in the source dataset.

**Deliverables**
- Tableau packaged workbook: `Online Sales Data Visualization.twbx`
- Presentation summary: `Online Sales Data Visualization.pptx`

**Skills demonstrated**
- Dashboard layout and visual hierarchy
- KPI selection
- Trend and comparative analysis
- Business-focused presentation design

### COVID-19 Trends Dashboard

**Business objective:** Organize public-health data into an accessible dashboard for comparing changes over time and across geographic categories.

**Deliverables**
- Tableau packaged workbook: `COVID-19 DASHBOARD.twbx`
- Presentation summary: `COVID-19 DASHBOARD.pptx`

**Skills demonstrated**
- Time-series visualization
- Geographic comparisons
- Filter and interaction design
- Responsible communication of public data

### Datamation Analysis

**Business objective:** Explore a structured dataset through visual analysis and communicate the most relevant observations in a presentation-ready format.

**Deliverables**
- Tableau packaged workbook: `DATAMATION ANALYSIS.twbx`
- Presentation summary: `DATAMATION ANALYSIS.pptx`
- Supporting narrative: `Data Insights From dashboards.pptx`

**Skills demonstrated**
- Exploratory visual analysis
- Dashboard-to-presentation storytelling
- Selection of decision-relevant observations
- Communication for non-technical audiences

## How to Review the Work

1. Review the PowerPoint files for a quick summary of each dashboard.
2. Download the corresponding `.twbx` file.
3. Open the workbook using Tableau Desktop or Tableau Public.
4. Use the filters and interactive views to explore the underlying analysis.

See [docs/REVIEW_GUIDE.md](docs/REVIEW_GUIDE.md) for a recruiter-oriented review path.

## Data and Privacy

All datasets used in this repository were obtained from public or study-purpose sources. No confidential company, customer, or employer data is included. See [docs/DATA_AND_PRIVACY.md](docs/DATA_AND_PRIVACY.md) for the repository's data-handling principles.

## Repository Roadmap

- Add static dashboard previews that render directly on GitHub
- Document data sources and KPI definitions for each case study
- Add reproducible data-preparation scripts where source data is redistributable
- Expand the portfolio with Power BI case studies and analytical notebooks

## Author

**Mohammed Adeen Shaik**  
[LinkedIn](https://www.linkedin.com/in/as1607/) | [GitHub](https://github.com/Adeen1607)



## Rebuild the reading edition

```bash
python -m pip install -r requirements-research.txt
python scripts/build_research_site.py
```

This renders saved notebook outputs without rerunning model training or external APIs. To refresh findings, run the analysis commands above first, update `reports/research-findings.md`, and rebuild.

<!-- research-edition:start -->
## Research edition

[Research report and final visual results](research/report.md) · [Browser-ready notebook catalogue](research/notebooks.html)

Evidence status: historical outputs or implementation only. Numerical findings are limited to the original artifacts; no new model performance is claimed.

The `research/` folder contains a professional static reading edition. The Pages workflow deploys it after GitHub Pages is enabled with **GitHub Actions** as the publishing source. Intended URL: `https://adeen1607.github.io/BI-DASHBOARDS/`. Deployment status must be checked in Actions before treating that address as live.

<!-- research-edition:end -->
