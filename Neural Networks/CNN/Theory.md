#Convolutional Neural Network is a feed forward neural network that learns through kernel optimization. They are primarily used in Computer Vision tasks and allows us 
to build translational invariance into them through pooling.
Kernels are matrices that perform convolution operations, the kernels are slid across the input data to extract features which are then fed into the next layer.

I will expand on the classic convolutional neural network LeNet in here and provide a breakdown of the architecture. And the implementation to it will be
provided in jupyter notebook file.

Architecture of LeNet5:

The CNN comprised of 7 layers not including the input layer. And the input is normalized such that the mean is zero and the variance is 1 (This is usually done to accelerate learning). A CNN typically consisits of 3 kinds of layer 1. Convolutional Layer 2. Pooling/Sun sampling Layer 3. Fully connected layers.

![LeNet-5 Architecture](Screenshot%202025-05-03%20191016.png)
*Source: [Gradient Based Learning Applied to Document Recognition](https://example.com)*










