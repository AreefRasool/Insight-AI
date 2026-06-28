📊 InsightAI — Smart Data Analytics Platform
InsightAI is a fully offline, rule-based data analytics SaaS platform that turns any raw CSV into a complete business intelligence report. Powered by Pandas, Scikit-Learn, Plotly, and Gradio, it delivers automated data cleaning, statistical analysis, machine learning, forecasting, and business insights — all through a premium, enterprise-style dashboard with zero API keys and zero internet dependency for analysis.
Whether you're exploring a new dataset, prototyping a data science workflow, or showcasing analytics capabilities, InsightAI turns raw rows and columns into instant, decision-ready intelligence.
�
�
�
�
�
Load image
Load image
Load image
Load image
Load image
🎯 Features
📁 Smart Dataset Profiling — Instant preview, schema overview, dataset health score, and KPI dashboard the moment a CSV is uploaded.
🧹 One-Click Data Cleaning — Removes duplicates, fixes missing values, converts date columns, trims whitespace, and drops empty columns automatically.
📈 Automatic Visualizations — Bar, line, pie, scatter, histogram, box, violin, correlation heatmap, and pair plots — auto-selected based on your column types.
🧠 Rule-Based Insight Engine — Generates human-readable, analyst-style business insights and actionable recommendations without any external AI API.
📐 Deep Statistical Analysis — Descriptive statistics, skewness & kurtosis, Shapiro-Wilk normality testing, and IQR/Z-score outlier detection.
🤖 Machine Learning Toolkit — K-Means clustering, Linear Regression, Decision Trees, Random Forest feature importance, and PCA — all running locally via Scikit-Learn.
🔮 Time Series Forecasting — Auto-detects date columns and projects future trends using Holt's Linear Trend model, complete with growth rate and seasonality detection.
📤 One-Click Report Export — Download the cleaned dataset, a polished business PDF report, or a plain-text summary report.
🎨 Premium Dashboard UI — A dark, glassmorphism-inspired SaaS interface with a fixed sidebar navigation, gradient accents, and smooth micro-animations.
🛡️ Built-In Error Handling — Gracefully handles empty files, unsupported formats, missing columns, and large datasets.
📸 Preview
Dashboard & Upload Workspace
�
Load image
Dataset Health & KPI Metrics
�
Load image
Business Insights Engine
�
Load image
Correlation Matrix & Statistical Analysis
�
Load image
K-Means Clustering
�
Load image
Forecasting Model
�
Load image
Settings & Cleaning Pipeline
�
Load image
🧰 Tech Stack
Tool
Purpose
Gradio
Interactive web dashboard
Pandas
Data wrangling & cleaning
NumPy
Numerical operations
Plotly
Interactive visualizations
Scikit-Learn
Clustering, regression, trees, PCA
SciPy
Statistical testing
Statsmodels
Time series forecasting
ReportLab
PDF report generation
Python 3.9+
Core application logic
🚀 Getting Started
1. Clone the Repository
Bash
2. Install Dependencies
Bash
3. Run the Application
Bash
The dashboard will launch locally in your browser with a shareable public link.
💡 Prefer Google Colab? Just open a new notebook, paste the contents of app.py into a cell, and run it — the first line installs all dependencies automatically.
🧠 How It Works
Upload any CSV file through the Dashboard page.
Review the auto-generated dataset health score, KPIs, and schema overview.
Run the one-click cleaning pipeline from the Settings page.
Explore auto-generated visualizations and the correlation matrix.
Generate business insights and recommendations from the rule-based engine.
Run clustering, regression, decision trees, or PCA on your data.
Forecast future trends if your dataset contains a date column.
Export your cleaned dataset, PDF report, or summary report from the Reports page.
The entire pipeline runs locally — no data ever leaves your session.
📊 Core Analytics
KPI Dashboard
Tracks:
Rows & Columns
Numeric & Categorical Features
Missing Values & Duplicate Rows
Memory Usage
Data Quality Score
Visual Reports
Correlation Heatmap & Pair Plots
Distribution Charts (Histogram, Box, Violin)
Category Breakdown (Bar, Pie, Top Categories)
Forecast Trend Charts with Moving Average
Machine Learning Outputs
K-Means Cluster Visualization (PCA-projected)
Linear Regression Predicted vs. Actual Plot
Decision Tree Confusion Matrix / Regression Fit
Random Forest Feature Importance Ranking
PCA 2D Projection with Explained Variance
📌 Future Improvements
Multi-file dataset comparison mode
Natural-language query bar for filtering rows
Auto-generated PowerPoint export
Support for Excel (.xlsx) and JSON ingestion
User-saved dashboard templates
Advanced anomaly detection models
👤 Author
Areef Rasool
BSAI Student | AI, Data Science & Networking Enthusiast
📄 License
This project is open-source and available under the MIT License.