# Bachelor's Thesis – Analyzing the monotonicity and shape of learning curves in anomaly detection

This repository contains the PDF for my Bachelor's thesis in Computing Science at Radboud University.

The thesis investigates **non-monotonic learning curves in unsupervised anomaly detection**, exploring how increasing the amount of training data affects the performance of different anomaly detection algorithms.

The research evaluates multiple algorithms, including k-Nearest Neighbors (kNN), Isolation Forest (IF), and Minimum Covariance Determinant (MCD), across different datasets. Experiments involve repeated subsampling, performance evaluation using ROC-AUC, and statistical analysis to investigate the relationship between training set size and detection performance.

### Original Codebase and Modifications

The experiments were built upon the existing codebase from **[outlierdetection / Roel Bouman]** ([https://github.com/RoelBouman/outlierdetection]).

The original implementation was adapted and extended for the purposes of this thesis. These modifications include changes to the experimental pipeline, dataset handling, subsampling procedures, algorithm configurations, and evaluation methodology to support the investigation of learning curves in unsupervised anomaly detection.
