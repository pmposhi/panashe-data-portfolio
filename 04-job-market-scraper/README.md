# UK Tech Job Market Scraper & Skills Demand (Bonus)

## Problem
Briefly describe the business question. What decision does this analysis support?

## Data
- Source: (public dataset or scraped)
- Rows/Columns: (fill after EDA)
- Key fields: (ids, dates, metrics)
- Data issues: (missing values, outliers, duplicates)

## Architecture (Quick)
```
raw_data → cleaning/validation → features/sql → model/metrics → dashboard/report
```

## Steps
1. **Ingest**: Load CSV/API into `/data/raw` (or a DB).
2. **Clean**: Notebook in `/notebooks` writes clean data to `/data/processed`.
3. **Analyze/Model**: Notebook trains model or computes KPIs.
4. **Visualize**: Power BI file in `/powerbi` (export PNG/PDF here too).
5. **Explain**: Add a short business summary (below) with numbers.

## Results (Fill Me In)
- Key metrics: (e.g., MAPE = 8.4%, AUC = 0.87)
- Top drivers: (e.g., recency, tenure, promo)
- Business impact: (e.g., forecast accuracy → better staffing)
- Link to dashboard/report: (if published; else PNG/PDF in `/powerbi/exports`)

## How to Run
```
conda create -n data-portfolio python=3.11 -y
conda activate data-portfolio
pip install -r requirements.txt
# open notebooks in /notebooks and run top to bottom
```
Optional: Use `make run` if you add a Makefile.

## Repository Layout
```
.
├─ data/
│  ├─ raw/
│  └─ processed/
├─ notebooks/
│  ├─ 01_exploration.ipynb
│  └─ 02_model_or_analysis.ipynb
├─ src/
│  ├─ __init__.py
│  └─ utils.py
├─ sql/
│  └─ queries.sql
├─ powerbi/
│  ├─ report.pbix
│  └─ exports/
└─ README.md
```

## Business Summary
- Context:
- Insight:
- Recommendation:
- Next steps: