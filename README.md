# Variational-AutoEncoders-meets-NeuralNets
Comparing results between features obtained by a VAE as compared to using raw inputs for a feed forward neural network.
Variational Autoencoders help us perform semi-supervised learning in cses when there is a shortage of data for deep learning. But do these features accurately capture enough patterns to train Neural Networks? This interactive notebook is an attempt to understand the limitations and uses of VAE for this puprose.

The notebook is divided into 4 parts - 
1. Creating a VAE and all its constituent parts.
2. Training a simple feedforward neural network using features obtained from the VAE.
3. Training a simple feedforward neural network using the plain dataset.
4. Comparing results and investigating further.

The dataset used here is the MNIST Handwritten Digits dataset, available with the keras library.
