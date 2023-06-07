# Text-Mining-Project
Task 1: Finding similar items
- Randomly selected 1000 abstracts from the whole dataset. Used pairwise Jaccard similarities, MinHash and LSH (vectorized versions) to find similar items.

- Compared the performance in time and the results for k-shingles = 3, 5 and 10, for the three methods and similarity thresholds s=0.1 and 0.2.

- Compared the results obtained for MinHash and LSH for different similarity thresholds s = 0.1, 0.2 and 0.25 and 50, 100 and 200 hashing functions.

Task 2: Mining information from Text Data
- Using the whole anthologies abstract dataset. Extracted a list of the authors and editors per publication and create baskets and performed a search of similar items 
 
- Used the naïve, A-priori and PCY algorithms to find the frequent pair of items. Compared the results for supports s=10, 50, 100.

- For the PCY algorithm, created up to 5 compact hash tables and compared the time of execution for 1,2,3,4 and 5 tables.

- Found the final list of k-frequent items (k-tuples) for k=3 and 4.

Task 3: creating Graphs and social networks
 - Used two different similarity thresholds to create an unweighted network from the obtained similar pairs for each threshold.

- From the basket list of authors/editors, using A-Priori or PCY, created a weighted network using the support threshold as weight.

- Found the communities for the networks as final steps for task 1 and 2.
