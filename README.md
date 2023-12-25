# Data Analysis Project

## Overview

This repository contains the code and analysis for a data science project utilizing R. The project is divided into two main sections:

1. **USArrests Dataset and Hierarchical Clustering**
   - Analysis of the "USArrests" dataset using hierarchical clustering.
   - Identification of clusters and interpretation of the results.

2. **Market Segmentation**
   - Customer segmentation analysis for a large club store based on a marketing dataset.
   - Utilization of K-Means clustering for identifying similar customer groups.
   - Characterization of clusters and visualization of the results.

## Files

- **USArrests_Analysis.Rmd**: R Markdown file containing the code and documentation for the USArrests dataset analysis.
- **Market_Segmentation_Analysis.Rmd**: R Markdown file for the market segmentation analysis.
- **m_marketing_campaign.csv**: Dataset used for market segmentation analysis.

## Getting Started

1. Clone this repository to your local machine.
2. Open the R Markdown files in an R environment or an R Markdown viewer.
3. Run the code chunks sequentially for a comprehensive analysis.

## Analysis Details

### USArrests Dataset Analysis

- Hierarchical clustering using complete linkage and Euclidean distance.
- Interpretation of clusters and insights into crime rates across states.

### Market Segmentation Analysis

- Customer segmentation using K-Means clustering.
- Characterization of customer clusters based on demographics, purchasing behavior, and membership details.

## Results

- Detailed summaries and visualizations for each analysis are available in the respective R Markdown files.

## Dependencies

Ensure you have the required R packages installed by running the following commands:

```R
install.packages(c("tidyverse", "cluster", "plotly", "caret", "ggbiplot", "ggdendro", "fastDummies", "arsenal", "data.table", "dplyr", "factoextra"))


