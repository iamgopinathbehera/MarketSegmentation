# Market Segmentation in Insurance

### Objective  :

This case requires to develop a customer segmentation to give recommendations like saving plans, loans, wealth management, etc. on target customer groups.
<img align="center" src="https://user-images.githubusercontent.com/34673684/137431219-a5d99ac4-ce63-4435-8a49-4e19b09d0a07.png" alt="image">

### Data Description : 

The sample Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.
### Data :  
Use the below link to download the Data Set:[here](https://github.com/iamgopinathbehera/MarketSegmentation/blob/main/Clustered_Customer_Data.csv) 

### Algorithms used : 

In this dataset i've used five clustering algorithm to perform segmentation.These algorithms are given below.
- [K-Means Clustering](https://en.wikipedia.org/wiki/K-means_clustering)
- [Agglomerative Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html)
- [Spectral Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.SpectralClustering.html)
- [DBSCAN Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html)
- [GaussianMixture Model based clustering](https://en.wikipedia.org/wiki/Mixture_model)
- 
### Final Model  :
We have created a Streamlit Application based on this clustering technique, where we are taking the customer details & identifying which cluster the custoemr belongs to.



# Insurance Market Segmentation Analysis

## Project Overview
This project implements advanced customer segmentation techniques for the insurance industry to provide personalized financial recommendations including savings plans, loans, and wealth management services to distinct customer groups.

![Market Segmentation Visual](https://user-images.githubusercontent.com/34673684/137431219-a5d99ac4-ce63-4435-8a49-4e19b09d0a07.png)

## Business Objectives
- Identify distinct customer segments based on behavioral patterns
- Develop targeted financial product recommendations
- Optimize marketing strategies for different customer groups
- Improve customer engagement and satisfaction
- Enable data-driven decision making for product development

## Dataset Description

### Overview

- **Sample Size**: ~9,000 active credit card holders
- **Time Period**: 6 months of transaction data
- **Scope**: 18 behavioral variables at customer level
- **Source**: [Download Dataset](https://github.com/iamgopinathbehera/MarketSegmentation/blob/main/Clustered_Customer_Data.csv)

### Key Features
- Demographic information
- Transaction patterns
- Credit utilization metrics
- Payment behavior
- Account activity indicators

## Methodology
The project employs multiple clustering algorithms to ensure robust segmentation:

### Implemented Algorithms

1. **K-Means Clustering**
   - Partition-based clustering
   - Optimal for spherical clusters
   - Fast and memory-efficient

2. **Agglomerative Clustering**
   
   - Hierarchical clustering approach
   - Bottom-up merging strategy
   - Flexible distance metrics

4. **Spectral Clustering**
   
   - Graph-based segmentation
   - Effective for complex geometries
   - Dimensionality reduction capabilities

6. **DBSCAN (Density-Based Spatial Clustering)**
   
   - Density-based clustering
   - Handles noise effectively
   - No predetermined cluster number needed

8. **Gaussian Mixture Model**
   - Probabilistic clustering
   - Soft assignment capabilities
   - Flexible cluster shapes

## Implementation

### Interactive Application

We've developed a Streamlit application that:
- Accepts customer information as input
- Processes data using trained models
- Identifies customer segment membership
- Provides segment-specific insights

### Technical Stack
- Python
- Scikit-learn
- Streamlit
- Pandas
- NumPy

## Getting Started
1. Clone the repository:
```bash
git clone https://github.com/iamgopinathbehera/MarketSegmentation.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Streamlit app:
```bash
streamlit run app.py
```

## Results and Insights
- Identified distinct customer segments
- Developed targeted marketing strategies
- Created personalized product recommendations
- Improved customer engagement metrics



## Contact
For questions or feedback, please open an issue in the repository.

#   M a r k e t S e g m e n t a t i o n 
 
 
