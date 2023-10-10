# Behavioral-Segmentation
In summary, this project delves into the segmentation of customers based on their shopping behavior using clustering algorithms. The initial data exploratory analysis provided valuable insights into customer characteristics and relationships between variables, with a focus on gender, age, annual income, and spending score.

![image](https://github.com/aidapouradam4/Behavioral-Segmentation/assets/103252922/5818b344-9db5-4911-aa0a-7651dbbd4f71)
![image](https://github.com/aidapouradam4/Behavioral-Segmentation/assets/103252922/2dc27d3d-54e6-4171-84fa-084f6e97fd36)
![image](https://github.com/aidapouradam4/Behavioral-Segmentation/assets/103252922/c78dec40-b16a-4e41-ab3c-54eefaa203c3)
![image](https://github.com/aidapouradam4/Behavioral-Segmentation/assets/103252922/2b08f5ea-721a-45fb-b1b5-ba8fa5d3a898)
![image](https://github.com/aidapouradam4/Behavioral-Segmentation/assets/103252922/ffd28773-1476-42e7-af36-26a187e9e080)
![image](https://github.com/aidapouradam4/Behavioral-Segmentation/assets/103252922/e8e9cf57-e9df-4878-a44c-064415b0d311)

The paired analysis revealed the potential for clustering based on "Annual Income" and "Spending Score." Interestingly, gender did not seem to significantly influence this relationship. Subsequently, we selected the K-means and DBSCAN clustering algorithms, taking into consideration their suitability for the task.

![image](https://github.com/aidapouradam4/Behavioral-Segmentation/assets/103252922/5aae9b6b-c0fa-4bb6-b042-86b90b5f55fc)
![image](https://github.com/aidapouradam4/Behavioral-Segmentation/assets/103252922/0209824c-ccb1-4a0d-8ee9-2696058d3ccf)


Evaluation of algorithm performance revealed that K-means outperformed DBSCAN, achieving a silhouette score of 0.55 and effectively clustering the dataset into five distinct groups. In contrast, DBSCAN grouped all data points into a single cluster, indicating its limitations for this specific dataset.

![image](https://github.com/aidapouradam4/Behavioral-Segmentation/assets/103252922/c93f0c55-c44b-453b-8c4a-584e71ce35d8)
![image](https://github.com/aidapouradam4/Behavioral-Segmentation/assets/103252922/2e2ddfde-7387-45cc-b1d5-94522c629f82)


