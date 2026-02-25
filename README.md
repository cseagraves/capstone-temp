# QM 2023 Capstone Project

Semester-long capstone for Statistics II: Data Analytics.

## Project Structure

- **code/** — Python scripts and notebooks. Use `config_paths.py` for paths.
- **data/OpenData_rows (1).csv** - OpenData
- **data/raw/** — Original data (read-only)
- **data/processed/** — Intermediate cleaning outputs
- **data/final/** — M1 output: analysis-ready panel
- **results/figures/** — Visualizations
- **results/tables/** — Regression tables, summary stats
- **results/reports/** — Milestone memos
- **tests/** — Autograding test suite

Run `python code/config_paths.py` to verify paths.


Policy Uncertainty & Hiring Cycles
Research Question: Does higher policy uncertainty reduce hiring growth, and are small labor markets more
sensitive than large labor markets?
Datasets:
Dataset Source What It Provides
Economic
Uncertainty Indices
Open Dataset Catalog
(OpenData_rows.csv, id 28; Policy
Uncertainty)
Monthly policy uncertainty
measures
U.S. Bureau of Labor
Statistics (BLS)
Open Dataset Catalog
(OpenData_rows.csv, id 58; BLS)
Employment, unemployment, and
wage growth by region
FRED Openly available (FRED) via pandas-
datareader API
Interest rates and business cycle
controls
Key Variables:
Outcome: Monthly employment growth (%)
Driver: Policy uncertainty index (lagged 1-3 months)
Controls: Interest rates, wage growth, prior employment trend
Groups: Small-population metros vs. large-population metros
Why It's Interesting: Businesses often delay hiring under uncertainty. This project quantifies where labor
markets are most exposed to policy-driven uncertainty shocks.
Option J: Disaster Exposure & Local Housing Markets
7 / 11
Research Question: How do repeated natural disasters affect local housing price growth and volatility in
high-risk counties?
