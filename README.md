# Financial-BI-Dashboard
Overview
This dashboard transforms a multi-entity SAP balance sheet trend report into an interactive visual analytics experience. The underlying dataset spans 11 business entities, 463 monthly records, and covers January 2022 through January 2026.
All entity names and identifying data have been anonymized to protect client confidentiality — a standard practice when working with proprietary financial data.

Features

KPI Summary Row — Total net position, average monthly movement, peak period, and active entity count, all dynamically updated based on filters
Multi-Entity Trend Chart — Line/area view for monthly data, switchable to stacked bar for annual comparison
Entity Comparison Bar Chart — Horizontal bar ranking all entities by total net position
Activity Mix Donut Chart — Proportional breakdown by absolute transaction volume
Performance Summary Table — Per-entity totals, monthly averages, activity bars, and directional indicators
Interactive Filters — Filter by entity or year with all charts and KPIs updating in sync


Technical Stack
LayerTechnologyData ProcessingPython (pandas, numpy)Source DataSAP GL Trend Report (.xlsx)VisualizationChart.js 4.4FrontendVanilla HTML / CSS / JavaScriptDeploymentGitHub Pages
The data pipeline reads the raw Excel export, parses the multi-header structure, aggregates GL activity by entity and period, applies anonymization mapping, and embeds the result directly into the HTML file as a self-contained artifact — no backend or build tooling required.

Skills Demonstrated

FP&A Analysis — Multi-period balance sheet trend analysis, variance identification, entity-level performance benchmarking
Data Engineering — Parsing complex SAP report structures (merged headers, multi-sheet workbooks, mixed data types) with Python/pandas
Data Visualization — Translating raw GL data into actionable visual narratives for non-technical stakeholders
Financial Data Governance — Anonymization methodology for safe use of client data in demo/portfolio contexts
Frontend Development — Self-contained dashboard with no external dependencies beyond a CDN-hosted charting library


Background
This project is part of an ongoing portfolio of FP&A and analytics work. My background spans financial data analysis, payroll systems, and ERP integrations — including hands-on experience with SAP, Microsoft Dynamics, Workday, and Power BI. I specialize in bridging the gap between raw financial data and actionable business insights, including automating reporting pipelines that previously required significant manual effort.
