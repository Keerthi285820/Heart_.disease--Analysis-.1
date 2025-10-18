# ❤️ Heart Disease Prediction Using RapidMiner

This project uses RapidMiner to build a Heart Disease prediction model with preprocessed patient data.

Overview

The workflow includes:

Data Retrieval – Loading the Heart dataset.

Preprocessing:

Convert numerical attributes to polynomial features.

Convert nominal attributes to numerical (dummy coding).

Normalize numeric features (Z-transformation).

Detect and remove outliers using distance-based methods.

Feature Weighting – Apply Chi-Squared statistic for feature importance.

Data Splitting – Train/Test split (80% / 20%).

Modeling – Train a Decision Tree with pre-pruning.

Evaluation – Assess performance with accuracy, classification error, cross-entropy, and weighted precision/recall.

Results – Correlation matrix, feature weights, trained model, and performance metrics.

Tools & Techniques

RapidMiner Studio (version 10.5)

Decision Tree Classifier

Preprocessing operators: Normalization, Outlier Detection, Nominal/Numerical conversion

Attribute weighting: Chi-Squared statistic

Performance evaluation: Accuracy, Classification Error, Precision, Recall, Cross-Entropy

How to Run

Open RapidMiner Studio.

Import the XML process file (Heart_Disease_Prediction.xml).

Make sure the dataset is available in the repository path (data/heart).

Run the process to train the model and view results in the Results perspective.

Outputs

Decision Tree model

Predicted labels for test data

Performance metrics

Feature importance (Chi-Squared)

Correlation matrix

Author

Keerthi Sri
