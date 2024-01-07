# K-Means-Clustering
The K-Means clustering algorithm is an unsuperivised learning algorithm that classifies data points into clusters.
It classifies the points by randomly place a K amount of centroids in the graph of data.
A line is drawn to connect the centroids and a perpendicular line is drawn to that line to determine what centroid each point is closest to.
The centroid is repositioned by being place in the center of the points that were close to that centroid versus the other centroids.
The center is calculated by the mean of the coordiantes/feature values.
New lines are drawn to each centroid and perpendicular to those lines to re-establish the closest centroid to each point.
This process is repeated until the centroid does not move when calculating the new center of the points that were closest to it.
The final result is classified points based on their closest centroid.