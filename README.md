# Logistics Data Analytics Internship Project

**Prepared by:** Aachal Raut

This repository contains the Week 1–4 work for a logistics data analytics internship project. The project progresses from strategic planning and data preprocessing to advanced exploratory analysis, visualization, predictive modeling, and operational optimization.

## Project Roadmap

### Week 1 — Strategic Planning and Data Exploration
- Logistics scenario definition
- KPI framework
- Data sources and analytical methods
- Strategic roadmap
- Python analysis concepts

### Week 2 — Data Collection, Cleaning, and Preprocessing
- Public logistics dataset planning
- Data quality checks
- Missing-value handling
- Duplicate validation
- Date/time cleaning
- Outlier detection
- Feature engineering
- Normalization

### Week 3 — Advanced Data Analysis and Visualization
- Simulated 500-shipment logistics dataset
- Descriptive statistics and distributions
- Zone and transport-mode analysis
- Correlation analysis
- Delivery-time, traffic, distance, and cost visualizations
- Operational bottleneck interpretation

### Week 4 — Predictive Modeling and Optimization
- Delivery-time forecasting
- Linear Regression, Random Forest, and Gradient Boosting comparison
- MAE, RMSE, R²
- 5-fold cross-validation
- Actual-vs-predicted and residual analysis
- Scenario-based transport-mode optimization

## Repository Structure

```text
logistics-data-analytics/
├── README.md
├── GITHUB_UPLOAD_GUIDE.md
├── requirements.txt
├── .gitignore
├── LICENSE
├── week-1-strategic-planning/
├── week-2-data-preprocessing/
├── week-3-advanced-analysis-visualization/
│   ├── README.md
│   ├── Week_3_Advanced_Data_Analysis_and_Visualization_Report.docx
│   └── visualizations/
├── week-4-predictive-modeling-optimization/
│   ├── README.md
│   ├── Week_4_Predictive_Modeling_and_Optimization_Report.docx
│   ├── model_comparison.csv
│   ├── optimization_scenario.csv
│   └── visualizations/
├── data/
│   ├── raw/
│   │   └── week3_week4_logistics_simulated.csv
│   └── processed/
├── notebooks/
│   ├── week1_exploration.ipynb
│   ├── week2_preprocessing.ipynb
│   ├── week3_advanced_analysis_visualization.ipynb
│   └── week4_predictive_modeling_optimization.ipynb
└── src/
    ├── strategic_analysis.py
    ├── preprocessing.py
    ├── week3_analysis.py
    └── week4_model_optimization.py
```

## Tools
Python, pandas, NumPy, matplotlib, scikit-learn, Jupyter Notebook, and python-docx.

## Week 3 Visual Outputs
Six figures are included in the Week 3 folder and embedded in the report.

## Week 4 Model Results
The model comparison table is generated from the included simulated data. The optimization scenario is a transparent demonstration rather than a production routing optimizer.

## Running the project

```bash
pip install -r requirements.txt
python src/week3_analysis.py
python src/week4_model_optimization.py
```

For notebooks:

```bash
jupyter notebook
```

## Dataset note

Weeks 3–4 use a **simulated logistics dataset** created specifically for this internship task. Week 2 references the Brazilian E-Commerce Public Dataset by Olist as a public logistics data source.

## Reproducibility

Random seeds are fixed where appropriate. The Week 3/4 simulated CSV, scripts, notebooks, reports, model comparison, optimization scenario, and visualization outputs are included in this repository.

## Internship submission

The GitHub repository URL can be submitted as the technical project link required by the internship. The repository is structured to show progression across Weeks 1–4.
