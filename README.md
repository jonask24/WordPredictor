# WordPredictor

A Python-based natural language processing tool that predicts semantically related words using a word space model trained on Swedish Wikipedia data via word2vec.

## Overview

WordPredictor represents words as vectors in a high-dimensional vector space (word embeddings) to capture semantic relationships between words. Built using the Gensim library and trained on the Swedish Wikipedia corpus, this tool can:

- Find semantically similar words
- Solve word analogy tasks
- Calculate semantic similarity between words

## Features

- **Semantic Similarity Calculation**: Measure how similar two words are using cosine distance
- **Word Analogy Prediction**: Complete word analogies (e.g., "man is to woman as king is to ___")
- **Word Vector Representation**: Represent words as 100-dimensional vectors

## Technologies Used

- Python
- Gensim library
- Word2vec model
- Swedish Wikipedia corpus (training data)
- Jupyter Notebook