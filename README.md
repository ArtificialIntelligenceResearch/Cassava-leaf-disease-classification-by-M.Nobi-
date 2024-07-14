<div align="center">
      <h1> <img src="http://bytesofintelligences.com/wp-content/uploads/2023/03/Exploring-AIs-Secrets-1.png" width="200px"><br/> Cassava Leaf Disease Classification Challenge Documentation </h1>
     </div>

<body>
<p align="center">
  <a href="mailto:mdmnb435@gmail.com"><img src="https://img.shields.io/badge/Email-mdmnb435%40gmail.com-blue?style=flat-square&logo=gmail"></a>
  <a href="https://github.com/nobi004"><img src="https://img.shields.io/badge/GitHub-Mahmudun Nobi-lightgrey?style=flat-square&logo=github"></a>
  <a href="https://linkedin.com/in/nobi04"><img src="https://img.shields.io/badge/LinkedIn-Mejbah%20Ahammad-blue?style=flat-square&logo=linkedin"></a>
  <a href="https://bytesofintelligences.com/"><img src="https://img.shields.io/badge/Website-Bytes%20of%20Intelligence-lightgrey?style=flat-square&logo=google-chrome"></a>
  <a href="https://www.youtube.com/@BytesOfIntelligences"><img src="https://img.shields.io/badge/YouTube-BytesofIntelligence-red?style=flat-square&logo=youtube"></a>
  <a href="https://www.researchgate.net/profile/Mejbah-Ahammad-2"><img src="https://img.shields.io/badge/ResearchGate-Mejbah%20Ahammad-blue?style=flat-square&logo=researchgate"></a>
  <br>
  <img src="https://img.shields.io/badge/Phone-%2B8801874603631-green?style=flat-square&logo=whatsapp">
  <a href="https://www.hackerrank.com/profile/ahammadmejbah"><img src="https://img.shields.io/badge/Hackerrank-ahammadmejbah-green?style=flat-square&logo=hackerrank"></a>
</p>




# Table of Contents
1. [Introduction](#introduction)
   1. [Program Overview](#program-overview)
2. [Data Source](#data-source)
   1. [Dataset Overview](#dataset-overview)
   2. [Accessing the Dataset](#accessing-the-dataset)
3. [Task Specifications](#task-specifications)
   1. [Data Management](#data-management)
      1. [Data Acquisition](#data-acquisition)
      2. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
         1. [Distribution of Classes](#distribution-of-classes)
         2. [Image Quality and Variability](#image-quality-and-variability)
         3. [Data Insights](#data-insights)
   2. [Model Engineering](#model-engineering)
      1. [Dataset Splitting](#dataset-splitting)
      2. [Model Architecture](#model-architecture)
      3. [Model Training and Validation](#model-training-and-validation)
   3. [Evaluation and Analysis](#evaluation-and-analysis)
      1. [Performance Testing](#performance-testing)
      2. [Metrics Reporting](#metrics-reporting)
   4. [Conclusion and Future Work](#conclusion-and-future-work)

## Introduction
### Program Overview
This project was done as a part of "Bytes of Intelligence: Data Science and AI Internship Program," This program provides a comprehensive learning experience in data science and AI through workshops, challenges, and mentorship. Which is an innovative platform designed to propel aspiring data scientists and AI enthusiasts into the forefront of technological advancement and real-world problem-solving.

## Data Source
### Dataset Overview
The dataset for the Cassava Leaf Disease Classification Challenge is a comprehensive collection of annotated images representing various common diseases affecting cassava plants, one of the most crucial crop resources in tropical and subtropical regions. It includes thousands of high-resolution images categorized into several disease classes, as well as a category for healthy leaves. This provides 5 folders/classes of data; some data are incorrect as inside one named folder one may find data of another folder. The dataset is highly imbalanced. Most of them are Cassava Mosaic Disease (CMD).

### Accessing the Dataset
The dataset is hosted on Kaggle, a popular platform for data science competitions and collaborative projects.

## Task Specifications
### Data Management
#### Data Acquisition
Data was downloaded from Kaggle.

#### Exploratory Data Analysis (EDA)
Conduct an in-depth EDA to understand the dataset's characteristics:
##### Distribution of Classes
There are 5 classes:
- 'Cassava Mosaic Disease (CMD)': 10,526
- 'Healthy': 2,061
- 'Cassava Green Mottle (CGM)': 1,909
- 'Cassava Brown Streak Disease (CBSD)': 1,751
- 'Cassava Bacterial Blight (CBB)': 870

##### Image Quality and Variability
Most of the images are high resolution having an 800x600 shape.

##### Data Insights
Some data are incorrect as inside one named folder one may find data of another folder. The dataset is highly imbalanced. Most of them are Cassava Mosaic Disease (CMD).

### Model Engineering
#### Dataset Splitting
#### Model Architecture
#### Model Training and Validation

### Evaluation and Analysis
#### Performance Testing
#### Metrics Reporting

### Conclusion and Future Work
