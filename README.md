# Embeddings hypergraphs analysis
Analysis of the embeddings using higher-order structures, such as hypergraphs and simplicial complexes. 


# How to use this repository?
This repository illustrates a framework for studying the latent space of the embedding models. 
The framework consists of several steps:
1. we apply the embedding model to the datapoints $D_i$ with the metadata $m_i$; 
See notebook hypergraph_creation_embedding_space.ipynb
2. we apply standard ML metrics (confusion matrix, accuracy scores) to deduce scores against the embedding model producing the vectorisation of datapoints $D_i$ using the true labels of clusters $m_i$; 
See notebook hypergraph_confusion_matrix.ipynb
3. we calculate hypergraph motifs in hypergraphs HD constructed from both the embedded textual data $D_i$ and hypergraph obtained from just the metadata $m_i$. Motifs in hypergraphs are subhypergraphs structures [Battiston et al. 2020]. We also perform testing of hypergraph measures against the null models.
See notebook random_testing_arxiv_hypergraph_decades.ipynb 
[Battiston et al. 2020] F. Battiston, G. Cencetti, I. Iacopini, V. Latora, Maxime Lucas, Alice Patania, Jean-Gabriel Young, Giovanni Petri, Networks beyond pairwise interactions: Structure and dynamics, Physics Reports, Volume 874, (2020)


# Contributions

This is common work done together at Nokia Bell labs, submitted to the CNA 2024 conference with Hritika Kathuria (short paper in collaboration).
This work is in progress, do share more suggestions and your comments in issues https://github.com/Liyubov/embeddings_hypergraphs_analysis/issues 
