# K-Means Clustering — PaySim Fraud Analysis

## Objective
Discover hidden fraud patterns in 6.3M financial transactions 
using unsupervised learning — without any labels.

## Approach
- Feature scaling with StandardScaler
- Elbow Method to find optimal K
- K-Means clustering with K=3

## Key Finding
| Cluster | Transactions | Fraud Rate |
|---------|-------------|------------|
| Cluster 0 | 60.1L | 0.13% |
| Cluster 1 | 3.1L | 0.03% |
| Cluster 2 | 37K | **0.94%** |

Cluster 2 showed 7x higher fraud rate — discovered without 
any labels. Fraud transactions have a distinct financial 
fingerprint.

## Tech Stack
Python, Scikit-learn, K-Means, Pandas, Matplotlib

## Dataset
[PaySim on Kaggle](https://www.kaggle.com/datasets/ealaxi/paysim1)
