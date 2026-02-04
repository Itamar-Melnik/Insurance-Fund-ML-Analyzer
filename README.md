# Insurance Fund ML Analyzer

A comprehensive machine learning project for analyzing insurance fund performance using supervised and unsupervised learning techniques.

## 📋 Overview

This academic project demonstrates the application of machine learning algorithms to predict and analyze insurance fund performance metrics. The primary focus is on predicting Alpha levels (performance above market benchmarks) and discovering patterns in financial data through clustering techniques.

The project showcases a complete ML workflow including data preprocessing, model training, evaluation, and insight extraction within a financial analysis context.

## 🎯 Project Objectives

### Supervised Learning (Classification)
- Predict insurance fund performance levels (High/Low Alpha)
- Classify funds based on historical returns, risk metrics, and exposures
- Identify key features that drive fund performance

### Unsupervised Learning (Clustering)
- Discover natural groupings in insurance fund data
- Identify market segments and risk profiles
- Uncover patterns in financial metrics without predefined labels

## 🏗️ Project Structure

```
ML2/
├── Code/
│   ├── Classification_ML.ipynb    # Supervised learning implementation
│   └── Clustering_ML.ipynb        # Unsupervised learning implementation
├── Data/
│   └── [Insurance fund datasets]  # Financial data (returns, risks, exposures, Alpha)
├── Final_Write-up/
│   └── [Project report]           # Complete analysis and findings
├── Slide_show/
│   └── [Presentation slides]      # Project presentation materials
├── pictures/
│   └── [Visualizations]           # Generated plots and diagrams
├── README.md                      # This file
└── requirements.txt               # Python dependencies

```

## 🔧 Technology Stack

- **Language**: Python
- **Environment**: Jupyter Notebooks
- **ML Framework**: scikit-learn
- **Data Processing**: pandas, numpy
- **Visualization**: matplotlib, seaborn

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- pip package manager
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Itamar-Melnik/ML2.git
   cd ML2
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Run the notebooks**
   - Navigate to the `Code/` directory
   - Open and execute `Classification_ML.ipynb` for supervised learning analysis
   - Open and execute `Clustering_ML.ipynb` for unsupervised learning analysis

## 📊 Methodology

### Classification Pipeline
1. **Data Loading**: Import insurance fund datasets from `Data/` directory
2. **Preprocessing**: Data cleaning, normalization, and feature engineering
3. **Model Training**: Implementation of multiple algorithms:
   - Random Forest
   - Gradient Boosting
   - XGBoost
   - Support Vector Machines (SVM)
   - k-Nearest Neighbors (kNN)
4. **Evaluation**: Performance assessment using:
   - Accuracy
   - Precision & Recall
   - Confusion Matrix
   - Feature Importance Analysis

### Clustering Pipeline
1. **Data Preparation**: Scaling and preprocessing financial metrics
2. **Algorithm Implementation**:
   - K-Means Clustering (partition-based)
   - Agglomerative Clustering (hierarchical)
   - DBSCAN (density-based)
3. **Evaluation**:
   - Silhouette Score
   - Dendrograms
   - Cluster Visualization (scatter plots)

## 📈 Key Features

- **Comprehensive ML Implementation**: Both supervised and unsupervised approaches
- **Financial Context**: Real-world application to insurance fund analysis
- **Model Comparison**: Multiple algorithms tested and evaluated
- **Visualization**: Rich graphical outputs for interpretation
- **Reproducibility**: Complete environment specification via requirements.txt

## 📁 Detailed Component Description

### Code Directory
Contains two primary Jupyter notebooks:

- **Classification_ML.ipynb**: Implements supervised learning models to predict fund performance categories based on historical financial features. Includes extensive model evaluation and feature importance analysis.

- **Clustering_ML.ipynb**: Applies unsupervised learning techniques to discover natural groupings in fund data, revealing market segments and risk profiles without prior labeling.

### Data Directory
Houses the raw insurance fund datasets including:
- Historical returns
- Risk metrics
- Exposure data
- Alpha values (performance above market)

### Final_Write-up Directory
Contains the comprehensive project report with:
- Methodology description
- Results and findings
- Statistical analysis
- Conclusions and insights

### Slide_show Directory
Presentation materials including:
- Problem introduction
- Methodology overview
- Results visualization
- Key conclusions and recommendations

### Pictures Directory
Visual outputs generated during analysis:
- Feature importance charts
- Cluster visualizations
- Confusion matrices
- Performance plots

## 🎓 Academic Context

This project was developed in 2025 as an academic demonstration of machine learning applications in financial analysis. It serves as a complete example of applying ML techniques to real-world financial problems.

**Status**: Archived - This repository is no longer under active development and serves as a reference implementation.


## 🔗 Repository

[https://github.com/Itamar-Melnik/ML2](https://github.com/Itamar-Melnik/ML2)
