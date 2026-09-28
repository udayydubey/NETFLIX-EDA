# Netflix EDA

A portfolio-ready Exploratory Data Analysis project on the Netflix titles catalog using Python, Pandas, NumPy, and Matplotlib.

## Project Overview

This project follows a structured EDA workflow to understand the Netflix catalog, investigate data-quality issues, analyze distributions and relationships, identify potential outliers, and translate the findings into business-oriented insights.

**Workflow:** Load → Understand → Clean → Univariate Analysis → Bivariate Analysis → Outlier Analysis → Business Insights → Recommendations

## Dataset

- **Rows:** 7,787
- **Original columns:** 12
- **Movies:** 5,377 (69.05%)
- **TV Shows:** 2,410 (30.95%)
- **Most common rating:** TV-MA (2,863 titles)

The dataset file is included in the repository as `netflix_titles.csv`.

## Key Analysis

The notebook covers:

- Dataset structure, data types, and descriptive statistics
- Missing-value and duplicate analysis
- Investigation of missing `director` data by content type
- Datetime conversion and whitespace-safe date cleaning
- Type-aware transformation of the mixed `duration` field
- Movie vs TV Show distribution
- Rating distribution
- Release-year distribution
- Movie duration and TV Show season analysis
- Content additions over time
- Rating differences by content type
- Release-year comparison by content type
- Movie duration vs release year correlation
- IQR-based outlier detection and interpretation
- Country and genre metadata analysis
- Business insights and next-step recommendations

## Selected Findings

- Movies make up **69.05%** of the catalog.
- **TV-MA** is the most frequent rating.
- Title additions peaked at **2,153 in 2019** within the dataset.
- Median movie duration is **98 minutes**.
- Median TV Show length is **1 season**.
- Movie duration and release year have a **weak negative Pearson correlation (~ -0.20)**.
- Potential outliers were investigated rather than automatically removed.

## Tools & Libraries

**Python · Pandas · NumPy · Matplotlib · Jupyter Notebook**

## Repository Structure

```text
Netflix_EDA/
├── Netflix_EDA.ipynb
├── netflix_titles.csv
└── README.md
```

## How to Run

1. Clone or download the repository.
2. Keep `Netflix_EDA.ipynb` and `netflix_titles.csv` in the same folder.
3. Open the notebook in Jupyter Notebook, JupyterLab, Google Colab, or VS Code.
4. Run the cells from top to bottom.

## Notes on Interpretation

This dataset describes **catalog composition and metadata**. It does not include user-level viewing, revenue, retention, or engagement metrics. Therefore, the recommendations in this project are framed as **areas for further investigation**, not claims about Netflix's actual content performance.

## Author

**Uday Dubey**  
BBA Finance Student | Aspiring Data Analyst
