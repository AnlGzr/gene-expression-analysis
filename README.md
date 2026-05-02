# Gene Expression Analysis and Systems-Level Exploration

## Overview
This project applies basic bioinformatics and data analysis methods to breast cancer diagnostic data. The goal is to compare malignant and benign samples, identify features that differ between them, and explore relationships between biological variables.

This project was created as part of my preparation for further study in systems biology and bioinformatics.

## Objectives
- Compare malignant and benign biological samples
- Identify the features with the strongest differences between groups
- Explore relationships between features using correlation analysis
- Apply basic clustering to observe patterns in the dataset

## Dataset
The project uses the built-in Breast Cancer Wisconsin dataset from `scikit-learn`.

Each row represents a sample, and each column represents a numerical biological feature. The target labels classify samples as malignant or benign.

## Methods
The analysis includes:

1. Loading and preparing the dataset
2. Separating samples into malignant and benign groups
3. Calculating mean feature differences between groups
4. Visualizing the most differentiating features
5. Performing correlation analysis on selected features
6. Applying KMeans clustering to explore sample grouping

## Tools and Libraries
- Python
- pandas
- matplotlib
- seaborn
- scikit-learn

## Key Results
- Identified the top features that differ between malignant and benign samples
- Visualized feature differences using a bar chart
- Explored relationships between key features using a correlation heatmap
- Applied clustering to examine whether samples show natural grouping patterns

## Relevance
This project demonstrates my interest in applying computational methods to biological data. It reflects foundational skills relevant to systems biology and bioinformatics, including data processing, statistical comparison, visualization, and pattern exploration.

## Future Improvements
- Apply additional statistical testing
- Compare clustering results with true diagnostic labels
- Explore dimensionality reduction methods such as PCA
- Extend the workflow to gene expression datasets## How to Run

## How to Run
1. Open the notebook `analysis.ipynb`
2. Run all cells in order
3. Review outputs and visualizations

The project was developed using Python with standard data analysis libraries.