# Semantics

## Overview
We include different notebooks to provide the student with practical means to explore some of the modern methods used to represent meaning in NLP and NLU. We follow an incremental approach in accordance with the contents of session 5 of the course, focused on semantics.

## Notebooks

### Word embeddings
Our first notebook is focused on learning word embeddings from a training corpus, assigning a vector to each word, following the distributional representational theory. We will see how to use one of the many algorithms available nowadays to this purpose and illustrate some of the properties that such word vector representations have, allowing for basic semantic operations, like checking word similarity, relatedness and analogy based on the cosine distance between the vectors that represent such words in the embeddings space.

### Knowledge Graph Embeddings
Word embeddings aim at capturing the meaning of words based on large corpora; however, there are decades of experience and approaches that have tried to capture meaning by structuring knowledge into semantic networks, ontologies and graphs. Examples of such resources include lexical knowledge graphs like WordNet. The second notebook shows how to leverage such resources and calculate representations of their content, like lemmas, senses, and the relations between them, in a common vector space.

### Building a vecsigrafo – generating hybrid representations from text corpora and knowledge graphs.
Knowledge graph embedding algorithms can capture structured knowledge about concepts and relations in a graph as embeddings in a vector space, which then can be used in downstream tasks. However, this type of approaches can only capture the knowledge that is explicitly represented in the graph, hence lacking in recall and domain coverage. Here we include tow examples of algorithms that address this limitation through the combination of information from both unstructured text corpora and structured knowledge graphs. The third notebook shows how to combine document corpora and knowledge graphs to learn richer representations that better capture the meaning of words.

## Resources and bibliography
