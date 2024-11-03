# Insurance Market Segmentation Analysis

[![GitHub Repository](https://img.shields.io/badge/GitHub-MarketSegmentation-blue.svg)](https://github.com/iamgopinathbehera/MarketSegmentation)

## Project Overview
This project implements advanced customer segmentation techniques for the insurance industry to provide personalized financial recommendations including savings plans, loans, and wealth management services to distinct customer groups.

![Market Segmentation Visual](https://user-images.githubusercontent.com/34673684/137431219-a5d99ac4-ce63-4435-8a49-4e19b09d0a07.png)

## Author
- **Gopinath Behera** 
- GitHub: [@iamgopinathbehera](https://github.com/iamgopinathbehera)
- Project Link: [MarketSegmentation](https://github.com/iamgopinathbehera/MarketSegmentation)

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

3. **Spectral Clustering**
   - Graph-based segmentation
   - Effective for complex geometries
   - Dimensionality reduction capabilities

4. **DBSCAN (Density-Based Spatial Clustering)**
   - Density-based clustering
   - Handles noise effectively
   - No predetermined cluster number needed

5. **Gaussian Mixture Model**
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
For questions or feedback, please:
- Open an issue in the repository
- Contact [@iamgopinathbehera](https://github.com/iamgopinathbehera)

---
