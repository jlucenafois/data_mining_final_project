# Healthcare Network Analysis in Venezuela: Insurance Claims Study

## Project Overview
This study analyzes the effectiveness of a network-based healthcare delivery system in Venezuela through insurance claims data. We examine whether implementing an in-network healthcare system delivers value to both patients and the insurance company.

## Dataset
- **Time Period**: September 2023 - June 2024
- **Size**: 840,000 insurance claims
- **Key Features**: 
  - Client information (age, plan tier, contract holder)
  - Claim details (status, USD amount, procedure, specialty)
  - Healthcare provider data (clinic ID, type, admission/discharge dates)

## Analysis Goals

1. **Cost & Volume Analysis**
   - Does the insurance network lower prices for patients?
   - Does the network drive higher claims volume for the insurance company?
   - Cost comparison between in-network and out-of-network providers
   - Claims volume trends pre/post network implementation

2. **Procedure Diversity Analysis**
   - Does the network increase procedure diversity?
   - Analysis of non-urgent vs urgent procedures
   - Changes in procedure mix after network implementation
   - Accessibility impact on elective procedures

3. **Business Strategy Evaluation**
   - Network effectiveness as a business strategy
   - Cost-benefit analysis of network implementation
   - Provider participation and tier structure assessment
   - Market competitiveness analysis

## Methods
- Feature Engineering
- K-means Clustering
- Multivariate Linear Regression
- Time Series Analysis
- Statistical Hypothesis Testing

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
