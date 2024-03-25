# Recognizing Hand written numbers using Convolutional Neural Network 

This project is focused on recongnizing hand written letters using cnn model. 

The first procedure I have applied is loading the dataset is preprocessing it to best fit the model. 

Then a I have created a CNN model with 3 convolutional blocks each contains 2 Conv2D layers and one MaxPooling layers. Then I have specified the models optimizer function, loss and metrics. 

### The following image shows the models summary 

<img src="https://github.com/tewodrosseble/handwritten-number-recognition-using-cnn/blob/main/modelinfo.png">

Totally there are around 290 thousand parameters from which the model can learn. 

I have evaluated the model and get an accuracy of 97.9%. 

### The following image shows the accuracy-epoch and loss-epoch plots 

<img src="https://github.com/tewodrosseble/handwritten-number-recognition-using-cnn/blob/main/graph.png">


### I have tested the trained model with new data and here it shows the result as the following 

<img src="https://github.com/tewodrosseble/handwritten-number-recognition-using-cnn/blob/main/test.png">


### Tewodros Seble
### @ 2022
