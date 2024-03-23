
![The Simpsons](https://www.indiewire.com/wp-content/uploads/2014/08/the-simpsons.jpg)

## Objective of the project

Train a Convolutional neural network (CNN) model to classify characters from the animated series "The Simpsons".

## Tasks:
Achieve the best quality of the model on the test dataset. 
 -The minimum required metric value is 0.83. A metric value over 0.95 is considered an excellent indicator

In addition to building a neural network and assessing its quality, it is necessary to:
- measure network training time;
- write a function that will take a link to an arbitrary image as input and predict its class;
- write a code that will output 9 random images from the test with their actual and predicted classes;
- study the classes in which the model most often makes mistakes.

## Conclution

In the process of data preprocessing, the following actions were performed:
- Pre-balancing classes by removing the number of images in classes with large data content;
- Doubling the number of images by augmentation copies of images in small classes.

These transformations improved the classification accuracy of the trained models and reduced the training time (on the model with the highest accuracy, the training time decreased by 10% compared to the same model trained on the original dataset).

The highest image classification accuracy was obtained based on the ResNet152 model - about 97%. 
This model classifies characters with high accuracy for which sufficient training data has been collected. The model generally makes mistakes when classifying characters for which little data has been collected. To improve the model's accuracy, it is necessary to increase the amount of training data in small classes.

## Skills and tools 

* Data preprocessing
* Data augmentation
* Python
* Pandas
* PIL
* Matplotlib
* Scikit-learn
* PyTorch

## Project status
- [x] 
