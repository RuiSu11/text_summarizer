# Abstractive Text Summarization Using the Transformer Model
Abstractive Text Summarization is the task of generating a short and concise summary that captures the salient ideas of the source text. The generated summaries potentially contain new phrases and sentences that may NOT appear in the source text.

A transformer is a deep learning model introduced in 2017 by a team at Google brain. It adopts the mechanism of self-attention, differentially weighting the significance of each part of the input data. Transformers are increasingly the model of choice for NLP problems, replacing recurrent neural network (RNN) models such as long short-term memory (LSTM).

Here I used the transformer model for the task of abstractive text summarization. I used a dataset consisting of 0.5 million reviews of fine foods from amazon (available at https://www.kaggle.com/snap/amazon-fine-food-reviews). Each review comes with a summary of a few words.

The model was written using the tensorflow package. The codes were run on google colab where free gpus are available for faster training.
