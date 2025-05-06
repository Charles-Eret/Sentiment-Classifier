# Sentiment-Classifier
This project implements a sentiment analysis model using an LSTM-based Recurrent Neural Network built from scratch with PyTorch. The model is trained on the IMDB Movie Reviews dataset to classify reviews as either **positive** or **negative** in sentiment.

## 🚀 Project Overview

The pipeline includes:
- Data preprocessing (cleaning, tokenization, stopword removal)
- Vocabulary creation and word-to-index mapping
- Sequence padding
- Model definition with embedding, LSTM, dropout, and linear layers
- Training and validation loops with accuracy and loss tracking
- A prediction function to evaluate custom review inputs

## 🧠 Model Architecture

- **Embedding Layer**: Converts token indices to dense word vectors
- **LSTM Layer**: Captures sequential dependencies in text
- **Dropout Layer**: Prevents overfitting
- **Fully Connected Layer**: Maps LSTM output to a binary sentiment prediction
- **Sigmoid Activation**: Produces a probability score between 0 and 1

## 🗃️ Dataset

The model is trained on the [IMDB Movie Reviews Dataset](https://ai.stanford.edu/~amaas/data/sentiment/), which contains 50,000 reviews labeled as positive or negative.
