# MSc-project
MSc Project – Personal Wellbeing Classification in the UK

This repository contains the code and materials for my MSc Data Science project. The research explores the classification of personal wellbeing in the UK using survey data, applying a range of machine learning models and explainability methods.

**Project Overview**

Objective: Predict individual wellbeing (categorized into high and very high) based on demographic, social, and health-related factors.

Approach: Multiple supervised machine learning algorithms were tested (logistic regression, decision trees, random forests, XGBoost, MLPs, SVMs, KNNs). Model performance was compared and interpreted with explainable AI tools (e.g., SHAP).

Outcome: Insights into the most important determinants of wellbeing and the predictive potential of ML in this context.

The full methodology, results, and discussion are documented in the accompanying dissertation PDF.

**Repository Structure**

MSc_project.ipynb → Main notebook with the full pipeline and final results.

MSc project.pdf → Final MSc dissertation report (includes literature review, methodology, results, and discussion).

Other Notebooks (Robustness & Variants):

178f_noclean.ipynb

49f_cleaned.ipynb

4splitpredictor_noclean.ipynb

5f_cleaned.ipynb

'>4Threshold_noclean.ipynb'

Prototype.ipynb

These contain alternative preprocessing strategies, feature splits, and thresholding approaches used to test robustness and sensitivity of results. Their filenames indicate the main differences compared to the primary workflow in MSc_project.ipynb.
