# Single-Cell-Multiome-Data-Analysis-and-Predictive-Modeling 

This project focuses on analyzing single-cell multiome (RNA + ATAC) data to predict peak-to-gene associations. The data comes from a hackathon challenge, with the goal of identifying associations between chromatin accessibility and gene expression. The analysis leverages dimensionality reduction, genomic distance calculation, and machine learning techniques to achieve accurate predictions.

## Key Steps:

### Data Preprocessing:
Applied PCA to reduce the high-dimensional RNA data from 30,000 to 38 columns (a 99.87% reduction) and ATAC data from 30,000 to 2,234 columns (a 92.45% reduction) while preserving 95% of the variance.

### Genomic Distance Calculation:
Calculated genomic distance using RNA data to enhance the model's ability to predict which chromatin regions regulate specific gene expressions.

### Model Development:
Implemented a hypertuned Random Forest model, using k-fold cross-validation to select optimal parameters and avoid overfitting.
Achieved a Matthews Correlation Coefficient (MCC) score of 0.7667 on the test data.

#### Domain Expertise Integration:
Collaborated with domain experts to generate meaningful features based on biological knowledge, improving the accuracy and robustness of the model.

### Objective:
The primary objective of this project was to predict whether specific peak-to-gene associations in single-cell multiome data are TRUE or FALSE, using advanced preprocessing, genomic distance measures, and machine learning techniques.

This project demonstrates the importance of combining domain knowledge with technical skills to effectively analyze and model complex biological data.
