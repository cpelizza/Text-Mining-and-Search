# Text Mining and Clustering of NYSK articles

**Author:** [Daria Marinucci, Chiara Pelizza, Matteo Suardi]    

## Description
This project implements a complete text mining pipeline for the analysis of news articles from the NYSK dataset using Jupyter Notebooks.  
The work is organized into two main components, each implemented in a separate notebook:

- **Document Clustering** (`clustering.ipynb`):  
  This notebook covers data loading, text preprocessing, exploratory analysis, feature extraction using both sparse lexical representations (TF–IDF) and dense semantic embeddings (Word2Vec and GloVe), unsupervised clustering (K-Means, Agglomerative Clustering, DBSCAN), evaluation, and visualization of results.

- **Text Summarization** (`summarization.ipynb`):  
  This notebook focuses on automatic summarization of news articles, comparing extractive approaches (SumBasic, LexRank, LexRank with MMR) with an abstractive baseline based on BART. Model performance is evaluated using ROUGE, BLEU, and BERTScore metrics.

Together, the two notebooks provide a comprehensive framework for unsupervised document organization and automatic text summarization.


## Requirements
- Python 3.11
- Jupyter Notebook or Google Colab
  

## Running the Notebook
- Open the notebook in Colab or Jupyter
- Ensure the XML file path is correct
- Run all cells sequentially
- The notebook will automatically install all required packages
- Outputs include preprocessed data, WordClouds, clustering visualizations, and evaluation metrics
