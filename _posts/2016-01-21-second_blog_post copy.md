---
layout: post
title: Application of k-means clustering algorithm!
---


**My Thesis**

As part of my M.Sc. in Management Engineering from the University of Waterloo, I wrote a thesis on [“Detecting Weak Signals by Internet-Based Environmental Scanning.”](https://uwspace.uwaterloo.ca/bitstream/handle/10012/6314/Tabatabaei_Nasim.pdf?sequence=1) This was an opportunity to apply data mining, computer tools and human judgement to predict the market potential of a new product called Micro-tile which is displayed below.

![alt image](/images/micro-tile.png)
*[image was taken from christiedigital website](https://www.christiedigital.com/en-us/microtiles)*

I used both programming and human analysis to retrieve 40,000 HTML pages, analyze the data, and produce information that was relevant for the strategic marketing department of Christie Digital. 

To succeed in my thesis, I used a novel methodology which enabled me to consolidate data from a large sample of web pages and convert it into practicable information. I retrieved 40,000 HTML pages to extract weak signals and find behavior patterns. It was essential to cluster pages according to their content. I chose to use a combination of Apple script (in the pre-processing phase to convert from HTLM to txt); the k-means algorithm (with each cluster accounting for no more than 10% of the overall count) and CLUTO for the clustering function. This enabled me to produce clusters with similar content (matching key words), which were ready for human analysis.

In this post, I would specifically want to discuss the k-mean clustering algorithm. 

**Document clustering**

- Document clustering is one of the most applicable methods of text mining and used to group large amounts of documents into a number of clusters. Clustering is part of the unsupervised method which means that no training set is required. 

- For large document sets, K-means perform better (Cutting, Pederson, Karger, & Turkey, 1992; Steinbach et al., 2000). The goal of clustering algorithm is to parition documents into different groups in way that document in one group are similar to each other and not similar from other groups.

Below are the steps to perform K-means algorithm:
[source](https://www.codeproject.com/Articles/439890/Text-Documents-Clustering-using-K-Means-Algorithm)

1- Select K as the initial number of clusters
2- Assign all points to the closest centroid
3- Recompute the centroid of each cluster
4- Repeat steps 2 and 3 until the K clusters are reached.


