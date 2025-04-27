# Cancer Diagnosis Prediction

## Overview
This project focuses on building a Machine Learning model to predict breast cancer diagnoses  whether a tumor is benign or malignant based on clinical features extracted from digitized images of breast masses.

### Dataset
- Source: UCI Machine Learning Repository : https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)
- Instances: 569 samples
- Features:
  - radius (mean of distances from center to points on the perimeter)
  - texture (standard deviation of gray-scale values)
  - perimeter
  - area
  - smoothness (local variation in radius lengths)
  - compactness (perimeter^2 / area - 1.0)
  - concavity (severity of concave portions of the contour)
  - concave points (number of concave portions of the contour)
  - symmetry
  - fractal dimension ("coastline approximation" - 1)

- Target Classes:
  - Malignant (Cancerous)
  - Benign (Non-cancerous)

## Results
- Achieved over 98% accuracy in classification.
- Maintained a low false negative rate — a critical factor in healthcare diagnostics.
- Built a scalable AI pipeline capable of generalizing well to unseen data.
