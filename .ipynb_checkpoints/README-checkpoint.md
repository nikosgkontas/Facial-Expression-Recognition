# Facial-Expression-Recognition

This project explores how much emotional information is encoded in 25 facial landmark measurements using exploratory data analysis and both supervised and unsupervised machine learning models.

## Data
Synthetic data mimicking the Cohn-Kanade facial expression dataset ([source](https://www.cs.cmu.edu/~face/database.htm)) is used for all modeling, training, validation, and testing. **No original images or identifiable records are included or redistributed.**

The original dataset contains 210 instances, each with 25 facial landmark measurements, grouped by region:

- **Left eyebrow:** H1, H2, H3, H4, L1  
- **Right eyebrow:** H5, H6, H7, H8, L2  
- **Left eye:** H9, H10, W1  
- **Right eye:** H11, H12, W2  
- **Mouth:** H13, H14, H15, W3, L3  
- **Inter-region:** R1, R2, R3, R4  

Each record has an “Expression” label: NEUTRAL, DISGUST, SADNESS, FEAR, SURPRISE, ANGER, or JOY.

## Workflow

1. **Data Exploration:** Inspect ranges, empirical distributions, inter-feature correlations, and outliers.
2. **Feature Selection:** Rank and retain variables that maximize information for learning.
3. **Synthetic Sample Generation:** Expand data with statistically consistent replicas (no original data is shared).
4. **Classification:** Train supervised models to map features to emotion classes.
5. **Validation & Benchmarking:** Evaluate models with appropriate metrics.
6. **Clustering:** Apply unsupervised methods to discover natural groupings in the data.

## Legal Disclaimer

- This repository contains only code and aggregate statistics (means, standard deviations, histograms, boxplots, correlation matrices, etc.).
- **No original images or individual-level data are included or distributed.**
- All analyses are for academic and research purposes only.
- The dataset was accessed through institutional permission for my master's studies.  
- Redistribution, publication, or sale of the dataset or derivatives that allow reconstruction is prohibited.
- You may share code and analysis pipelines, but not original data, for academic/non-commercial purposes.

## Citations

- T. Kanade, J. F. Cohn and Yingli Tian, "Comprehensive database for facial expression analysis," *Proc. IEEE Int. Conf. Automatic Face and Gesture Recognition*, 2000, pp. 46-53, doi:10.1109/AFGR.2000.840611.
- P. Lucey et al., "The Extended Cohn-Kanade Dataset (CK+): A complete dataset for action unit and emotion-specified expression," *2010 IEEE CVPR Workshops*, pp. 94-101, doi:10.1109/CVPRW.2010.5543262.


Do not use this repository or the underlying dataset for commercial purposes.

Do not attempt to reverse-engineer or reconstruct the original dataset from any aggregate statistics shared here.
