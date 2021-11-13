

![Untitled](https://user-images.githubusercontent.com/85421407/141608035-7757add5-ca33-4622-80cd-1eaceff203ca.png)


## Overview
In this unsupervised machine learning exercise, the K-Means method was applied on a crypto currency trading data set to find statistical group classifications or groupings on the data.

## Preprocessing the Data for PCA
The first step was to clean and modify the data to get it ready for Principal Component Analysis (PCA) by scandalizing and scaling the data. 
![a]( https://github.com/serpaulus/Cryptocurrencies/blob/main/Resources/GetDummies.PNG)
![b]( https://github.com/serpaulus/Cryptocurrencies/blob/main/Resources/SdtScaler.PNG)

## Reducing Data Dimensions Using PCA
Next, features are reduced to the top three principal components 
![c]( https://github.com/serpaulus/Cryptocurrencies/blob/main/Resources/Top3PCs.PNG)

## Clustering Cryptocurrencies Using K-Means
An Elbow Curve method is applied to determine the appropriate number of clusters to the ran in the K-Means method.
![d]( https://github.com/serpaulus/Cryptocurrencies/blob/main/Resources/ElbowC.PNG)

After the K-Means is ran the data is ran the normalized results is put back together with the rest of the data in a data frame.
![e]( https://github.com/serpaulus/Cryptocurrencies/blob/main/Resources/combined_results.PNG)

## Visualizing Cryptocurrencies Results
Next, the data is placed in 3D graphical form to facilitate further visual inspection of the top three principal components
![f]( https://github.com/serpaulus/Cryptocurrencies/blob/main/Resources/3D.png)

Total Coins Mined and Total Coin Supply are graphed for visualization
![e]( https://github.com/serpaulus/Cryptocurrencies/blob/main/Resources/2.PNG)

## Conclusion
Unsupervised learning is used mainly to transform the data to create an intuitive representation for analysis or to use in another machine learning model; or cluster or determine patterns in a grouping of data, rather than to predict a classification. It can be utilized as a away to arrange data for further analysis with a supervised learning model. 
