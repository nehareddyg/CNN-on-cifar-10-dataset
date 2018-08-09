# CNN-on-cifar-10-dataset

Base Architecture of the model:
The neural network has 2 convolution layers and 2 fully connected
layers, followed by a softmax layer. The first convolution layer has 64 filters each of size
5*5. It is followed by a max pooling layer of size 2*2. The second convolution layer also
has 64 filters each of size 5*5. This layer is also followed by a max pool layer. The size
of the first fully connected layer is 256 and followed by another fully connected layer of
size 128.

![alt text](https://github.com/nehareddyg/CNN-on-cifar-10-dataset/blob/master/model.png)
