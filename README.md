# Gas Turbine CO and NOx Emission Clustering



## Project Description
In this project it is aimed that *clustering unlabeled data* by using clustering  alorithms.  In order to obtain data, **UC Irvine Machine Learning Repository** is used. If you would like to see content of the dataset, you can check out the dataset in the **CO_NOx_Emissions.csv** file or you can visit the [**UCI ML Repository - HTRU2 webpage**](https://archive.ics.uci.edu/dataset/551/gas+turbine+co+and+nox+emission+data+set). In order to accomplish clustering operation, following Clustering ML Algorithms are used, **K-Means**, **Density-Based Spatial Clustering of Applications with Noise(DBSCAN)** and **Gaussian Mixture Model**. These ML Algorithms are evaluated by using **Silhouette Score**, **Davies-Bouldin Index** and **Calinski-Harabasz Index** as well as visually controlling the clusters with different coloring on the scatter plot for all features. As a result of these algorithms and evaluation metrics, the best performed model is **K-Means**. It should be mentioned that, Data Science Project LifeCycle is followed on this project to effectively simulate business level project handling as it can be seen from the following image. Therefore, project is formed in to 7 steps with the proceduralized contents and the step/file names are as follow; **1. Business_Understanding, 2. Data_Mining, 3. Data_Cleaning, 4. Data_Exploration_(EDA), 5. Feature_Engineering, 6. Predictive_Modelling_&_Evaluation** and **7. Data_Visualization**.

![Data_Science_LifeCycle](https://github.com/HasanUnlu09/Gas_Turbine_CO_and_NOx_Emission_Clustering/assets/133260754/e39179a5-d1b4-4fd9-9afa-ad749898e345)

## Install/Run
Each Data Science LifeCycle steps in Jupyter Notebook files can be runned one by one on your computer to see the results. If you want more generalized and compact file you can download and run **Gas_Turbine_CO_and_NOx_Emission_Clustering.ipynb** Jupyter Notebook.

## Project Outcomes
- In the below image correlations of the fewatures can be seen,
<br>![1 correlation_matrix_heatmap](https://github.com/HasanUnlu09/Gas_Turbine_CO_and_NOx_Emission_Clustering/assets/133260754/263adb99-0936-41ef-96a3-af5d2f2a554e)

---

- In the below image distributions of the feature can be seen as un-scaled and scaled, <br>
<br>![2 scalings](https://github.com/HasanUnlu09/Gas_Turbine_CO_and_NOx_Emission_Clustering/assets/133260754/d0e6b6df-fece-4f50-b1eb-c021eb97c688)

---

- In the below image, best number of cluster determination by using elbow method for K-Means algorithm is shown as well as silhouette plot that shows how well the clusters separate the data points. <br> 
<br>![3 elbow_silhouette](https://github.com/HasanUnlu09/Gas_Turbine_CO_and_NOx_Emission_Clustering/assets/133260754/dc0bb76d-ee8d-4b76-a3d9-d8487da02c6e)

---

- In the below image, clusters and their amounts are shown for each clustering algoirthms, <br>
<br>![4 clusters_and_amounts](https://github.com/HasanUnlu09/Gas_Turbine_CO_and_NOx_Emission_Clustering/assets/133260754/0c4479c0-9cfd-4ec7-8adb-e120205c3702)

---

- In the below image, evaluation metric results are shown. <br>
<br>![5  evaluations](https://github.com/HasanUnlu09/Gas_Turbine_CO_and_NOx_Emission_Clustering/assets/133260754/f465ecb7-6d48-416d-89d1-82f0086864af)

---

- In the below image, colored clusters are shown for each model on the **CO**/**NOX** feature change with respect to **TEY** feature <br>
<br>![6 evaluations_visual](https://github.com/HasanUnlu09/Gas_Turbine_CO_and_NOx_Emission_Clustering/assets/133260754/7bedb123-c321-4cf7-8010-2f7341243356)

---

Gas Turbine CO and NOx Emission Data Set. (2019). <br>
UCI Machine Learning Repository. https://doi.org/10.24432/C5WC95.

!!! If you would like to reach me out about this project you can use following e-mail address; <br>
hasan.09.unlu@gmail.com

