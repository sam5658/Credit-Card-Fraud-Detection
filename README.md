# Credit-Card-Fraud-Detection
This project ustilizes semi supervised learning for detecting credit card fraud. I will be using the kaggle dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud.

The autoencoders is trained with unsupervised learning, an autoencoder does not have any target data but rather uses the same input as target. It first reduces the dimension to a latent space and then decodes the vector to the original input shape. It evovels through reducing the loss in reproduce the input data.

Here we aim to feed the data to a trained autoencoder and extract the new data representation.
Later we can perform supervised learning classification task on the new data representation.

The latent space representation is produced in order to create a more easily distinguishable distribution for easily classifing the data.
