
![Lenet](https://github.com/deadshotbane80/LeNet-5-Implementation-in-Pytorch./assets/91062830/71d66c64-dfb9-4dcb-9166-c8f54238d87c)


This project implements the [LeNet-5](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf) Convolutional Neural Network (CNN) in PyTorch, training it on the classic MNIST handwritten digit recognition dataset.
I also wrote a [blog](https://vedantpoduval.hashnode.dev/from-pixels-to-predictions-a-lenet-5-intro-in-pytorch) to give a detailed explanation of the whole code.
The architecture of the model is simialar to original [paper](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf) but instead of the tanh activation it uses ReLU and also the weights are initialised using [kaiming](https://arxiv.org/abs/1502.01852) initialisation.
The overall accuracy I achieved was 97.4% while running for 10 epochs.
References : 
1.)[Original Paper](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf)
2.)[Andrej Karpathy's Lecture](https://www.youtube.com/watch?v=LxfUGhug-iQ)

