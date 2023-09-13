# Text Classification using Graph Neural Networks (GCNs) and Graph Attention Networks (GATs)

A comprehensive repository for text classification utilizing Graph Neural Networks (GCNs) and Graph Attention Networks (GATs). This repository contains a collection of notebooks and code implementations focusing on node classification, message passing, and text classification using graph-based techniques.
## Table of Contents

- [About the Project](#about-the-project)
  - [Motivation](#motivation)
  - [Built With](#built-with)
- [Key Notebooks](#key-notebooks)
- [Node Classification](#node-classification)
  - [Graph Convolutional Networks (GCNs)](#graph-convolutional-networks-gcns)
  - [Graph Attention Networks (GATs)](#graph-attention-networks-gats)
- [Message Passing](#message-passing)
- [Graph Neural Networks from Scratch](#graph-neural-networks-from-scratch)
- [Text Classification](#text-classification)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

---

## About The Project

### Motivation

Text classification is a vital task in Natural Language Processing (NLP) with applications ranging from sentiment analysis to content categorization. Traditional methods rely on term frequency and other statistical features. However, these methods may not capture the underlying semantics and relationships between words effectively. This project explores advanced techniques like Graph Neural Networks (GCNs) and Graph Attention Networks (GATs) to enhance text classification accuracy.

### Built With

- Python
- PyTorch
- DGL (Deep Graph Library)
- Numpy

---

## Key Notebooks

This repository includes several notebooks, each focusing on specific aspects of text classification and graph-based techniques:

1. **Node Classification with GCNs**: Node classification on the Cora dataset using Graph Convolutional Networks (GCNs).

2. **Node Classification with GATs**: Node classification using Graph Attention Networks (GATs) on the Cora dataset.

3. **Message Passing in GCNs**: A notebook explaining the concept of message passing in GCNs.

4. **GCNs from Scratch**: Implementation of Graph Convolutional Networks from scratch using Numpy.

5. **Text Classification with GCNs and GATs**: Text classification using GCNs and GATs, leveraging the graph structure of text data.

---

## Node Classification

### Graph Convolutional Networks (GCNs)

GCNs are a class of neural networks designed for graph-structured data. In node classification tasks, GCNs learn to predict labels for nodes in a graph by aggregating information from neighboring nodes. The key idea is to propagate information through the graph using a series of graph convolutional layers.

### Graph Attention Networks (GATs)

GATs are another type of graph neural network that introduces the concept of attention mechanisms to graph data. GATs adaptively weigh neighboring nodes' contributions when computing node embeddings. This leads to improved performance in tasks like node classification.

---

## Message Passing

Message passing is a fundamental concept in graph-based machine learning. In GCNs and GATs, nodes send and receive messages (information) to and from their neighbors iteratively. These messages are aggregated to update node embeddings in a way that incorporates information from the entire graph.

---

## Graph Neural Networks from Scratch

For a deeper understanding of GCNs, this notebook demonstrates how to implement them from scratch using Numpy. It covers the fundamental operations involved in message passing and node classification using a simplified GCN architecture.

---

## Text Classification

Text classification using GCNs and GATs treats words as nodes in a graph. The connections between words are established based on word co-occurrence and TF-IDF features. This approach captures semantic relationships between words and enhances the accuracy of text classification models.

---

## Results

The repository provides results and insights from experiments conducted using GCNs and GATs for text classification. You can find details on model performance, accuracy, and other relevant metrics in the notebooks.

---

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, please feel free to contribute to the project. You can also open issues for bug reports or feature requests.

---

## Acknowledgements

This project draws inspiration and knowledge from various research papers, online resources (https://github.com/berksudan/GCN-Text-Classification), and open-source contributions. We acknowledge the contributions of the NLP and graph-based machine learning communities.

Thank you for visiting my repository!
