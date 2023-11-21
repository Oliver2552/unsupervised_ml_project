# Unsupervised Learning Project: Wholesale Customer Analysis

## Project Overview

In this project, we applied unsupervised learning techniques to analyze a real-world dataset containing information about various products sold by a grocery store. The goal was to gain insights from the data and communicate these insights to stakeholders through appropriate visualizations and metrics.

## Dataset

The dataset used for this project is the "Wholesale Data" dataset, which includes annual spending in monetary units (m.u.) on diverse product categories by clients of a wholesale distributor. The dataset contains information about 440 instances with 8 features, including "Channel" and "Region."

- Subject Matter: Business
- Task: Unsupervised Clustering
- Feature Type: Integer
- Number of Instances, Features: 440, 8

## Project Tasks

### Part I: Exploratory Data Analysis (EDA) and Pre-processing

- Data Import: Imported the dataset into Python using Pandas.
- Data Cleaning: Checked for missing or incorrect data, handled missing values and outliers, and performed necessary data cleaning.
- Data Description: Generated summary statistics (mean, median, standard deviation) for each column.
- Data Visualization: Created various visualizations (histograms, box plots, scatter plots, heatmaps) to understand relationships and trends.
- Outlier Detection: Checked for outliers and determined their validity.
- Correlation Analysis: Calculated correlations between different variables.
- Data Transformation: Standardized or normalized variables if necessary.

### Part II: KMeans Clustering

- Applied k-means clustering to group similar products based on attributes.
- Determined the optimal number of clusters.
- Visualized clustering results using scatter plots.

### Part III: Hierarchical Clustering

- Explored hierarchical clustering to group data points in a hierarchy.
- Determined the optimal number of clusters and visualised with dendrogram.

### Part IV: Principal Component Analysis (PCA)

- Applied PCA to create insights about the structure of the data.
- Employed the explained variance ratio to see which components have the highest explained variance.
- Determined the optimal number of components based on explained variance.

## Project Results

- The optimal number of clusters as found through KMeans was 6.
- PCA process was able to take the 6 numerical columns and deduce that 2 principal components best explain the data.

## Project Dependencies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run the Code

1. Clone the repository.
2. Ensure modules list at top of .ipynb file are installed.
3. Ensure .csv file is in your working directory.
4. Run the notebook.

## Acknowledgments

- The dataset used in this project is sourced from: https://www.kaggle.com/datasets/binovi/wholesale-customers-data-set
