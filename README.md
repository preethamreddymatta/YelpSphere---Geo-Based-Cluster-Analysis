# Yelp Business Geospatial Clustering & Exploratory Analysis
## Overview

This project performs a large-scale exploratory and clustering analysis on 150,000+ Yelp businesses to uncover geographic, behavioral, and category-driven patterns across metropolitan regions. Using advanced clustering algorithms such as K-Means, DBSCAN, and HDBSCAN, the analysis identifies dense business hubs, detects outlier regions, and evaluates how geography influences customer engagement and business behavior.

### The project combines:

Exploratory Data Analysis (EDA)
Geospatial feature engineering
Density-based clustering
Dimensionality reduction
Interactive geographic visualization

The findings demonstrate that business clustering on Yelp is primarily driven by geographic density, with dense metropolitan areas forming highly structured patterns compared to sparse rural regions.

## Problem Statement

#### How can we analyze a large-scale Yelp dataset to:

Understand how businesses naturally cluster geographically
Identify major metropolitan business hubs
Analyze rating and review behavior across regions
Detect sparse/outlier business regions
Compare clustering algorithms for real-world geographic segmentation
Visualize geographic business density and engagement patterns effectively

### Dataset

The project uses the Yelp business dataset containing:

150,000+ businesses
600+ cities
Geographic coordinates (latitude & longitude)
Ratings and review counts
Business categories
Location metadata

### Key Features
Exploratory Data Analysis (EDA)
Rating distribution analysis
Review count analysis
Category frequency analysis
Business hotspot detection
Geographic density exploration
Geospatial Feature Engineering
Coordinate cleaning and validation
Latitude/longitude transformation to radians
Haversine distance computation for geographic clustering

### Clustering Algorithms

K-Means Clustering
Standardized feature scaling
Elbow Method optimization
Silhouette score evaluation

### DBSCAN
Density-based spatial clustering
Noise/outlier detection
Haversine distance metric support

### HDBSCAN
Hierarchical density clustering
Variable-density cluster handling
Automatic noise labeling
Dimensionality Reduction
UMAP embeddings for spatial manifold visualization
Cluster structure visualization in lower dimensions

### Visualization
Interactive Folium maps
Hexbin density heatmaps
Cluster scatterplots
UMAP cluster projections

| Category                 | Tools & Libraries           |
| ------------------------ | --------------------------- |
| Programming              | Python                      |
| Data Processing          | Pandas, NumPy               |
| Visualization            | Matplotlib, Seaborn, Folium |
| Machine Learning         | Scikit-learn, HDBSCAN       |
| Dimensionality Reduction | UMAP                        |
| Geospatial Analysis      | Haversine, Geopy            |

### Clustering Evaluation Metrics

The following metrics were used to evaluate clustering quality:

Silhouette Score
Davies–Bouldin Index
Calinski–Harabasz Score
Elbow Method
Noise Ratio Analysis

## Key Insights

Identified 18 major metropolitan clusters across the Yelp dataset.
Detected 953 geographic outlier locations using density-based clustering.
Found that geographic density explains over 90% of clustering structure.
DBSCAN and HDBSCAN significantly outperformed K-Means for irregular city boundaries and sparse regions.
Dense urban areas exhibited substantially higher review activity and engagement patterns.
