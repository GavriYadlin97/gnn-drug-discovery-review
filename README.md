# Graph Neural Networks for Drug Discovery and Repurposing

A literature-review seminar on how **Graph Neural Networks (GNNs)** can model molecular and biomedical relationships across the drug-development pipeline.

The work was completed for the Open University of Israel AI seminar course and surveys both the foundations of graph learning and concrete applications in pharmaceutical research.

## Scope

The seminar focuses on four major application areas:

- **Target identification** — learning disease–gene / biological-entity relationships from heterogeneous knowledge graphs.
- **Molecular generation and optimization** — representing molecules as graphs and modifying structures while optimizing multiple drug-like properties.
- **Drug–drug interaction prediction** — combining drug interaction matrices with biomedical knowledge graphs.
- **Drug repurposing** — identifying new therapeutic indications for existing drugs using interaction networks and molecular / gene-expression information.

## GNN concepts covered

- Graph-, node-, and edge-level prediction
- Message passing and neighborhood aggregation
- Graph convolution
- Heterogeneous knowledge graphs
- GraphSAGE and inductive learning
- Link prediction
- Molecular graph generation
- Focal loss for severe class imbalance

## Representative methods reviewed

| Method | Application | Main idea |
| --- | --- | --- |
| **ProGENI** | Target identification | Probabilistic biomedical knowledge graph for prioritizing disease-related targets |
| **MIMOSA** | Molecular optimization | GNN-guided multi-constraint molecular editing with MCMC sampling |
| **KGNN** | Drug–drug interactions | Knowledge-graph neighborhood aggregation for interaction prediction |
| **GraphRepur** | Drug repurposing | GraphSAGE over drug links combined with drug-exposure gene-expression signatures |

## Key themes

### Why graphs fit drug discovery

Biomedical systems are naturally relational. Molecules can be represented through atoms and bonds, while larger biomedical systems can be represented through drugs, genes, diseases, proteins, and their interactions. GNNs allow learned representations to incorporate both entity features and graph topology.

### Knowledge graphs

A recurring theme is the use of heterogeneous knowledge graphs to combine multiple biological information sources. These representations support tasks such as discovering missing links, prioritizing candidate targets, and predicting previously unknown drug interactions.

### Molecular optimization

The seminar reviews methods that generate or edit molecular graphs while balancing several objectives, such as similarity to an existing compound and improvements in desired drug properties.

### Drug repurposing

Drug repurposing can shorten development by searching for new indications for existing compounds. Graph-based models can combine known drug relationships, molecular signatures, and disease-related information to rank candidate treatments.

## Challenges and open directions

The review discusses several important limitations of graph learning in biomedicine:

- **Over-smoothing** — node representations can become too similar as message passing gets deeper.
- **Over-squashing** — information from large neighborhoods can be compressed through limited-dimensional representations.
- **Under-reaching** — shallow models may fail to incorporate sufficiently distant information.
- **Interpretability** — biomedical predictions are difficult to trust when the reasoning of the model is opaque.
- **Complex biological data** — biological measurements can be heterogeneous, incomplete, imbalanced, noisy, and stochastic.

## Seminar document

The original seminar is a **35-page report in Hebrew** titled *Graph Neural Networks for Drug Discovery and Repurposing* (2024). It contains the full technical discussion, equations, figures, examples, and bibliography.

## Skills demonstrated

`Graph Neural Networks` · `Deep Learning` · `Knowledge Graphs` · `Drug Discovery` · `Drug Repurposing` · `Scientific Literature Review` · `Biomedical AI`
