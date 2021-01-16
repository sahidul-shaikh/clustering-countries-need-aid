# Clustering countries which are in direst need of aid

## Problem statement 

HELP International is an international humanitarian NGO that is committed to fighting poverty and providing the people of backward countries with basic amenities and relief during the time of disasters and natural calamities. It runs a lot of operational projects from time to time along with advocacy drives to raise awareness as well as for funding purposes.

After the recent funding programmes, they have been able to raise around $ 10 million. Now the CEO of the NGO needs to decide how to use this money strategically and effectively. The significant issues that come while making this decision are mostly related to choosing the countries that are in the direst need of aid. 

And this is where we come in as a data analyst. Our job is to categorise the countries using some socio-economic and health factors that determine the overall development of the country. Then we need to suggest the countries which the CEO needs to focus on the most.  The datasets containing those socio-economic factors. 

## Objectives

Our main task is to cluster the countries by the factors mentioned above and then present the solution and recommendations to the CEO using a PPT.  The following approach is followed :

- Perform PCA on the dataset and obtain the new dataset with the Principal Components. Choose the appropriate number of components k. We need to perform our clustering activity on this new dataset, i.e. the PCA modified dataset with the k components.
- **Outlier Analysis:** We must perform the Outlier Analysis on the dataset, before or after performing PCA, as per our choice. However, we do have the flexibility of not removing the outliers if it suits the business needs or a lot of countries are getting removed. Hence, all we need to do is find the outliers in the dataset, and then choose whether to keep them or remove them depending on the results we get.
- Try both K-means and Hierarchical clustering(both single and complete linkage) on this dataset to create the clusters. [Note that both the methods may not produce identical results and we might have to choose one of them for the final list of countries.]
- Analyse the clusters and identify the ones which are in dire need of aid. We can analyse the clusters by comparing how these three variables - [gdpp, child_mort and income] vary for each cluster of countries to recognise and differentiate the clusters of developed countries from the clusters of under-developed countries. Note that we perform clustering on the PCA modified dataset and the clusters that are formed are being analysed now using the original variables to identify the countries which we finally want to select.
- Also, we need to perform visualisations on the clusters that have been formed.  We can do this by choosing the first two Principal Components (on the X-Y axes) and plotting a scatter plot of all the countries and differentiating the clusters. We should also do the same visualisation using any two of the original variables (like gdpp, child_mort, etc.) on the X-Y axes as well. We can also choose other types of plots like boxplots, etc. 
The final list of countries depends on the number of components that we choose and the number of clusters that we finally form. Also, both K-means and Hierarchical may give different results. Hence, there might be some subjectivity in the final number of countries that we think should be reported back to the CEO. Here, make sure that we report back at least 5 countries which are in direst need of aid from the analysis work that we perform.

## Dataset
The dataset and data dictionary are uploaded. 

