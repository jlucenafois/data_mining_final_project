# Healthcare Network Analysis in Venezuela: Insurance Claims Study

## Project Overview
This study analyzes the effectiveness of a network-based healthcare delivery system in Venezuela through insurance claims data. We examine the impact of in-network versus out-of-network healthcare providers on costs, acceptance rates, and processing efficiency.

## Dataset
- **Time Period**: September 2023 - June 2024
- **Size**: 840,000 insurance claims
- **Key Features**: 
  - Client information (age, plan tier, contract holder)
  - Claim details (status, USD amount, procedure, specialty)
  - Healthcare provider data (clinic ID, type, admission/discharge dates)

## Analysis Goals
1. **Primary Analysis**
   - Cost comparison between in-network and out-of-network providers
   - Claim acceptance rate analysis by network status
   - Procedure-specific cost variations

2. **Secondary Analysis**
   - Claims processing efficiency
   - Treatment pattern variations
   - Geographic distribution analysis

## Methods
- Feature Engineering
- K-means Clustering
- Multivariate Linear Regression
- Statistical Analysis

## Setup

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Download Data

```bash
git lfs pull
```


## Team
- Logan Kinajil-Moran (Paper/Presentation)
- Juan Lucena Fois (Preprocessing/Feature Engineering)
- Ashton Prescott (Visualization/Paper)
- Krish Jain (Clustering/Classification)
