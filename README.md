# Breast-Cancer-Detection
This repository contains the official implementation and report for the course project: *Breast Cancer Detection using Machine Learning Approach: A Comparative Study of Different Methods.*

## Quick Start
Click the badge below to run the code directly in your browser without any setup:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FarazHeydar/Breast-Cancer-Detection/blob/main/Breast_Cancer_Detection.ipynb)

## Dataset
The dataset used in this project is available at:

- [**Breast Cancer Wisconsin (Diagnostic)**](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic))
- **Description:** Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. The dataset contains 569 instances with 30 numeric features (such as radius, texture, perimeter, area, etc.) and a binary target class (Malignant vs. Benign).

## Usage
1. Open the Colab notebook linked above.
2. The dataset is automatically downloaded within the notebook. No manual download is required.
3. Run all cells to train the classifiers (Logistic Regression, SVM, Random Forest, etc.) and generate performance metrics.
4. The final cell launches a Gradio Interface (GUI). You can manually input feature values using sliders or dropdowns to get real-time predictions from your trained models.
