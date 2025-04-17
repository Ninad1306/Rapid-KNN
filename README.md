# Rapid k-NN

## Sampling-Based Approach: 
Traditional k-NN suffers from high computational costs due to its need to compare each query point with all training samples. We introduced a sampling-based approach that reduces the dataset size while preserving essential class distribution.

## Efficient Indexing: 
To further improve performance, we leveraged approximate nearest neighbor (ANN) indexing using PyNNDescent, which significantly accelerates neighbor searches compared to brute-force methods.

## Lower Computational Complexity: 
By reducing the number of comparisons through sampling and using fast indexing techniques, our approach achieves lower computational complexity while maintaining classification accuracy.

## Scalability for Large Datasets: 
Unlike traditional k-NN, which becomes impractical for large datasets, our method scales efficiently, making it suitable for real-world applications involving millions of data points.
