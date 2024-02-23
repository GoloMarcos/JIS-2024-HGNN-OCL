# Unsupervised Heterogeneous Graph Neural Networks for One-Class Tasks: Exploring Early Fusion Operators

- Marcos Paulo Silva Gôlo (ICMC/USP) | marcosgolo@usp.br
- Marcelo Isaias de Moraes Junior (ICMC/USP) | marcelo.junior@usp.br
- Rudinei Goularte (UFMS) | rudinei@icmc.usp.br
- Ricardo Marcacini (ICMC/USP) | ricardo.marcacini@icmc.usp.br

# Citing:

Under review at JIS - Journal on Interactive Systems

# Abstract

Heterogeneous graphs are an essential structure that models real-world data through different types of nodes and relationships between them, including multimodality, which comprises different types of data such as text, image, and audio. Graph Neural Networks (GNNs) are a prominent graph representation learning method that takes advantage of the graph structure and its attributes that, when applied to the multimodal heterogeneous graph, learn a unique semantic space for the different modalities. Consequently, it allows multimodal fusion through simple operators such as sum, average, or multiplication, generating unified representations considering the supplementary and complementarity relationships between the modalities. In multimodal heterogeneous graphs, the labeling process tends to be even more costly due to the multiple modalities analyzed, in addition to the imbalance of classes inherent to some applications. In order to overcome these problems in applications that comprise a class of interest, One-Class Learning (OCL) is used. Given the lack of studies on multimodal early fusion in heterogeneous graphs for OCL tasks, we proposed a method based on unsupervised GNN for heterogeneous graphs and evaluated different early fusion operators. In this paper, we extend another work by evaluating the behavior of the main GNN convolutions in the method. We highlight that using operators such as subtraction, multiplication, and average were the best early fusion operators. In addition, GNN layers that do not use an attention mechanism performed better. In this way, we argue for heterogeneous graph neural networks in multimodal using early fusion simple operators instead of well-often-used concatenation and less complex convolutions.

# Datasets

- **Fake News** : https://github.com/GoloMarcos/FKTC.git

- **Recommender Systems** : https://github.com/GoloMarcos/One-Class-Recommendation-GNNLinkPrediciton.git

- **Music** : : https://github.com/AngeloMendes/Unsupervised-Heterogeneous-GraphNeural-Network-for-Hit-Song-Prediction-through-One-Class-Learning.git

- **Event** : https://github.com/joaopedromattos/GNEE


| Datasets | Nodes | Edges | Nodes with initial features 
| :---: | :---: | :---: | :---: |
| Fake News | 10348 | 318411 | 2064 |
| Rec. Sys. | 8774 | 30471 | 2397 | 
| Music | 2125 | 5243 | 1529 | 
| Event | 579 | 803 | 96 | 

# Proposal
![Proposal](/images/pipeline.jpg)

# Results
![Results](/images/results.png)

# TSNE on FCN for GCN
![TSNE](/images/tsne_gcn.ppg)

# TSNE on FCN for GAT
![TSNE](/images/tsne_gat.ppg)

# TSNE on FCN for GraphSAGE
![TSNE](/images/tsne_sage.ppg)
