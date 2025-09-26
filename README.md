This project implements a Natural Language Processing (NLP) model that classifies movie reviews from the IMDB dataset as either positive or negative. The dataset contains 50,000 reviews that are preprocessed into integer sequences representing words.

To prepare the data, reviews were tokenized using only the 10,000 most frequent words, and then padded to a fixed length of 500 tokens to ensure uniform input size.

A deep learning model was built using TensorFlow/Keras, combining an Embedding layer for word vector representations and an LSTM (Long Short-Term Memory) network for learning long-term dependencies in text. The final layer uses a sigmoid activation to output probabilities for binary sentiment classification.
