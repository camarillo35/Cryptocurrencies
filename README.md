# Cryptocurrencies

The purpose of this project will be to help Martha create a report on cryptocurrencies to present to the board

Creating a grouping / classification system for all the available cryptocurrencies using unsupervised ML with the scikit PCA and K-means libraries.

Dataset was initially cleaned to exclude currencies that are not traded and not currently mined. Final, cleaned dataset includes 532 currencies.

This challenge consists of four technical analysis deliverables:

Deliverable 1 - Preprocessing the Data for PCA
Deliverable 2 - Reducing Data Dimensions Using PCA
Deliverable 3 - Clustering Cryptocurrencies Using K-means
Deliverable 4 - Visualizing Cryptocurrencies Results



<img width="745" alt="M18_1" src="https://user-images.githubusercontent.com/92793248/155633753-f85c9f22-8a0a-4cb9-847e-9ad2d0c57c2d.png">





<img width="896" alt="M18_2" src="https://user-images.githubusercontent.com/92793248/155633774-fbaaa400-24c7-4895-a1c1-c07341057bc6.png">





<img width="734" alt="M18_3" src="https://user-images.githubusercontent.com/92793248/155633786-9e211998-37f5-4c70-b9c8-190bccba4c3d.png">




Preprocessing of data required removal of nulls, filter for traderable currencies, removal of unneeded columns and conversion of text data to numeric data. There are 532 tradable cryptocurrencies. The best k-mean value for clustering cryptocurrencies determined on a Elbow Curve chart was 4. Though fun to rotate the 3D chart, the 2D chart proved more readible for this data set.
