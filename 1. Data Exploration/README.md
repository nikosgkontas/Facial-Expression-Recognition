# 1. Data Exploration
## Goal
To explore the distribution, range, relationships, and outlier characteristics of facial landmark data used for emotion recognition.

## Steps Performed
-**Data loading & cleaning**

-**Descriptive statistics** (mean, std, quartiles, min, max, etc.)

-**Visualization** (histograms, boxplots) for each feature

-**Outlier analysis** with discussion on their potential significance

-**Correlation analysis** (using heatmaps and network graphs) to reveal inter-feature dependencies

-**Preparation of the dataset** for downstream machine learning tasks

## Key Results
-**Statistical summaries** provided insight into the typical values and spread for all facial features.

-**Visualizations** helped to uncover skewness, non-normality, and the presence of outliers in the data.

-**Outlier analysis** indicated that some individuals exhibit much stronger facial expressivity, especially in the 'SURPRISE' category, but outliers are present in all classes; therefore, outliers were retained for integrity.

-**Correlation heatmaps**  highlighted which facial features are most strongly related, suggesting possible redundancy or multicollinearity in certain measurements.

-**Data is now ready** for feature selection, synthetic data generation, and machine learning analysis.


**Technical Note:**
If this notebook does not render correctly on GitHub, use [nbviewer.org](https://nbviewer.org/github/nikosgkontas/Facial-Expression-Recognition/blob/main/1.%20Data%20Exploration/1%20DATA%20EXPLORATION.ipynb).

**Data Ethics:**
No original or identifiable data is included in this repository. Only aggregate summaries and synthetic data are used.
