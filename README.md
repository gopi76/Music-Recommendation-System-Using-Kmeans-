
# Music Clustering and Recommendation System 🎵

## Overview 📊

This project involves the clustering of music data using KMeans and the implementation of a simple music recommendation system based on the clustered data. The clustering helps in organizing songs with similar characteristics, and the recommendation system suggests songs from the same cluster.

## Table of Contents 📑

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Data Exploration](#data-exploration)
- [Data Transformation](#data-transformation)
- [KMeans Clustering](#kmeans-clustering)
- [Recommendation System](#recommendation-system)


## Getting Started 🚀

### Prerequisites

Make sure you have the following dependencies installed:

- Python (>=3.6)
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Installation

1. Clone the repository:

```bash
git clone https://github.com/gopi76//Music-Recommendation-System-Using-Kmeans-.git
```

2. Run the Jupyter notebook or script to execute the music clustering and recommendation system.

## Data Exploration 📈

Explore the dataset to understand its structure and content. Check for missing values, view summary statistics, and examine the data's basic information. I have used Spotify dataset (Collected from the kaggle)



## Data Transformation 🔄
Apply data transformations, such as normalization using MinmaxScalar, to prepare the dataset for clustering.

## KMeans Clustering 🔍
- Utilize KMeans clustering to group similar songs together. Determine the optimal number of clusters using the Elbow Method.
- Then the check the quality of clustering using Silhuoette Score (range is -1 to 1).

## Recommendation System 🎧
- Implement a basic music recommendation system that suggests songs based on the clustered data.
- Create an instance for this class
- finally call the function.

## Note
- I have included all the files like Python code, Dataset, Project Report.
-  Take this reference if you need and improve with other methods like Collaborative filtering and Content based filtering.





