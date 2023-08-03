# Spotify-Song-Genre-Classification
Spotify data from Kaggle to perform an analysis and examine the accuracy of unsupervised and supervised machine learning models in making predictions. The process of dimensionality reduction of data using PCA is described in the study. K-means clustering is used to classify the genre of the songs, and hierarchical clustering techniques are used to enhance and identify the subgenre of the songs.

## Software
R Studio

## Packages
`library(tidyverse)`
`library(ISLR2)`
`library(caret)`
## Getting Started
Selecting the Genre Rap, Emo, Dark Trap.

## Methods
- Principal Component Analysis
- Hirearchial clustering
    - Linkage Methods
- K - Means
- Random Forest
## Key Findings
- The potential of using reduced dimensionality data using PCA, by retaining most of the data with 8 principal components having 90% of the information.
- The primary and the secondary principal components (PC1 and PC2) capture most of the variance of the attribute’s “energy”, “loudness”, and “danceability”.
- The logistic regression model has performed with an accuracy of 77% with a computational time of 0.036 sec and
- The random forest model has performed with an accuracy of 83% with a computational time of 0.15 sec.
- Additionally,a K-Means-based unsupervised machine learning algorithm that finds patterns and clusters songs based on features with a 65.7% accuracy and a computational time of 0.04 seconds was developed. To provide more precise genre predictions, the genre hierarchies option was considered in the classification model.

## Results
he evolution of songs over time, artists have the freedom to explore different features. Therefore, it is challenging for supervised machine learning algorithms as music trends constantly change over time, whereas unsupervised models constantly learn and update the models from the data. The “time period” is also one of the important features that must be incorporated to see the evolution of the genre that we want to classify. In addition, when addressing such classification problems, incorporating additional audio features like lyrics, rhythm, and timbre becomes crucial.

## References
- Adhithya Raut. Spotify-dataset-predict. Retrieved May 27th, 2023, from https://www.kaggle.com/code/adityaraut/spotify-dataset-predict/input
- James, G., Witten, D., Hastie, T., & Tibshirani, R. (n.d.). An Introduction to Statistical Learning. Retrieved Jun 1st, 2023, from https://www.statlearning.com/
  
