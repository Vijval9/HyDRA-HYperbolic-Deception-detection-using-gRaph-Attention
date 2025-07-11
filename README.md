# HyDRA-HYperbolic-Deception-detection-using-gRaph-Attention

This repo contains notebooks, checkpoints, and a report for our work on deception detection. We tried different approaches, and the most successful approach included using a Hyperbolic GRU for sequential data and then passing the resulting embeddings to a Graph Attention Network (GAT). After a few GAT layers, we finally use a binary classifier.
