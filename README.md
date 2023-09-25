# Customer Complaint Topic Modeling

This project focuses on conducting topic modeling on a customer complaint dataset using the Latent Dirichlet Allocation (LDA) algorithm implemented with Gensim. The goal is to uncover meaningful topics within the dataset and provide insightful visualizations using pyLDAvis.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Topic Modeling with LDA](#topic-modeling-with-lda)
- [Visualization with pyLDAvis](#visualization-with-pyldavis)
- [License](#license)

## Introduction
Customer complaints are valuable sources of feedback for businesses, and understanding the main topics within these complaints can be crucial for improving customer satisfaction and product/service quality. This project employs the LDA algorithm to perform topic modeling on a customer complaint dataset, providing a structured way to identify key topics and patterns in the complaints.

## Dataset
The dataset used for this project contains a collection of customer complaints. It is preprocessed in this notebook [`data_preparing.ipynb`](https://github.com/chukbert/topicModeling/blob/master/data_preparing.ipynb) and ready for topic modeling. You can find the dataset [here](https://data.world/cfpb/consumer-complaints).

## Topic Modeling with LDA
Latent Dirichlet Allocation (LDA) is a popular algorithm for topic modeling. It works by identifying latent topics within a collection of documents and assigning each document a distribution over these topics. In this project, we use Gensim, a powerful library for topic modeling, to implement LDA.

## Visualization with pyLDAvis
To gain a better understanding of the topics identified by LDA, we use pyLDAvis for visualization. This interactive visualization tool allows you to explore the topics and their relationships in a user-friendly manner.

## License
This project is licensed under the [MIT License](LICENSE).

---
