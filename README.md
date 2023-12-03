# Bootcamp Group N - 2023
Enterprise Datascience Bootcamp Project

# Project Title: Predictive Churn Tool - Telecom Operator

## Overview
This repository contains a series of Jupyter notebooks (Python language) that document the various stages of data analysis and predictive modeling used to understand and predict churn from the Telecom company. Each notebook focuses on a specific phase of the project, from data collection and exploration to advanced modeling techniques.

This repository is organised as follows:
- OLD: contains old files
- data: contains all the raw and processed data
- docs: contains documents used by the team members during the work
- outputs: contains files outputed during the project
- powerbi: contains the Power BI file used for exploration
- presentation: contains the presentation of the project
- notebooks (.ipynb): named with a numerical preffix translating the logical order of the work
- requirements.txt: necessary Python libraries to run the notebooks.

## Notebooks

### 1. Data Exploration (`01_data_exploration.ipynb`)
This notebook begins with data collection, including importing libraries and reading and merging datasets. It then proceeds to data exploration, providing insights into the structure of the data, patterns, and relations.

### 2. Clustering Analysis (`02_clustering_analysis.ipynb`)
The notebook's content involves applying clustering techniques (Elbow Mehtod, Dendogram, K-Means) to discover inherent groupings in the data. Functions are defined at the beginning of the file.

### 3. Feature Selection (`03_feature_selection.ipynb`)
This notebook delves into the critical process of feature selection. It identifies the most relevant features for predictive modeling, essential for enhancing model performance and ensuring interpretability.

### 4. Modelling (`04_modelling.ipynb`)
Dedicated to modeling, this notebook begins by preparing data for the modeling process. It then explores various machine learning algorithms to predict churn, evaluating their performance. Models used: Logistic Regression, Decision Tree, Random Forest, SVC, Gaussian, KNN, Gradient Boosting, MLP.

## Getting Started
Clone the repository and install the required dependencies listed in the `requirements.txt` file. Run each notebook individually to understand the different stages of the project, from initial data handling to complex modeling strategies. The notebooks already contain the outputs, run only if needed.