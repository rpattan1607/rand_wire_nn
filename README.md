# Rand Wire NN
The repository contains code for RandWire this is a type of convolutional neural network that arise from randomly wired neural networks that are sampled from stochastic network generators, in which a human-designed random process defines generation.

<div align="center">
	<img src="https://github.com/rpattan1607/rand_wire_nn/blob/3adcaa80144d76a4d8a14eceaa956569e6b44cf6/images/model.png">
</div>

Original Paper: https://arxiv.org/pdf/1904.01569

## Key features and functionalities:

*CIFAR-10 Dataset Loading with Augmentation:*
The dataset is loaded using torchvision.datasets with built-in data augmentation techniques to enhance model generalization.

*Randomly Wired Model Architecture:*
The neural network architecture is built based on random graph generation, following the approach from the paper "Exploring Randomly Wired Neural Networks for Image Recognition."

*Training Loop:*
Implements a standard training loop with:
Cross-entropy loss
Optimization using stochastic gradient descent (SGD)
Cosine annealing learning rate scheduler for efficient training.

*Checkpoint Loading:*
Provides functionality to load model checkpoints to resume training or for evaluation.

*Prediction and Plotting:*
After training, the model makes predictions on test data, and results are plotted for visualization.

## Requirements 

* Python
* PyTorch 
* NumPy
* Matplotlib
* networkx

*The Libraries used in my environment : [requirements.txt](https://github.com/rpattan1607/rand_wire_nn/blob/e6e7a2c570b8e6e4443ba1d3fa7d35b26a8f761c/requirement.txt)*

## Sample Output
