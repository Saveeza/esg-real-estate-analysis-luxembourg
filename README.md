![Banner](visuals/ESG%20Real%20Estate%20Banner.png)

![MIT License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Project%20Status-Complete-blue)
![Last Updated](https://img.shields.io/badge/Last%20Updated-July%202025-lightgrey)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16146240.svg)](https://doi.org/10.5281/zenodo.16146240)

# 🏢 Sustainable Real Estate Investment in Luxembourg  
### ESG Scoring vs Market Returns — Full-Scale Data Science & Policy Integration

This repository presents a **deep technical analysis** of how ESG scores relate to financial performance in Luxembourg’s real estate funds — a rare public investigation linking **EU Taxonomy**, **SFDR disclosures**, and actual market returns in a critical green finance sector.

> 💡 This is the **first open-source study** to model ESG-return relationships using fund-level data across multiple ESG pillars and property sectors in Luxembourg — Europe’s ESG fund capital.

---

## 💡 Why This Project Matters

The built environment is responsible for nearly **40% of global carbon emissions**, making real estate a **top priority** under the EU Green Deal, SFDR, and Taxonomy frameworks. Yet investors, regulators, and the public face a **critical blind spot**:  
🧩 *Do ESG scores actually align with financial outcomes?*

This project offers a rare, open-source answer — backed by full data science methods — and provides:

- ✅ **First Quantitative Linkage**: A public, fund-level analysis connecting ESG scores, sub-pillar data, and actual market returns in Luxembourg — Europe’s ESG fund capital.  
- ⚠️ **Policy-Relevant Evidence**: Our findings address Luxembourg’s real regulatory concerns, including CSSF’s 2024 SFDR sanction and its 2023 ESG disclosure review.  
- 📊 **Return Risk Insights**: Identifies financial underperformance in ESG deciles and mismatches between regulatory scoring and real fund outcomes.  
- 🏛️ **Compliance Signaling**: Equips stakeholders with a forward-looking map of where disclosure gaps may breach SFDR or greenwashing guidelines.  
- 🔍 **Data Science Depth**: All models are reproducible, diagnostics-validated, and grounded in econometric best practices — far beyond typical ESG commentary.  
- 🌐 **Global Relevance**: Though rooted in Luxembourg, this analysis informs fund behavior across the EU — especially as the European Supervisory Authorities step up enforcement.

> 🌱 Whether you're an asset manager, regulator, or researcher, this project delivers **real analytics for real sustainability accountability.**

---

## 🌟 Key Contributions

- 📌 First public dataset linking ESG scores and market returns for Luxembourg real estate funds  
- 🧮 Deep-dive regression and subscore analysis, validated with residual diagnostics  
- 🏛️ Policy-relevant findings aligned with SFDR enforcement and CSSF thematic reviews  
- 🧠 Full data pipeline: cleaning, modeling, visualization, reporting  
- 📢 100% reproducible, open-source, and ready for policy, academic, or investment use

---

## 🏛️ Regulatory Context in Luxembourg

This project directly supports regulatory insights from Luxembourg’s evolving sustainable finance framework:

- **CSSF Sanctions**: In 2024, the CSSF issued its first SFDR-related enforcement action — a €56,500 sanction — signaling active supervision of sustainability claims.  
- **Thematic Reviews**: CSSF’s 2023 thematic review exposed major inconsistencies in ESG disclosures and methodologies used by investment funds.  
- **Legal Framework**: Luxembourg’s **Law of 25 February 2022** implements SFDR and the EU Taxonomy locally, assigning supervisory authority to CSSF and CAA.  
- **Policy Gap Mapping**: This project identifies how ESG scores (used for regulatory reporting) do or don’t translate into actual return performance, highlighting risk for greenwashing.

This makes the project not only an academic exercise, but a **live map of regulatory exposure** in ESG scoring practices.

---

## 🎯 Target Audience

- CSSF, ESMA, EBA, and other supervisory bodies  
- Sustainable real estate fund managers  
- Climate-aligned institutional investors  
- Researchers in ESG finance and econometrics  
- Policymakers involved in EU Green Deal enforcement  
- Think tanks, advocacy groups, and financial journalists  

---

## 📦 Repository Structure

```
├── data/             # ESG, return, subscore, and sector-level datasets
├── notebooks/        # Fully structured Jupyter notebooks with analysis
├── visuals/          # Final output visuals: plots, charts, and performance tables
├── reports/          # Final article, policy summaries, references
├── requirements.txt  # Python dependencies
├── LICENSE           # Open license for academic/research reuse
├── .gitignore        # Ignore temp & dev files
└── README.md         # Project overview (this file)
```

---

## 📊 Notebooks Overview

| Notebook | Description |
|----------|-------------|
| `01_ESG_vs_Return_Regression.ipynb` | OLS regression: ESG score vs annual return (%) |
| `02_Decile_Analysis.ipynb`          | ESG decile boxplot + return bar chart |
| `03_Leaders_vs_Laggards.ipynb`      | ESG quartile comparison: return gap |
| `04_Subscore_Correlation.ipynb`     | Environmental, Social, Governance pillars vs return |
| `05_Sector_Performance.ipynb`       | ESG and return averages by property sector |
| `06_Regression_Diagnostics.ipynb`   | Residual scatter plot to check model assumptions |

Each notebook includes markdown explanations and polished visual output.

---

## ✅ Project Status

| Component                      | Status       |
|-------------------------------|--------------|
| ESG dataset compiled           | ✅ Complete  |
| Return dataset merged          | ✅ Complete  |
| Subscore/sector layers added   | ✅ Complete  |
| All visuals generated (8 total)| ✅ Complete  |
| Jupyter notebooks written      | ✅ Complete  |
| Final article uploaded         | ✅ Complete  |
| README.md and licensing        | ✅ Complete  |

✅ This project is **fully complete** and production-ready.

---

## 📊 Visuals (8 Total)

All figures are in the `/visuals/` folder and directly support the published analysis:

1. `esg_vs_return_ols.png` — **OLS regression figure**: ESG score vs annual return  
2. `esg_vs_return_scatter.png` — Regression: ESG vs Annual Return  
3. `esg_decile_boxplot.png` — Return distribution by ESG decile  
4. `esg_decile_bar_chart.png` — Average return by decile  
5. `decile_return_gap_table.png` — Decile gap summary table  
6. `quartile_comparison_bar.png` — Leaders vs laggards return gap  
7. `esg_subscore_correlation.png` — ESG pillar vs return correlation  
8. `sector_performance_bars.png` — Sectoral ESG and return side-by-side  
9. `regression_residual_plot.png` — Fitted vs residuals for model validation

---

## 📘 Reports

Located in `/reports/`:

- `Sustainable_Real_Estate_Luxembourg.pdf` — Full research article +  APA references for data, policy, and academic sources
- `policy_document_summary.md` — Summary of Green Deal, IFEU, national plans  

---

## 🧰 Tools & Skills Used

- **Languages & Frameworks**: Python, Pandas, NumPy, Seaborn, Matplotlib, Statsmodels, Jupyter  
- **Modeling Techniques**: OLS regression, quantile binning, residual diagnostics, correlation mapping  
- **Data Engineering**: ESG fund data cleaning, score normalization, subscore integration  
- **Visualization**: Bar charts, scatter plots, residual plots, boxplots, return gap tables  
- **Policy & Domain Expertise**: SFDR, EU Taxonomy, CSSF regulatory review, ESG reporting frameworks  
- **Reproducibility & Version Control**: Git, Zenodo DOI, markdown documentation, open licensing


---

## 🧬 Methodology Summary

- **OLS Regression** — ESG score vs return
- **Quantile Binning** — Decile & quartile analysis
- **Subscore Analysis** — Independent correlation of E, S, and G with returns
- **Sector Aggregation** — Mean ESG and return by sector
- **Residual Validation** — Scatterplot diagnostics to test model fit

Methodologically, this work combines **financial econometrics**, **ESG signal analysis**, and **policy overlay**.

---

## 🛠️ Reproducibility

```bash
git clone https://github.com/Saveeza/esg-real-estate-analysis-luxembourg.git
cd esg-real-estate-analysis-luxembourg
pip install -r requirements.txt
jupyter notebook
```

All outputs are reproducible with the included datasets and code.

---

## 📚 How to Cite

Aziz, S. (2025). *Saveeza/esg-real-estate-analysis-luxembourg: Initial Zenodo Release — ESG Scoring vs Market Returns (Luxembourg) (v1.0)*. Zenodo. https://doi.org/10.5281/zenodo.16146240


---

## 📖 License

This repository is licensed under the [MIT License](LICENSE).  
Free to use, adapt, cite, or remix — attribution appreciated.

---

## 👤 About the Author

**Saveeza Aziz** is a data analyst with a focus on sustainable finance and applied policy evaluation. Her work combines technical expertise in ESG scoring, EU Taxonomy alignment, and investment modeling to support real-world financial decisions. She has contributed to projects on the real estate market in Luxembourg, the green transport transition in Germany, and pension fund decarbonization in the Netherlands. Her approach bridges regulatory frameworks and market performance through data-driven insights that are both practical and impact-focused.

---
