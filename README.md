
# **IMBD Sentiment analysis**

**This project utilizes a PyTorch-based BERT (Bidirectional Encoder Representations from Transformers) model for sentiment analysis on IMDb movie reviews. The goal is to predict the sentiment (positive or negative) of a given movie review.**

## Prerequisites

1. **Python 3.x**
2. **PyTorch**
3. **Transformers library (Hugging Face)**
4. **minor dependencies (listed in requirements.txt)**

## Model Architecture

- **BERT, or Bidirectional Encoder Representations from Transformers, is a cutting-edge natural language processing architecture. Unlike traditional models, BERT employs a bidirectional encoder-only architecture, processing input data by considering context from both left and right sides of each word in a sentence.**

- **The attention mechanism, a pivotal component, allows the model to assign varying weights to different words, emphasizing their importance in understanding context. BERT utilizes word embeddings, representing words as vectors in a high-dimensional space to capture semantic relationships.** 

- **Pre-training on vast amounts of unlabeled text data enables BERT to learn general context and relationships between words. Fine-tuning on specific tasks, such as sentiment analysis, refines the model for more targeted applications.**

## Dataset

**The dataset has been taken from kaggle, the following link provides access to the dataset.**

[Link to the dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

## Results

**The model was able to obtain 92% accuracy in sentiment analysis of reviews.**

## License

**This project is licensed under the MIT License.**