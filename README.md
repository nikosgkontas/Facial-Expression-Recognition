# Facial-Expression-Recognition
Use exploratory data analysis and both supervised and unsupervised machine learning models to determine  how much emotional information is contained in 25 facial expression landmark measurements. 

# Data: 
We will use the Cohn-Kanade facial expression database (https://www.cs.cmu.edu/~face/database.htm). 
The dataset contains 210 instances, each one consisting of 25 measurements grouped by facial region: 
• Left eyebrow: H1, H2, H3, H4, L1 
• Right eyebrow: H5, H6, H7, H8, L2 
• Left eye: H9, H10, W1 
• Right eye: H11, H12, W2 
• Mouth: H13, H14, H15, W3, L3 
• Inter-region relationships: R1, R2, R3, R4 
Each record is labelled with an “Expression” field that can take one of seven emotion classes:  
NEUTRAL, DISGUST, SADNESS, FEAR, SURPRISE, ANGER, or JOY. 
Workflow and Activities: 
During this project, we will investigate the following activities: 
1. Data Exploration 
Inspect the raw landmark vectors to characterize value ranges, empirical distributions, inter-feature 
correlations, and outlier behavior. 
2. Feature Selection 
Quantitatively rank variables and retain a subset that maximizes information content for subsequent 
learning activities. 
3. Synthetic Sample Generation (Data Augmentation) 
Expand the training instances with statistically consistent replicas that respect the underlying data 
assumptions and do not contaminate testing partitions. 
4. Classification Methods 
Develop a suite of classification models that selected attributes to discrete emotion labels. 
5. Model Validation and Comparative Analysis 
Implement an evaluation framework (procedures and quantitative metrics) to benchmark and 
contrast models’ performances. 
6. Clustering Methods 
Apply unsupervised techniques to uncover structures and assess the alignment with known 
expression classes.

# # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # # #
Legal Disclaimer:
This repository contains code and analysis pipelines for facial expression recognition using the Cohn-Kanade (CK/CK+) dataset. 
No original images or identifiable data from the CK dataset are included or redistributed in this repository. 
All visualizations and statistical summaries (means, standard deviations, histograms, boxplots, correlation matrices, etc.) are based on aggregate data and are intended strictly for academic and research purposes.

Dataset access:
The CK/CK+ dataset used for this analysis was provided through institutional access granted by my university for academic research as part of my master's degree studies. Use of the dataset complies with all university and dataset provider terms.
You may not redistribute, publish, or sell the dataset or any derivatives that could allow reconstruction of the original data or identities.
You may share your code, analysis pipeline, and aggregate statistical results (but not the original data) for academic and non-commercial purposes.

Citation and Terms of Use
If you use or reference this repository, please cite the following papers:

Kanade, T., Cohn, J. F., & Tian, Y. (2000). Comprehensive database for facial expression analysis. Proceedings Fourth IEEE International Conference on Automatic Face and Gesture Recognition (Cat. No. PR00580), 46–53. doi:10.1109/AFGR.2000.840611

Lucey, P., Cohn, J. F., Kanade, T., Saragih, J., Ambadar, Z., & Matthews, I. (2010). The Extended Cohn-Kanade Dataset (CK+): A complete dataset for action unit and emotion-specified expression. 2010 IEEE Computer Society Conference on Computer Vision and Pattern Recognition - Workshops, 94–101. doi:10.1109/CVPRW.2010.5543262


Do’s:

Use this repository and code for academic, research, or educational purposes.

Share your analysis code and summary statistics (not the data) with proper citation.

Don’ts:

Do not upload or share the original CK/CK+ dataset or any data enabling reconstruction of individual identities.

Do not use this repository or the underlying dataset for commercial purposes.

Do not attempt to reverse-engineer or reconstruct the original dataset from any aggregate statistics shared here.
