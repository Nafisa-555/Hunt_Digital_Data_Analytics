# Hunt Digital Media – Data Analytics Assignment

### Bg Author
**Nafisa Ansari**

### Objective
Analyze traffic data of 6 apps to understand patterns behind IVT (Invalid Traffic) detection.

### Steps Performed
- Cleaned and preprocessed raw Excel data
- Converted text-based columns to numeric
- Compared IVT vs Non-IVT apps
- Computed correlation and key ratios
- Exported analysis results to Excel

### Key Insights
- Higher `requests_per_idfa` and `idfa_ua_ratio` are strong indicators of Invalid Traffic.
- IVT apps show lower `impressions_per_idfa`, suggesting non-human activity.
- A stable `idfa_ip_ratio` near 1 is a sign of genuine user traffic.

### Output Files
- `hunt_digital_analysis_results.xlsx` – contains Summary, IVT vs Non-IVT, and Correlation.

### Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
