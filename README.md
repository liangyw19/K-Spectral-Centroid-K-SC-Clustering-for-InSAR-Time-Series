# K-Spectral-Centroid-K-SC-Clustering-for-InSAR-Time-Series

This repository provides a Python implementation of the K-Spectral Centroid (K-SC) clustering algorithm, which is designed to group time series based on shape similarity, regardless of magnitude or temporal shift.
Features
Shape-based time series clustering

Shift- and scale-invariant similarity measure (d_hat)

Designed for unsupervised clustering of InSAR displacement series or similar data

Returns both cluster membership and centroid templates

📌 Algorithm
The K-Spectral Centroid (K-SC) method clusters time series using a custom distance metric:

This metric allows:

Scaling invariance (via α)

Shape-based clustering

Robustness to phase shifts via eigendecomposition in centroid updates

📘 Reference
Yang, J., & Leskovec, J. (2011). Patterns of temporal variation in online media. Proceedings of the fourth ACM international conference on Web search and data mining
