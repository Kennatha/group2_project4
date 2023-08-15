# Consumer Analysis
# Overview
In this model, we will predict and analyze consumer spending scores based on a set of consumer demographics. The data used contains demographics such as annual income, age, profession, gender, work experience, family size and spending score. The spending score is a value assigned by the organization for each customer an indicator of spending probablity. Consumers with the highest spending score would be the ideal consumer for this organization. We will identify which factors could be used to predict a high spending score, or in other words, an ideal customer. In the data cleaning process, we found outliers in the age and work experience data. We filtered the data to only view the age range of 25 - 65, and work experience years that are greater than zero. To compare the consumer spending score with average annual income, we began with unsupervised learning, and created 4 clusters of data based on the results of the elbow curve. There are 4 clear clusters generated, but there was no strong indication of a relationship between spending score and average annual income. To further analyze, we introduced a third dimension for comparison. By adding age as a Z axis and creating 5 clusters, there is more segration of the clusters in annual income and spending score indicating that age is a stronger determining factor of spending score. (Data source: https://www.kaggle.com/datasets/datascientistanna/customers-dataset/code?select=Customers.csv)

# Results
The analysis of the 4 clusters are:

Cluster 0:

Cluster 1:

Cluster 2:

Cluster 3:

# Conclusion
