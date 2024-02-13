# analyzing_citation_networks
Analyze a citation network using graph neural networks

   - Louvain Method:
        Type: Modularity-based
        Description: A popular algorithm that optimizes modularity to find communities in a graph. It is known for its efficiency and effectiveness in detecting communities in large graphs.

   - Label Propagation Algorithm (LPA):
        Type: Semi-supervised
        Description: A simple algorithm where nodes adopt the most common label among their neighbors. It's computationally efficient and can be used for large graphs.

   - Node2Vec:
        Type: Embedding-based
        Description: An algorithm that learns embeddings for nodes by performing random walks on the graph. The learned embeddings can be used for community detection tasks.

   - GraphSAGE (Graph Sample and Aggregated Embeddings):
        Type: Graph neural network-based
        Description: A graph neural network approach that samples and aggregates information from a node's local neighborhood. It can be applied to large graphs for representation learning.

   - DeepWalk:
        Type: Random walk-based embedding
        Description: Similar to Node2Vec, DeepWalk generates embeddings by considering random walks in the graph. It is effective for capturing node similarities.

   - Walktrap Algorithm:
        Type: Hierarchical clustering
        Description: A hierarchical clustering algorithm based on random walks. It measures the similarity between nodes by the number of shared random walks.

   - Infomap Algorithm:
        Type: Flow-based
        Description: An algorithm that models the movement of information through the network to identify densely connected regions. It can uncover hierarchical community structures.

   - Community Detection with Graph Convolutional Networks (GCN):
        Type: Graph neural network-based
        Description: Utilizing graph convolutional layers to learn node representations and uncover community structures. It's effective for capturing complex relationships in large graphs.

   - SCAN (Structural Clustering Algorithm for Networks):
        Type: Structural
        Description: An algorithm that identifies clusters based on the structural roles of nodes in the network. It can uncover both overlapping and non-overlapping communities.

   - Leading Eigenvector Method:
        Type: Spectral
        Description: Based on the spectral properties of the graph's adjacency matrix. It uses the leading eigenvector to partition nodes into communities.


