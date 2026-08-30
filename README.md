# Sales Dashboard Analysis

## Overview
Analysis of 12 months of retail sales data (50,000+ records) to identify revenue trends, top-selling products, and customer segments. Visualized using Python and Power BI.

## Business Problem
Not specified in the source material. Consider adding a one-line problem statement here (e.g. what triggered this analysis, or what decision it supports) before publishing.

## Dataset
- Size: 50,000+ rows
- Time period: January to December 2023
- Source: Kaggle

## Project Structure
```
sales-dashboard-analysis/
├── data/
│   ├── raw/          # Original data (gitignored)
│   └── processed/    # Cleaned data
├── notebooks/
│   ├── 01_eda.ipynb
│   └── 02_analysis.ipynb
├── sql/              # SQL queries
├── outputs/          # Charts & exports
├── requirements.txt
└── README.md
```

## Tools Used
| Tool | Purpose |
|---|---|
| Python | Data cleaning and exploratory data analysis |
| Pandas | Data manipulation |
| SQL | Querying and aggregation |
| Power BI | Interactive dashboard |
| Matplotlib | Data visualization |

## How to Run / View
```
git clone https://github.com/yourusername/sales-dashboard-analysis.git
cd sales-dashboard-analysis
pip install -r requirements.txt
jupyter notebook notebooks/01_eda.ipynb
```
Dashboard preview: `outputs/dashboard_preview.png`

## Analysis Workflow
Not explicitly listed in the source material. Based on the folder structure, the likely order is:
1. Clean and explore data (`01_eda.ipynb`)
2. Run deeper analysis (`02_analysis.ipynb`)
3. Build Power BI dashboard from processed data

Confirm and adjust this before publishing.

## Key Findings
- Top 3 products contribute approximately 67% of total Q4 revenue
- November shows consistent peak performance, with 43% month-over-month growth
- VIP customers (8% of users) generate 52% of total revenue

## Business Impact / Recommendation
Not specified in the source material. Since three of the findings point toward concentration (in products, in one month, and in a customer segment), a natural next step would be to state what action follows, for example, inventory planning around the top 3 products, or a retention strategy for the VIP segment. Add this once the underlying decision or use case is confirmed.

## Future Improvements
Not specified in the source material. Add 2-3 realistic next steps here (e.g. extending the analysis to 2024 data, adding a churn view for the VIP segment).

## Author
Ahsan Chowdhury — Data Analyst
- LinkedIn: https://linkedin.com/in/ahsanxdata
- Portfolio: https://yourportfolio.com

## License
MIT
