# Iris Dataset --- Exploratory Data Analysis

## Project Overview

This project explores the Iris dataset to examine the numerical
characteristics of its three species and identify measurements that show
the clearest differences between them.

## Dataset

-   **Observations:** 150 rows initially; 147 rows after removing 3
    duplicate records.
-   **Features:** Sepal length, sepal width, petal length, and petal
    width.
-   **Target:** Iris species.

## Analysis

The exploratory analysis included: - Initial data inspection and
descriptive statistics. - Duplicate-record detection and removal. -
Missing-value assessment and species-wise median imputation where
needed. - Distribution analysis using histograms and KDE curves. -
Species-specific boxplots for the four numerical features. - Spearman
correlation heatmap. - Kruskal--Wallis H tests to compare each numerical
feature across the three species.

## Key Findings

-   The dataset contained 150 observations initially. After removing 3
    duplicate records, 147 observations remained.
-   The Kruskal--Wallis tests indicated statistically significant
    differences among the three species for all four numerical features
    (p-values below 0.05).
-   `PetalWidthCm` had the largest reported H-statistic (approximately
    128), showing the strongest distributional differences among the
    species in this comparison.

## Tools & Libraries

-   Python
-   pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   SciPy

## Files

-   `Iris_EDA.ipynb` --- Jupyter Notebook containing the analysis, code,
    visualizations, and results.
