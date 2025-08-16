# [24234227] MEIN40430 Internship Research Project 20 <!-- omit in toc -->

**Table of Contents**
- [Association of Circulating Metabolites with Pancreatic Ductal Adenocarcinoma (PDAC) and Predictive Modelling using Machine Learning](#association-of-circulating-metabolites-with-pancreatic-ductal-adenocarcinoma-pdac-and-predictive-modelling-using-machine-learning)
- [Files](#files)
  - [1) `Analysis_PDAC_Control.ipynb`](#1-analysis_pdac_controlipynb)
  - [2) `ML_PDAC_Control.ipynb`](#2-ml_pdac_controlipynb)
  - [3) `DisVal_PDAC_Control.ipynb`](#3-disval_pdac_controlipynb)
- [Usage](#usage)
- [Contact](#contact)

## Association of Circulating Metabolites with Pancreatic Ductal Adenocarcinoma (PDAC) and Predictive Modelling using Machine Learning
This repository contains analysis and modeling workflows for investigating the association of circulating metabolites with PDAC. The work integrates statistical analysis, machine learning, and analytical frameworks to explore potential metabolite biomarkers.

## Files
### 1) `Analysis_PDAC_Control.ipynb`
**Procedures covered:**
- Data collection
- Data cleaning
- Data preprocessing
- Exploratory data analysis (EDA)
- Data imputation ($K$-Nearest Neighbors (KNN), $K$ = 10)
- Principal component analysis (PCA)
- Analysis of variance (ANOVA)
- Uniform manifold approximation and projection (UMAP)
- Normality testing
- Univariate analysis (clinical features and metabolites)
- Multivariate analysis (metabolites)

### 2) `ML_PDAC_Control.ipynb`
**Procedures covered:**
- Model training (standard framework)
- Cross-validation (CV)
- Model evaluation
- Model comparison

### 3) `DisVal_PDAC_Control.ipynb`
**Procedures covered:**
- Model training (discovery–validation framework)
- Cross-validation (CV)
- Model evaluation
- Model comparison

## Usage
Each notebook can be run independently. The workflow is organized as follows:
- `Analysis_PDAC_Control.ipynb`: Data preprocessing, exploratory and statistical analyses.
- `ML_PDAC_Control.ipynb`: Machine learning model training and evaluation (standard framework).
- `DisVal_PDAC_Control.ipynb`: Discovery–validation framework for assessing robustness.

## Contact
For questions, suggestions, or issues, contact
- Chek, Zi Yan Jane (zi.chek@ucdconnect.ie)