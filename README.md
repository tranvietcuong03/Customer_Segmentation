# Marketing Campaign to Customer Segmentations 
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/matplotlib-%233A4CAA.svg?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/seaborn-%2302B6D6.svg?style=for-the-badge&logo=seaborn&logoColor=white)

## About

In this project, I will be performing an unsupervised clustering of data on the customer's records from database. 
Customer segmentation is the practice of separating customers into groups that reflect similarities among customers in each cluster. 
I will divide customers into segments to optimize the significance of each customer to the business.
To modify products according to distinct needs and behaviours of the customers, also help the business to cater to the concerns of different types of customers.

## Dataset
Dataset: [Download here](https://github.com/tranvietcuong03/Customer_Segmentation/blob/master/marketing_campaign.csv) <br>

## Data preprocessing

* Clean data: Handle null values and outlier
* Categorical feature: Modify values and convert to numerical features
* Alternative columns: Add some column to clarify information of customers

## Setup
- Requirement: Ensure you have Python 3 and required libraries installed (pandas, numpy, sklearn, matplotlib, seaborn).
- Installation:
  * Pandas
  ```sh
  pip install pandas
  ```
  There are similar to numpy, scikit-learn, matplotlib and seaborn to install
  
## Model
I used **KMean** and **PCA** to cluster the customer segmentation

## Evaluation
* After traning model by Kmean I have a visualization of clusters
  ![...](https://github.com/tranvietcuong03/Customer_Segmentation/blob/master/PCA.png)

* Distribution the Clusters based on Income and Spent:
![...](https://github.com/tranvietcuong03/Customer_Segmentation/blob/master/Income_Spent.png)

* Detail Clusters on Spent:
![...](https://github.com/tranvietcuong03/Customer_Segmentation/blob/master/Cluster_Spent.png).

From statistics, this can be used in planing better marketing stategies.
