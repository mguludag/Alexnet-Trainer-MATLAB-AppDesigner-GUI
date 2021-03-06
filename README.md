# Alexnet-Trainer-MATLAB-AppDesigner-GUI
GUI for create and train Alexnet Neural Network dataset with MATLAB

## Description
AlexNet is a convolutional neural network that is trained on more than a million images from the ImageNet database. The network is 8 layers deep and can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. As a result, the network has learned rich feature representations for a wide range of images. The network has an image input size of 227-by-227. For more pretrained networks in MATLAB®, see [Pretrained Deep Neural Networks](https://www.mathworks.com/help/deeplearning/ug/pretrained-convolutional-neural-networks.html).

## Requirements
* MATLAB 2019b or newer
* Deep Learning Toolbox
* Alexnet Support Package

## How to use?
* First resize the images to 227x227
* Don't mix different class images in same folder
* Arrange resized images in seperate folders and carefully set each folder's name because code will use foldernames for training *(example: cat pictures in cat folder)*
* Train the alexnet
* Load your created dataset and test the network

<p align="center">

  <img src="https://github.com/mguludag/Alexnet-Trainer-MATLAB-AppDesigner-GUI/blob/master/1.png?raw=true"><br>
  resize images screen

</p>

<p align="center">

  <img src="https://github.com/mguludag/Alexnet-Trainer-MATLAB-AppDesigner-GUI/blob/master/2.png?raw=true"><br>
  train alexnet screen

</p>

<p align="center">

  <img src="https://github.com/mguludag/Alexnet-Trainer-MATLAB-AppDesigner-GUI/blob/master/image.png?raw=true"><br>
  test screen

</p>
