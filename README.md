# Iris Dataset K-Means Clustering with Hadoop

This project demonstrates the application of K-means clustering on the Iris dataset, leveraging Hadoop for scalable data processing and R for visualization and analysis. The goal is to identify and analyze clusters within the dataset using advanced data processing techniques.

## Project Overview

- **Objective:** Apply K-means clustering to the Iris dataset to identify distinct clusters and visualize the results.
- **Technologies Used:**
  - **Hadoop** for distributed data processing.
  - **R** for data preprocessing, clustering, and visualization.
  - **Apache Mahout** for scalable machine learning algorithms.
  - **Apache Hive** for data management and SQL-like querying.

## Features

- Scalable data processing with Hadoop’s HDFS and MapReduce.
- Efficient K-means clustering using Apache Mahout.
- Comprehensive ETL processes, including data cleaning and optimization.
- Visualization of clustering results with R’s ggplot2 and ggfortify.

## Getting Started

### Prerequisites

- Hadoop 3.x or later
- R (with packages: ggplot2, ggfortify)
- Apache Mahout
- Apache Hive

### Installation

1. **Set up Hadoop:**
   - Follow the [Hadoop installation guide](https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-common/SingleCluster.html) to install and configure Hadoop on your system.

2. **Install R and required packages:**
   ```r
   install.packages("ggplot2")
   install.packages("ggfortify")
