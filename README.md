# toxic_comment_model
Deep Learning model for multi-label classification of toxic text

As part of the Jigsaw Toxic Comment Classification Challenge ([https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge]) machine learning competition held on kaggle.com[https://www.kaggle.com/competitions], I used a set of different neural network architectures to model the data. The Jupyter notebook in this repo contains a single Keras model for the network architecture
bidirectional LSTM - 1-D CNN - bidirectional LSTM - 1-D CNN
with Fasttext frozen embedding
and Adam optimizer (details in notebook).

The final submission was an ensemble model which incorporated the solution from this script.
