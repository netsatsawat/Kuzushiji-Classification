# Kuzushiji-Classification

Dataset and more information can be found in the following [github](https://github.com/rois-codh/kmnist).

This repository is for demonstrating how deep learning helps to identify and classify the Kuzushiji characters.

![image](https://github.com/netsatsawat/Kuzushiji-Classification/raw/master/img/KMNIST_example.JPG)

### The Dataset
<hr>
There are three datasets of Kuzushiji, which I used for demonstrating and writing the code.

__Kuzushiji-MNIST__ is a drop-in replacement for the MNIST dataset (28x28 grayscale, 70,000 images), provided in the original MNIST format as well as a NumPy format. Since MNIST restricts us to 10 classes, we chose one character to represent each of the 10 rows of Hiragana when creating Kuzushiji-MNIST.

__Kuzushiji-49__, as the name suggests, has 49 classes (28x28 grayscale, 270,912 images), is a much larger, but imbalanced dataset containing 48 Hiragana characters and one Hiragana iteration mark.

__Kzushiji-Kanji__ is an imbalanced dataset of total 3832 Kanji characters (64x64 grayscale, 140,426 images), ranging from 1,766 examples to only a single example per class.

### Part 1: Convolutional Neural Network
<hr>
This part consists of the Jupyter Notebook's tutorial for implementing various dimensional reduction techniques on the high dimension data and building the convolutional neural network from scratch using Keras. This notebook only used the Kuzushiji-MNIST data set.

![cnn-example](https://github.com/netsatsawat/Kuzushiji-Classification/raw/master/img/CNN-Architecture-from-AlexNet.png)

My two articles in medium.com are directly referenced toward this notebook.

- Dimension Reduction Tutorial on Kuzushiji MNIST [[Link](https://medium.com/@net_satsawat/dimension-reduction-tutorial-on-kuzushiji-mnist-93419101474e)]
- Beginner guides to Convolutional Neural Network from scratch - Kuzushiji-MNIST  


### Part 2
<hr>
TBC

### Part 3
<hr>
TBC


### License
<hr>
Both the dataset itself and the contents of this repo are licensed under a permissive  [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) license, except where specified within some benchmark scripts. CC BY-SA 4.0 license requires attribution, and we would suggest to use the following attribution to the KMNIST dataset.

"KMNIST Dataset" (created by CODH), adapted from "Kuzushiji Dataset" 
(created by NIJL and others), doi:10.20676/00000341
