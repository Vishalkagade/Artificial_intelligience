# Convolutional_Neural_Network_Classification

#### We are discussing how to build the CNN network for image classification for pokemon dataset.The dataset contains 150 different classses and it is downloaded from [kaggle Pages]([https://pages.github.com/](https://www.kaggle.com/datasets/rounakbanik/pokemon)]).
In this model, there are 3 CNN blocks, and each block consists of 2 convolution layers and 1 max-pooling layer. Relu activation function is used to remove negative values from the feature map because there can not be negative values for any pixel value. Stride(1,1) used and padding is also 1.

After applying convolution and extract features from the image, a flatten layer is used to flat the tensor which has 3 dimensions. The flatten layer converts the tensor to one-dimensional. Then 3 linear added to reduce the size of the tensor and learn the features.

<img width="466" alt="CNN" src="https://user-images.githubusercontent.com/105672962/204937168-b0f7b035-e472-4166-a36f-d6fa1b17e9eb.png">
