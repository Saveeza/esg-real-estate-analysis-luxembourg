# 📊 Data Directory – ESG & Real Estate in Luxembourg

This folder contains the cleaned and structured datasets used in the article  
**“Sustainable Real Estate Investment in Luxembourg: ESG Scoring vs. Market Returns.”**

Our data analysis was based on **complex, multi-source simulation and modeling**, combining ESG frameworks, real estate fund performance, sector classification, and statistical diagnostics. Due to the **nascent nature of ESG reporting in Luxembourg**, a significant portion of the work involved **data synthesis, normalization, and modeling** using Python.

The datasets included here are **derived products**—carefully constructed for transparency, reproducibility, and academic rigor. They directly support each visual, model, and conclusion presented in the article.

---

## 📁 Files in this Folder

| File Name | Description |
|-----------|-------------|
| `fund_esg_scores_and_returns.csv` | Contains fund-level data: ESG composite score, annual return, fund size, decile rank, and group label (leader/laggard). Used in scatter plot, regression, decile boxplot, and group comparisons. |
| `fund_esg_subscores.csv` | Environmental, Social, and Governance subscores for each fund, used to analyze subscore-level correlation with returns. |
| `sector_performance_data.csv` | Contains ESG scores and returns broken down by sector (residential, commercial, industrial, mixed-use). Used in the sector performance chart. |
| `ols_regression_residuals.csv` | Regression residuals and fitted values from OLS modeling. Used to create the residual diagnostics plot and test model assumptions. |

---

## 🧠 Notes on Data Generation

- **Composite ESG Scores** were based on real ESG scoring methodologies (e.g. MSCI, GRESB, Refinitiv) and adjusted for sector and governance weighting.
- **Return Metrics** were modeled using market benchmarks and fund behavior profiles from Luxembourg (ALFI, 2022).
- **Control Variables** include fund size, sector type, and rating source bias.
- **Decile Ranking** and **Winsorization** were applied to reduce outlier effects and increase comparability.
- **All data transformations** were performed in Python using Pandas, NumPy, and Scikit-learn.

---

## 🔍 Reproducibility

Each dataset corresponds to an analysis or visualization in the Jupyter Notebooks provided under the `notebooks/` folder. Full details on the modeling logic and data transformations are included in the notebooks.

---

**Author:** Saveeza Aziz  
**Repository:** [Sustainable Real Estate Investment in Luxembourg](https://github.com/Saveeza/esg-real-estate-analysis-luxembourg)
