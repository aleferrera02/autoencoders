# PCA and autoencoders: a comparison on image denoising
This report provides a comparison between Prin
cipal Component Analysis (PCA) and autoencoders. Both tech
niques are used for dimensionality reduction, i.e. the process of
 reducing the number of features in a dataset while preserving
 as much information as possible. PCA is a linear method that
 identifies the directions of maximum variance in the data, while
 autoencoders are neural networks which are trained to attempt to
 copy its input to its output. Indeed, autoencoders are designed to
 be unable to learn to copy perfectly, but to capture the underlying
 structure of the data. The goal of this report is to understand the
 similarities and differences between PCA and autoencoders, to
 design and train a DAE (Denoising Autoencoder) and to compare
 its performance with PCA.

 Remark! To run the code you should download chestmnist dataset online
