# Seminar Outline

## 1. Motivation

Drug discovery is expensive, slow, and characterized by high failure rates. The seminar motivates graph-based machine learning as a way to exploit increasingly available digital biological and pharmacological data.

## 2. Background

### Deep learning

A short introduction to supervised and unsupervised learning, deep neural networks, and the role of learned representations.

### Graph neural networks

The seminar introduces graphs as non-Euclidean data structures and discusses graph-, node-, and edge-level prediction. It covers message passing, aggregation, graph convolution, and the need for permutation-invariant processing.

## 3. GNNs in drug discovery

### Target identification

Biological entities and diseases can be represented in heterogeneous knowledge graphs. GNNs can combine node attributes, relation types, and graph structure to predict previously unknown disease–target relationships.

**Example reviewed:** ProGENI, a probabilistic knowledge-graph approach for target identification.

### Molecular generation and optimization

Molecules are naturally represented as graphs of atoms and bonds. The seminar reviews graph-based generative methods and multi-objective molecular optimization.

**Example reviewed:** MIMOSA, which combines GNNs with MCMC-style sampling to modify molecules while balancing similarity and desired chemical properties.

## 4. Drug–drug interaction prediction

The review discusses constructing knowledge graphs from known biomedical relations and combining them with drug interaction data. GNN neighborhood aggregation can capture higher-order relationships that pairwise feature methods may miss.

**Example reviewed:** KGNN, evaluated on DrugBank and KEGG-drug data.

## 5. Drug repurposing

Drug repurposing searches for new indications for existing compounds. The seminar discusses target-based, disease-similarity, and combination approaches, including the use of knowledge graphs and molecular signatures.

**Example reviewed:** GraphRepur, which combines drug–drug links with drug-exposure gene-expression profiles using a GraphSAGE-based architecture for breast-cancer drug repurposing.

## 6. Challenges and future directions

The seminar highlights:

- over-smoothing,
- over-squashing,
- under-reaching,
- model interpretability,
- incomplete and heterogeneous biological data,
- class imbalance,
- molecular flexibility and representation challenges,
- opportunities in single-cell data and more expressive 3D graph representations.

## 7. Conclusions

The central conclusion is that graph neural networks are particularly well matched to drug-discovery problems because many of the relevant objects and interactions are inherently relational. Their usefulness spans molecular-level tasks as well as larger biomedical knowledge networks, while interpretability and biological-data quality remain important limitations.
