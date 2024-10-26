# room-6-
Classification - Student Performance Prediction
Build a system to predict if a student will be a High Achiever,
Pass, or Fail in the MI-class based on HW and exam scores
This code divides the data into two clusters based on whether the values are less than or equal to the threshold or greater than it, and then prints the clusters
data = [3.1, 2.9, 5.4, 6.2, 1.9, 5.7]
threshold = 3.5

# Cluster 1: Values less than or equal to the threshold
cluster_1 = [x for x in data if x <= threshold]

# Cluster 2: Values greater than the threshold
cluster_2 = [x for x in data if x > threshold]

print(f"Cluster 1: {cluster_1}")
print(f"Cluster 2: {cluster_2}")
