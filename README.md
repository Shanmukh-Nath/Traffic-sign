# Traffic-sign

This project is developed to detect traffic sign objects using OpenCV Library and Deep Learning Algorithms

This model can classify upto 43 Labelled objects
Using Convolutional Neural Network I was able to achieve 89% accuracy.
There are two parts for this project

## Training
1. Training is done in [trainer.py](https://github.com/Shanmukh-Nath/Traffic-sign/blob/master/trainer.py) file
2. I have used 4 Conv2D Layers and 2 MaxPool Layers
3. Using Convolutional Neural Network(CNN) combined with Computer Vision (CV), I was able to train this Neural Network.
4. The trained model is saved in h5 format for further use.

## Implementation
1. The h5 formatted model file is loaded in [GUI.py](https://github.com/Shanmukh-Nath/Traffic-sign/blob/master/gui.py).
2. Then I created a dictionary stating 43 classes, starting from 0 - 42, where each class represents a label.
3. The dataset used in Training can be found in [Train Folder](https://github.com/Shanmukh-Nath/Traffic-sign/tree/master/Train). 
4. Then a basic Graphical User Interface(GUI) is designed for handling the model for prediction with upload button and classify image button. 

# Images

### Some GUI Images

![Before]<img src="https://i.ibb.co/xLcDXfZ/before.png" width="50%" height="50%">
![After](https://i.ibb.co/4WD3R5V/after.png)

