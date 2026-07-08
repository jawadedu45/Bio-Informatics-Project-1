# Bioinformatics Summer Project: Gene Expression & Disease Classification

## Overview
This project applies core bioinformatics and machine learning techniques to 
analyze gene/protein sequence data and gene expression profiles, with the goal 
of distinguishing normal vs. cancer samples based on expression patterns.

## Features

### 1. Sequence Analysis
- Computed GC content across multiple sequences
- Performed pairwise sequence alignment
- Visualized protein length distribution (bar chart, Matplotlib)
- Visualized GC content distribution (Seaborn)

### 2. Differential Gene Expression Analysis
- Applied independent t-tests to compare gene expression between normal 
  and cancer samples
- Identified the top 10 most differentially/highly expressed genes

### 3. Unsupervised Learning
- Performed PCA for dimensionality reduction
- Applied K-Means clustering to group samples based on expression profiles

### 4. Supervised Learning / Classification
- Built classification models (Random Forest, Logistic Regression) to 
  predict disease group (normal vs. cancer) from gene expression data
- Evaluated models using accuracy, precision, and recall

## Tools & Libraries
- Python
- BioPython
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn (PCA, K-Means, Random Forest, Logistic Regression)
- SciPy (t-test)

## Project Structure
[9:51 am, 08/07/2026] Me: ├── data/                  # raw/processed data
├── notebooks/             # analysis notebooks
├── sequence_analysis.py   # GC content, alignment
├── gene_expression.py     # t-test, top gene identification
├── clustering.py          # PCA + K-Means
├── classifier.py          # RF/Logistic Regression model
└── README.md 
## Tech stack
**Language: Python 3.x
** Libraries: Biopython, pandas, numpy, matlotlib,, seaborn, scipy
** Data sources: Uniprot, Gene Expression Datasets
name: Jawad Ahmad
