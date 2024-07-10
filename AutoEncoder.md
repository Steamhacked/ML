Autoencoder - unsupervised learning approach that utilizes deep learning neural network architecture 
Consists of the:
  Encoder - compresses data, into the lower-dimensional representation
  Decoder - decompresses data, into original data
Training Autoencoder:
  L(x, g(f(x)); L() -> Loss function that penalizes difference between reconstructed data from original, g() -> decoder function, f() -> encoder function
Optimal Autoencoder will be sensitive enough to properly reconstruct data, but insensitive enough to prevent overfitting

