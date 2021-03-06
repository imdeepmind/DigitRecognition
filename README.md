# Digit Recognition

Digit Recognition is a simple project that predicts handwritten digits.

![Screenshot from 2019-08-04 20-57-30](https://user-images.githubusercontent.com/34741145/62425763-84f15b00-b6fa-11e9-8c6e-03fa9343a86b.png)

## Branches
In this repo, there are 3 branches
1. master - This branch contains the main web app. I've used Flask for this part of the project.
2. cnn-keras - This branch contains the main CNN for making the classifier
3. gh-pages - This branch contains a simple Web app created using Bootstrap 

## Programming Languages and Libraries used
Python, Flask, Keras, Numpy, Pandas, HTML, CSS, JavaScript, jQuery, and Bootstrap

## gh-pages Branch
This branch contains a very simple web app. In this app you can draw a simple digit (0-9) and then click upload. It will recognize the digit. 

To run part of the project locally just run the index.html file. 

## cnn-keras Branch
This branch contains the python code for training a complex CNN. To run this part of the project locally, first install tensorflow and keras, and then extract the mnist_png.tar.gz file. Finally run the cnn.py file.

Link to colab notebook - https://colab.research.google.com/drive/1JOLiEy8uc-8Jr1i2ftbjigjsqFbfYdtQ

## master Branch
This branch contains a very simple REST API developed in Flask. This API just uses the model and predict the result.

## Demo
https://imdeepmind.com/DigitRecognition/
