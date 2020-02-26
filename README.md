# optimal-clusters
This program and method enables you to find the optimal number of clusters for any dataset before performing the actual clustering.
It generates a plot of a range of k-values vs corresponding inertia )or within cluster sum-of-squares. 
To determine the optimal number of clusters from the plot, we need to determine the point after which the inertia start decreasing in a linear fashion. This point is known as the 'elbow point'. Therefore, this method is know as elbow method of identifying the optimal number of clusters. 
To find optimal clusters, run the function by giving a dataframe as an input.
Set the range of k-values for which the graph will be plotted. One of these k values will be the optimal number of clusters. 
