# Embeddings hypergraphs analysis
Analysis of the embeddings using higher-order structures, such as hypergraphs and simplicial complexes. 


# How to use this repository?
This repository illustrates a framework for studying the latent space of the embedding models. 
The framework consists of several steps:
1. we apply the embedding model to the datapoints $D_i$ with the metadata $m_i$; 
see [notebook](https://github.com/Liyubov/embeddings_hypergraphs_analysis/blob/main/notebooks/hypergraph_creation_embedding_space.ipynb)
2. we apply standard ML metrics (confusion matrix, accuracy scores) to deduce scores against the embedding model producing the vectorisation of datapoints $D_i$ using the true labels of clusters $m_i$,
see notebook hypergraph_confusion_matrix.ipynb in [this notebooks folder](https://github.com/Liyubov/embeddings_hypergraphs_analysis/blob/main/notebooks)
3. we calculate hypergraph motifs in hypergraphs HD constructed from both the embedded textual data $D_i$ and hypergraph obtained from just the metadata $m_i$. Motifs in hypergraphs are subhypergraphs structures [Battiston et al. 2020]. We also perform testing of hypergraph measures against the null models.
See notebook random_testing_arxiv_hypergraph_decades.ipynb and this [notebook](https://github.com/Liyubov/embeddings_hypergraphs_analysis/blob/main/notebooks/subhypergraph_creation.ipynb)
4. comparison with hypergraph null model (notebook in progress) [Chodrow et al. 2024] [notebook in progress](https://github.com/Liyubov/embeddings_hypergraphs_analysis/blob/main/notebooks/testing_null_models_hypergraphs.ipynb))

[Battiston et al. 2020] F. Battiston, G. Cencetti, I. Iacopini, V. Latora, Maxime Lucas, Alice Patania, Jean-Gabriel Young, Giovanni Petri, Networks beyond pairwise interactions: Structure and dynamics, Physics Reports, Volume 874, (2020)

[Chodrow et al. 2024] P. Chodrow et al. https://www.philchodrow.prof/talks/2024-netsci-satellite/#/section-5 Netsci (2024)

# Contributions

This is common work done together at Nokia Bell labs, submitted to the CNA 2024 conference with Hritika Kathuria (short paper in collaboration).
This work is in progress, do share more suggestions and your comments in issues [here](https://github.com/Liyubov/embeddings_hypergraphs_analysis/issues)
