# Unsupervised-Myopia-Modeling
The purpose of this project is to analyze data on children's ocular health, specifically data related to Myopia or 'nearsightedness,' using unsupervised machine learning to see if distinct clusters can be identified in the data. First, the data is read in from this [CSV file](https://github.com/wawilson810/Unsupervised-Myopia-Modeling/blob/main/Resources/myopia.csv) and scaled using the StandardScaler method of sklearn. Then the data has its dimensionality reduced using Principal Component Analysis and t-SNE before. The output is then graphed in a scatter plot as shown below to determine if there are any easily identifiable clusters.

![Output Scatter Plot](https://user-images.githubusercontent.com/101532717/196510455-02c106c6-f6ea-4cab-8a14-cba2e93492f0.png)

Then we performed cluster analysis using the k-means method on the data that been processed with PCA. By looking at graph of the inertias of the different clustering models in the range of 1-10 clusters that is shown below, we can see that the inertia starts to level off when there are 3 clusters. However the inertia is still rather high so any clusters will be spread out. 

![download](https://user-images.githubusercontent.com/101532717/196511440-262f7741-f730-408a-9172-25e34b8a1cff.png)
