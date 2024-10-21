# rand_wire_nn
The repository contains code for RandWire this is a type of convolutional neural network that arise from randomly wired neural networks that are sampled from stochastic network generators, in which a human-designed random process defines generation.

![image](https://github.com/user-attachments/assets/44cce54a-a03f-46f9-9a5b-6bd6780e36d1)


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

*The Libraries used in my environment : [requirements.txt](https://github.com/rpattan1607/ImageCaptioning_CNN_LSTMs/blob/main/requirements.txt)*

## Sample Output
