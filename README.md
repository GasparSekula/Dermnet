# 🩺 Dermnet Clustering Project

## Project Overview
This project focuses on the clustering of the Dermnet dataset to identify patterns and group similar skin disease images. The project is a part of Introduction to Machine Learning course, a part of Data Science Engineering Bachelor Programme at Warsaw University of Technology.

##  Developers

Developed by: [@Gaspar Sekula](https://github.com/GasparSekula) & [@Nadia Serafin](https://github.com/nadias03)

## 📊 Dataset
- **Dataset:** Dermnet 
- **Source:** [Kaggle - Dermnet](https://www.kaggle.com/datasets/shubhamgoel27/dermnet/data)
- **Description:** The dataset consists of various images of 23 skin diseases, providing visual data to facilitate clustering and classification of different skin conditions. For project purposes the `train` data (consisting of over 15 000 images) was used.

## 📂 Directory Structure

### 1. 📈 EDA (Exploratory Data Analysis)
This directory contains scripts and notebooks for initial data exploration. The goal is to understand the dataset's structure, and potential issues before proceeding to more complex analyses.

### 2. ⚙️ Feature_Engineering
In this directory, you will find scripts and notebooks dedicated to creating and transforming features from the raw data. Feature engineering is crucial for improving the performance of clustering algorithms. The following methods were implemented:
- image modifications, such as: greyscale, extracted RGB channels, dilation, erosion, inverse Hough transform and thresholding,
- rotationg,
- VGG16 features.

### 3. 🧠 Models
This directory includes the clustering models developed during the project. Each model paragraph in notebook file contains the implementation details, training procedures, and evaluation metrics.  

Implemented models:
- Agglomerative Clustering (with linkage single, average, ward as well as complete),
- DBSCAN,
- Autoencoders,
- KMeans,
- BIRCH.

Models were evaluated using the following metrics:
- elbow method,
- Silhouette score,
- Dunn index,
- Davies-Bouldin index,
- Caliński-Harabasz index.

### 4. 🔍 clustering
Here, you'll find saved data frames with clusters assigned by different ok-performing models.

### 5. 📂 data
This directory holds the raw and processed data used in the project. It includes the original Dermnet dataset, cleaned datasets, and any intermediate files created during data processing.

### 6. 📊 features
In the features directory, you will find files that contain the engineered features used for clustering. This includes transformed data ready for model training and evaluation as well as VGG15 features or data frames after PCA.

### 7. Presentation
In this directory, you will find the final project presentation and 3D T-SNE visualisations of the best clustering achieved in the project.

## Validation 

The project was validated by: [@Kacper Rodziewicz](https://github.com/kacperrodziewicz8814) & [@Igor Rudolf](https://github.com/IgorRudolf )
