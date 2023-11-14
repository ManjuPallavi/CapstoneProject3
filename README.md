# CapstoneProject3

##  **Introduction:**

Instacart is an American technology company that operates as a same-day grocery delivery and pick up service in the U.S. and Canada. Customers shop for groceries through the Instacart mobile app or Instacart.com from various retailer partners. The order is shopped and delivered by an Instacart personal shopper.

## **Objectives:**

Analyze the anonymized data of 3 million grocery orders from more than 200,000 Instacart users open sourced by Instacart
Find out hidden association between products for better cross-selling and upselling
Perform customer segmentation for targeted marketing and anticipate customer behavior
Build a Machine Learning model to predict which previously purchased product will be in user’s next order

## **Project Organization :**

Data files can be downloaded from the Kaggle and copy them in the Data folder. [https://www.kaggle.com/competitions/instacart-market-basket-analysis/data]

* [Data Wrangling](/notebook/DataAnalysis.ipynb) :  to read all data files and merge the datasent and store in separate file for further analysis
* [Data Analysis](/notebook/DataWrangling.ipynb) :   to analyze the given data set , relationship between different columns
* [Feature Building](/notebook/FeatureBuilding.ipynb) : to build features on the dataset that can be used to train data model . This file also contains model based on decision Tree ,  
                    Ransodam Forest Classifier Algorithm
* [KmeansCluster](/notebook/KMeansCluster.ipynb) : to build Customer segmentation based on derived features 
* [XGBoost Algo](/notebook/XGBoostAlgo.ipynb)  : to build the ML model based on XGBoost algorithm
* [Final_report](/notebook/final_report.ipynb) :  to get list of product recommendation for a given using saved XGBoost Model
