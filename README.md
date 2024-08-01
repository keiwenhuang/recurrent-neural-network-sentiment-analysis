# recurrent-neural-network-sentiment-analysis

## Project Overview
This group project implements a recurrent neural network approach to perform sentiment analysis on data from RateMyProfessor, a college professor rating website.

## Data Sources
- Dr. Jibo He's sample dataset
- Kaggle JSON dataset
- Custom web-scraped data

## Data Preparation Methods
1. **Binary Sentiment Function**: 
   - Ratings < 4 classified as poor sentiment
   - Similar metric applied for difficulty

2. **Label Encoding**: 
   - Using scikit-learn's built-in Label Encoding
   - Encodes values into target labels between 0 and n_classes-1

3. **Raw Data**: 
   - Minimal preprocessing, used as-is in the model

## Models Implemented
1. **Model 1**: GRU with categorical_crossentropy loss function and sigmoid activation
2. **Model 2**: GRU with binary_crossentropy loss and sigmoid activation
3. **Model 3**: LSTM with binary_crossentropy loss and sigmoid activation
4. **Model 4**: GRU with sparse_categorical_crossentropy and softmax activation

## Requirements
- Python 3.x
- TensorFlow
- Keras
- scikit-learn
- Pandas
- NumPy
- NLTK
- Matplotlib
- IPython
