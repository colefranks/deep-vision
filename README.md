# Deep Learning in Computer Vision 

[PyTorch](https://github.com/pytorch/pytorch) / [Tensorflow](https://github.com/tensorflow/tensorflow) implementation of common deep learning models and training scripts for computer vision tasks. This is used to ease the learning curve for new DL practitioners. If you think my work is helpful, please ⭐star⭐ this repo. If you have any questions regarding the code, feel free create an issue.

The repo is categorized by datasets, then further by framework. Some pretrained models, Jupyter notebook visuliazation script, and training logs are also provided for your reference.

## Image Classification

- [ImageNet ILSVRC2012](imagenet-2012)
    - [PyTorch](imagenet-2012/pytorch)
        - AlexNet
        - VGG
        - GoogLeNet, Inception
        - ResNet
        - MobileNet
    - [TensorFlow](imagenet-2012/tensorflow)
        - AlexNet
        - ResNet
- [CIFAR-10](cifar-10)
- [MNIST](mnist)
    - [PyTorch](mnist/pytorch)
        - LeNet
    - [TensorFlow](mnist/tensorflow)
        - LeNet

## Object Detection

- [Pascal VOC2007](voc-2007)

## Setup

- Create a virtualenv with Python3 `python3 -m venv env`
- Install dependencies by `pip install -r requirements.in`
- If you have CUDA GPU, also run `pip install tensorflow-gpu`

## Disclaimer

- This repo is mainly for study purpose. Hence I write the code in a readable and understandable way, but may not be scalable and reusable. I've also added comments and referrence for those catches I ran into during replication.
- I'm not a researcher so don't have that much of time to tune the training and achieve the best benchmark. If you are looking for pre-trained models for transfer learning, there're some good ones from [PyTorch torchvision](https://pytorch.org/docs/stable/torchvision/models.html) or [TensorFlow slim](https://github.com/tensorflow/models/tree/master/research/slim).