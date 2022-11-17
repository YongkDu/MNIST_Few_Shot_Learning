# MNIST_Few_Shot_Learning

1. Train a FFN (fedforward neural network), such as fully connected network and CNN, with MNIST.

2. Manually select one image from each class from the training set.

3. Save the images and their logits from network 1.

4. Use data augmentation and generative models to train a second FFN network.

In file "FFN.ipynb", the basic FFN is fully connected network. The best ACC score is 0.72.

In file "ResNet.ipynb", the basic FFN is ResNet18. The best ACC score is 0.81, the best AUC score is 0.95.
