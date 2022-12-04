# Clustering Analysis: Implementation of K-Modes clustering algorithm in Python

For this project, my client provided a database with a number of profiles which had a different set of profiles. The objective was:

- Clustering the profiles with similar accesses

- Selecting base profiles for each cluster

- For each profile that is not a base profile, get a list of all the accesses that differ with the base profile of its own cluster

To complete this I used a machine learning algorithm called "K-Modes" similar to the well-known k-means but used for categorical data, that is, non-numerical data like text, characteristics, etc. All the cleaning and data wrnagling was done with pandas and the graphs with matplotlib.
