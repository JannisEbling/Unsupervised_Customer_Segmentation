# Customer Personality Analyis

In this project, I will analyze customer records from a grocery firm's database. Additionally, I will use an unsupervised clustering algorithm to segment the customers into clusters based on their similarities. This analysis can help the company understand the needs and behaviors of distinct customer groups, allowing them to target specific groups more effectively, grow market share, and increase profit.

The dataset together with a detailed description of all the features can be found here: https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis


## TABLE OF CONTENTS 
    
* [1. IMPORTING LIBRARIES / SET UP](#1-importing-libraries--set-up)
    
* [2. LOADING DATA](#2-loading-data)
    
* [3. DATA CLEANING](#3-data-cleaning)
    
* [4. FEATURE ENGINEERING](#4-feature-engineering)   

* [5. EDA](#5-eda)
    * [5.1 CATEGORICAL FEATURES](##51-categorical-features)
    * [5.2 NUMERICAL FEATURES/OUTLIER DETECTION](##52-numerical-featuresoutlier-detection)
    * [5.3 ANALYSIS OF PURCHASE TYPES](##53-analysis-of-purchase-types)
    * [5.4 ANALYSIS OF ACCEPTED CAMPAIGNS](##54-analysis-of-accepted-campaigns)
    * [5.5 ADDITIONAL ANALYSIS](##55-categorical-features)
    
* [6. DIMENSIONALITY REDUCTION](#6-dimensionality-reduction) 
      
* [7. CLUSTERING](#7-clustering)
    
* [8. PROFILING](#8-profiling)
    
* [9. FINDINGS AND CONCLUSION](#9-findings-and-conclusion)

## Findings
General Findings:
- Customers with only basic education spend much less than other education levels.
- Customers without children spend about 3x more than customers with children.
- Overall Customers with and without children spend an equally amount.
- Wine and meat are the goods that customer spend the most on.
- Customers with higher income tend to buy more meat while customers with low income buy more gold.
- Most Purchases are done in stores, parents use the web more while customers with no children use the catalog more frequently.
- The last campaign was the most successful.
- Campaign 3 and 4 were more successful with parents while 1 and 5 were more successful with customers without children.

Cluster Profiles:
The customers were grouped into 4 clusters with roughly the same size with the same average age of about 50 (except cluster 1).   
Description of cluster 0:  
    - This cluster contains customers that do not have children, have a high income and spend much (especially on meat).   
    - They also use the Catalog for purchases more often than other clusters.  
    - This cluster is highly acceptive of campaigns.  
    - Perform high number of Purchases with high value  
Description of cluster 1:   
    - This cluster contains customers that mostly have children, have a low income and spend less.  
    - Their buying habits are the most uniform but they are buying more gold compared to other clusters.  
    - Perform low number of Purchases with low value  
    - Average age is about 40.  
Description of cluster 2:   
    - This cluster contains customers that have children, have a medium to high income and spend a medium amount.  
    - Perform high number of Purchases with medium value  
Description of cluster 3:   
    - This cluster contains customers that have children, have a medium income and spend less.  
    - Compared to other customer groups, they buy much gold.  
    - Perform low number of Purchases with low value  

Business Recommendations:
- Use the catalog more heavily to advertise meat and the web to advertise gold.
- The next campaign should be similar to the last one since it was the most succesful.  
Elements from campaign 3 and 4 can be used in the web to target parents while elements of 1 and 5 can be used in the catalog.