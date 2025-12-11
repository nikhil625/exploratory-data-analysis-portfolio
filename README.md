# Exploratory Data Analysis & Statistical Modeling Case Studies

**Multi-domain EDA projects showcasing data cleaning, feature engineering, dimensionality reduction, clustering, and hypothesis testing.**

**Tech highlights:** KNN imputation, feature engineering, PCA, t-SNE, DBSCAN, t-tests, ANOVA, correlation analysis.

---

## Repository structure

```
eda-case-studies/
├── Netflix/
│   ├── netflix_eda.ipynb
│   └── README.md
├── Walmart/
│   ├── walmart_blackfriday_eda.ipynb
│   └── README.md
├── Delhivery/
│   ├── delhivery_feature_engineering.ipynb
│   └── README.md
├── Yulu/
│   ├── yulu_demand_analysis.ipynb
│   └── README.md
├── assets/
│   └── ...
└── README.md
```

---

## Consolidated Summary

This repository consolidates four domain-specific EDA case studies:
- **Netflix** — content & genre analysis, seasonal release trends, audience segmentation.
- **Walmart** — Black Friday purchase behavior and customer segmentation (spend patterns by gender and category).
- **Delhivery** — operations & feature engineering for logistics KPIs and forecasting readiness.
- **Yulu** — micro-mobility demand analysis and seasonality/weather impacts.

Each project demonstrates:
- Data cleaning & missing-value imputation (KNN imputation)
- Feature engineering & data pipeline readiness
- Dimensionality reduction (PCA & t-SNE) for visualization
- Clustering (DBSCAN) for segment detection & anomaly discovery
- Statistical validations (t-tests, ANOVA) for hypothesis testing
- Visualizations to communicate actionable business insights

---

## Colab Notebooks (original links)
- Netflix: https://colab.research.google.com/drive/1FMnqRffxwj48SklJg6VZ6Z1nsRTLmEBc?usp=sharing
- Walmart: https://colab.research.google.com/drive/1szhMxVfLP_uPZPd_JmoSPqlW8pvYjENM?usp=sharing
- Delhivery: https://colab.research.google.com/drive/1MYclHB7lBUMKy93ikRIjEAAWl9HAqHRH?usp=sharing
- Yulu: https://colab.research.google.com/drive/1eqpZp5Tp3qDqzpUjGCFRWwORcYFtSXAD?usp=sharing

---

## How to run locally
1. Install requirements:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn scipy jupyter
   ```
2. Open notebooks with Colab and `Runtime → Run all`.

---

## Key Findings (Short)

- **Netflix:** Movies dominate titles; content-addition spikes around July & December; recurring popular genres include romance, adventure, and family — recommendations for content diversification and region-specific strategy.
- **Walmart:** Higher average transaction spend observed for male shoppers during Black Friday; recommended targeted promotions for high-value categories and bundling strategies for other segments.
- **Delhivery:** Identified delivery performance drivers and data-quality issues; recommended feature creation and pipeline fixes to improve forecasting accuracy.
- **Yulu:** Demand shows strong seasonality and weather sensitivity; peak demand in fall — recommended demand-driven rebalancing and weather-aware operational planning.

---

## Techniques & Tools

- **Languages / Libraries:** Python (pandas, numpy, matplotlib, seaborn, scipy, scikit-learn)
- **Preprocessing:** KNN imputation (scikit-learn's KNNImputer), outlier detection, scaling
- **Dimensionality Reduction:** PCA, t-SNE
- **Clustering / Segmentation:** DBSCAN (density-based), k-means (where applicable)
- **Statistical Tests:** t-tests, ANOVA, correlation analysis
- **Visualization:** matplotlib, seaborn, plotly 

---

## Contributing

If you'd like to contribute improvements, please fork the repo and open a PR.

---

## License

MIT License
