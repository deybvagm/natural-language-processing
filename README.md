# natural-language-processing
This repository shows different NLP models on several datasets like IMDB, YELP, Sentiment140 and Sarcasm

This repository implements and compares different neural network architectures and libraries to solve a sentiment classification problem. Architectures range from simple neural networks architectures to LSTM, GRU and CNN with and without regularization techniques.
The idea is to compare performance on different datasets and with different hyperparameter configuration


## Frameworks

- [Tensorflow 2.0](https://www.tensorflow.org/)
- [FastText](https://fasttext.cc/)

## Datasets

- **IMDB movie review**: This dataset contains movie reviews along with their associated binary sentiment polarity labels. It is intended to serve as a benchmark for sentiment classification. The dataset contains 50.000 reviews evenly distributed into 25000 training reviews and 25000 testing reviews. The dataset is available from the Tensorflow data services module
- **YELP**: Is a dataset that contains reviews about different service providers like restaurants, parking lots, among others. The dataset contains 4.7 milliom reviews and the classification task consist in predict the number of starts (0-5) for each review
- **Sarcasm**: The goal with this dataset is to determine if a sentence is sarcastic. There are 26.000 sentences
- **Sentiment140**: This is a dataset with sentiments extracted from twitter. There are 1.600.000 tweets, each annotated as 0=negative or 4=positive to perform a sentiment classification task

