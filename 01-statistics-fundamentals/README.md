# Statistics & Experimental Design

**Foundation for Evidence-Based Decision Making in Life Sciences**

This module contains rigorous statistical frameworks and Python implementations designed for **Clinical Research**, **A/B Testing**, and **Bio-statistical Analysis**.

Moving beyond basic p-values, this section focuses on robust experimental design, effect size estimation, and the transition from Frequentist to Bayesian approaches in pharma-analytics.

## Core Competencies

This directory covers the following key statistical pillars:

- **Descriptive Statistics (The Foundation):**
  - Understanding data distribution *before* testing hypothesis.
  - Measures of central tendency (Mean, Median) vs. Dispersion (Standard Deviation, IQR).
  - Visualizing distributions (Histograms, Boxplots) to detect outliers in clinical data.

- **Hypothesis Testing & A/B Analysis:**
  - Rigorous frameworks for validating clinical outcomes.
  - Parametric (t-test, ANOVA) vs. Non-parametric (Mann-Whitney, Kruskal-Wallis) methods.
  - Correction for multiple comparisons (Bonferroni, FDR) in genomic data.

- **Bayesian Inference:**
  - Probabilistic programming using `PyMC`.
  - Updating prior beliefs with new evidence (essential for rare disease studies with small sample sizes).

- **Power Analysis & Sample Size:**
  - Calculating the required sample size (`n`) to detect a meaningful effect.
  - Critical for optimizing clinical trial costs and reducing failure rates.

## 📂 Notebook Index

| Notebook | Status | Description |
| :--- | :--- | :--- |
| `00_descriptive_analysis.ipynb` | 🚧 Planned | EDA, distribution checks, and outlier detection techniques. |
| `01_hypothesis_testing_framework.ipynb` | 🚧 Planned | Standard workflows for comparing treatment vs. control groups. |
| `02_bayesian_vs_frequentist.ipynb` | 🚧 Planned | A comparative analysis of statistical philosophies using medical data. |
| `03_power_analysis_clinical.ipynb` | 🚧 Planned | Simulation-based power analysis for experimental design. |

## 🛠️ Tech Stack

* **Libraries:** `scipy.stats`, `statsmodels`, `pymc`, `numpy`, `seaborn`
* **Focus:** Statistical rigor, reproducibility, and interpretability.