# Text Mining Project: Unsupervised Clustering and Automatic Summarization of News

**Author:** [Daria Marinucci, Chiara Pelizza, Matteo Suardi]    

## Description
This project implements a complete text mining pipeline for the analysis of news articles from the NYSK dataset using Jupyter Notebooks.  
The work is organized into two main components, each implemented in a separate notebook:

- **Document Clustering** (`clustering.ipynb`):  
  This notebook covers data loading, text preprocessing, exploratory analysis, feature extraction using both sparse lexical representations (TF–IDF) and dense semantic embeddings (Word2Vec and GloVe), unsupervised clustering (K-Means, Agglomerative Clustering, DBSCAN), evaluation, and visualization of results.

- **Text Summarization** (`summarization.ipynb`):  
  This notebook focuses on automatic summarization of news articles, comparing extractive approaches (SumBasic, LexRank, LexRank with MMR) with an abstractive baseline based on BART. Model performance is evaluated using METEOR, ROUGE, BLEU, and BERTScore metrics.

Together, the two notebooks provide a comprehensive framework for unsupervised document organization and automatic text summarization.

The folder also contains the raw dataset (nysk.xml), which is used as input for both the clustering and summarization pipelines. In addition, a preprocessed version of the data (df_preproc.pkl) is provided and used as input for the clustering notebook for the different text representations employed.
The notebook includes the code required to perform preprocessing from scratch; however, since this step is computationally demanding, we recommend loading the preprocessed file directly. The preprocessing cell is commented out, while the cell for loading the processed file is enabled.

## Requirements
- Jupyter Notebook or Google Colab
  

## Running the Notebook
- Open the notebook in Colab or Jupyter
- Ensure the XML file path is correct
- Run all cells sequentially
- Outputs include preprocessed data, WordClouds, clustering visualizations and evaluation metrics
