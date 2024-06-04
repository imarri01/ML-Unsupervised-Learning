
# 🧠 Unsupervised Learning - Project

Welcome to the **Unsupervised Learning - Project** notebook! This project explores various unsupervised machine learning techniques applied to the "Wholesale Data" dataset, which includes annual spending on diverse product categories by clients of a wholesale distributor.

[![Kaggle Dataset](https://img.shields.io/badge/Kaggle-Dataset-blue.svg)](https://www.kaggle.com/datasets/binovi/wholesale-customers-data-set)

---

## 📋 Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Conclusions](#conclusions)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## 📘 Introduction

Unsupervised learning involves training models on unlabeled data to discover hidden patterns and structures. This project focuses on implementing and analyzing different unsupervised learning techniques using the "Wholesale Data" dataset.

---

## 🌟 Project Overview

This notebook covers the following unsupervised learning techniques:

1. **Exploratory Data Analysis (EDA) & Pre-processing**
   - Data Import and Cleaning
   - Data Description and Visualization
   - Outlier Detection
   - Correlation Analysis
   - Data Transformation
   - Feature Selection

2. **K-Means Clustering**
   - Pre-processing the dataset
   - Determining the optimal number of clusters using the elbow method
   - Performing K-Means Clustering

3. **Hierarchical Clustering**
   - Pre-processing the dataset
   - Performing Hierarchical Clustering
   - Determining the optimal number of clusters using dendrograms

4. **Principal Component Analysis (PCA)**
   - Performing PCA to identify underlying structures
   - Analyzing which feature combinations best describe customers

---

## 🚀 Getting Started

Follow these instructions to set up the project on your local machine for development and testing.

### Prerequisites

Ensure you have the following installed:
- Python 3.6 or higher
- `pip` package manager
- Jupyter Notebook

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/imarri01/ML-Unsupervised-Learning.git
    cd ML-Unsupervised-Learning
    ```

2. **Create a Virtual Environment**:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install Required Packages**:
    ```bash
    pip install -r requirements.txt
    ```

---

## 🛠️ Usage

To explore the notebook, ensure your virtual environment is activated, then launch Jupyter Notebook:

```bash
jupyter notebook
```

Navigate to the `Unsupervised Learning - Project.ipynb` file and open it to start exploring the project.

---

## 📊 Results

The notebook includes detailed visualizations and analysis for each unsupervised learning technique. You will find plots and graphs that illustrate the performance and insights gained from the models. The results section of the notebook provides an in-depth interpretation of these visualizations.

### Key Findings

1. **K-Means Clustering**: Identified three customer segments, aiding in targeted marketing.
2. **Hierarchical Clustering**: Confirmed three main customer segments, validating K-Means results.
3. **PCA**: Reduced data complexity while retaining most variance, simplifying data visualization.
4. **EDA**: Highlighted key spending trends and correlations, informing marketing strategies.

---

## 🤝 Contributing

We welcome contributions to enhance this project! To contribute, please follow these steps:

1. **Fork the Repository**.
2. **Create a New Branch**:
    ```bash
    git checkout -b feature-branch-name
    ```
3. **Make Your Changes and Commit Them**:
    ```bash
    git commit -m 'Add some feature'
    ```
4. **Push to the Branch**:
    ```bash
    git push origin feature-branch-name
    ```
5. **Create a Pull Request**.

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 💼 Acknowledgements

- [Scikit-Learn](https://scikit-learn.org/stable/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

For any questions or suggestions, please feel free to reach out.

---
