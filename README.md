Fashion-MNIST Neural Network from Scratch

OVERVIEW
This project implements:

IMPLEMENTATION

-create a notebook in google colab.

-run the cell and load the data from keras.dataset.fashion_mnist

-install wandb in colab and log in using API key

-run the sweep cell

DATA HANDLING

-The total of 60000 data was split into the ratio of 90% for training and 10% for testing

SWEEP

-bayesian seacrch method is used

-hyperparameter searched are epochs, number of hidden layers, hidden layer size, weight decay, learning rate, optimizer, batch size , weight initialisation, activation function.

-sweep dashboard[https://wandb.ai/mohitofficial7777-misrimal-navajee-munoth-jain-college/fashion-mnist-nn/sweeps]

RESULT

-best validation accuracy[87.35%]

