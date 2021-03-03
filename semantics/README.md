# Semantics

## Overview
We include different notebooks to provide the student with practical means to explore some of the modern methods used to represent meaning in NLP and NLU. We follow an incremental approach in accordance with the contents of session 5 of the course, focused on semantics.

## Notebooks

### Word embeddings
Our [first notebook](https://github.com/hybridnlp/tutorial/blob/master/01_capturing_word_embeddings.ipynb) is focused on learning word embeddings from a training corpus, assigning a vector to each word, following the distributional representational theory. We will see how to use one of the many algorithms available nowadays to this purpose and illustrate some of the properties that such word vector representations have, allowing for basic semantic operations, like checking word similarity, relatedness and analogy based on the cosine distance between the vectors that represent such words in the embeddings space.

### Knowledge Graph Embeddings
Word embeddings aim at capturing the meaning of words based on large corpora; however, there are decades of experience and approaches that have tried to capture meaning by structuring knowledge into semantic networks, ontologies and graphs. Examples of such resources include lexical knowledge graphs like WordNet. The [second notebook](https://github.com/hybridnlp/tutorial/blob/master/02_knowledge_graph_embeddings.ipynb) shows how to leverage such resources and calculate representations of their content, like lemmas, senses, and the relations between them, in a common vector space.

### Building a vecsigrafo – generating hybrid representations from text corpora and knowledge graphs.
Knowledge graph embedding algorithms can capture structured knowledge about concepts and relations in a graph as embeddings in a vector space, which then can be used in downstream tasks. However, this type of approaches can only capture the knowledge that is explicitly represented in the graph, hence lacking in recall and domain coverage. Here we include tow examples of algorithms that address this limitation through the combination of information from both unstructured text corpora and structured knowledge graphs. The [third notebook](https://github.com/hybridnlp/tutorial/blob/master/03_vecsigrafo.ipynb) shows how to combine document corpora and knowledge graphs to learn richer representations that better capture the meaning of words.

## Resources
This notebooks are part of the tutorial [Hybrid Techniques for Hybrid Natural Language Processing](http://hybridnlp.expertsystemlab.com/tutorial/). The complete lessons, materials and resources of the tutorial can be found here [here](http://hybridnlp.expertsystemlab.com/tutorial/index.php/sample-page/). If you prefer, you can find all the Jupyter notebooks of the different lessons in the tutorial [repo](https://github.com/hybridnlp/tutorial).

## Bibliography
The following book is focused on the concepts illustrated here:

**_Jose Manuel Gomez-Perez, Ronald Denaux and Andres Garcia-silva. 2020. A Practical Guide to Hybrid Natural Language Processing - Combining Neural Models and Knowledge Graphs for NLP. https://doi.org/10.1007/978-3-030-44830-1_**

@book{10.1007/978-3-030-44830-1,  
author = {Gomez-Perez, Jose Manuel and Denaux, Ronald and Garcia-Silva, Andres},  
title = {A Practical Guide to Hybrid Natural Language Processing - Combining Neural Models and Knowledge Graphs for NLP.},  
year = {2020},  
isbn = {978-3-030-44830-1},  
publisher = {Springer Publishing Company, Incorporated},  
edition = {1st},  
abstract = {This book provides readers with a practical guide to the principles of hybrid approaches to natural language processing (NLP) involving a combination of neural methods and knowledge graphs. To this end, it first introduces the main building blocks and then describes how they can be integrated to support the effective implementation of real-world NLP applications. To illustrate the ideas described, the book also includes a comprehensive set of experiments and exercises involving different algorithms over a selection of domains and corpora in various NLP tasks. Throughout, the authors show how to leverage complementary representations stemming from the analysis of unstructured text corpora as well as the entities and relations described explicitly in a knowledge graph, how to integrate such representations, and how to use the resulting features to effectively solve NLP tasks in a range of domains. In addition, the book offers access to executable code with examples, exercises and real-world applications in key domains, like disinformation analysis and machine reading comprehension of scientific literature. All the examples and exercises proposed in the book are available as executable Jupyter notebooks in a GitHub repository. They are all ready to be run on Google Colaboratory or, if preferred, in a local environment. A valuable resource for anyone interested in the interplay between neural and knowledge-based approaches to NLP, this book is a useful guide for readers with a background in structured knowledge representations as well as those whose main approach to AI is fundamentally based on logic. Further, it will appeal to those whose main background is in the areas of machine and deep learning who are looking for ways to leverage structured knowledge bases to optimize results along the NLP downstream.}  
}
