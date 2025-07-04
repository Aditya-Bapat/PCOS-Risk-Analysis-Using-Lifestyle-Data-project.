PCOS Risk Analysis Using Lifestyle Data project.

This project explores patterns between lifestyle factors and the risk of Polycystic Ovary Syndrome (PCOS) using both manual EDA in Python and an interactive dashboard in Power BI.

Files Included
Cleaned-Data.csv — Preprocessed dataset (173 records, 36 features)
code.ipynb — Python notebook with manual EDA and visualizations
pcos_power_bi_dashboard.pbix — Power BI report file
pcos_power_bi_dashboard.pdf — Snapshot of the Power BI dashboard
README.md — Project summary and documentation

Project Summary
Performed exploratory data analysis (EDA) on 173 health records with 36 lifestyle and medical features.
Cleaned and standardized categorical values (e.g., "Yes"/"No", "Diagnosed by doctor") to ensure data consistency.
Encoded key binary features (0 = No, 1 = Yes) for simplified analysis.
Created interactive visualizations using Plotly and Seaborn to analyze relationships between PCOS and Hormonal Imbalance,Insulin Resistance,Stress Level,Exercise Frequency.
Identified the top 5 most correlated features with PCOS using correlation heatmaps and bar plots.
Found that Hormonal Imbalance showed the strongest correlation (~0.65+) with PCOS risk.

Power BI Dashboard
Developed an interactive Power BI dashboard for non-technical users to explore:
PCOS distribution across age, marital status, and smoking habits
Impact of diet, sleep hours, stress, and exercise on PCOS
Visual breakdown of medication and health condition effects
Dashboard allows easy filtering by key lifestyle and medical indicators to support better storytelling and data interpretation.

Tools & Technologies
Python: Data Cleaning, Visualization (pandas, seaborn, plotly)
Power BI: Interactive dashboard for lifestyle-health analysis
Jupyter Notebook: EDA workflow
