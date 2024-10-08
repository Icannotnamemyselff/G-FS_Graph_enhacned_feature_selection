# G-FS: Graph Representation Learning enhanced Semi-supervised Feature Selection

Feature selection is a key step in machine learning by eliminating features that are not related to the modeling target to create reliable and interpretable models. By exploring the potential complex correlations among features of unlabeled data, recently introduced self-supervision-enhanced feature selection greatly reduces the reliance on the labeled samples. However, they are generally based on the autoencoder with sample-wise self-supervision, which can hardly exploit the relations among samples. 
To address this limitation, this paper proposes Graph representation learning enhanced Semi-supervised Feature Selection (G-FS) which performs feature selection based on the discovery and exploitation of the non-Euclidean relations among features and samples by translating unlabeled “plain” tabular data into a bipartite graph. A self-supervised edge prediction task is designed to distill rich information on the graph into low-dimensional embeddings, which remove redundant features and noise. Guided by the condensed graph representation, we propose a batch-attention feature weight generation mechanism that generates more robust weights according to batch-based selection patterns rather than individual samples. The results show that G-FS achieves significant performance edges in fourteen datasets compared to twelve state-of-the-art baselines, including two recent self-supervised baselines. 

