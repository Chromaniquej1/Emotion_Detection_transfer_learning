# Emotion_Detection_transfer_learning
Computer vision (CV) is the field of study that helps computers to study using different techniques and methods so that it can capture what exists in an image or a video. There are a large number of applications of computer vision that are present today like facial recognition, driverless cars, medical diagnostics, etc. We will discuss one of the interesting applications of CV that is Emotion Detection through facial expressions. CV can recognize and tell you what your emotion is by just looking at your facial expressions. It can detect whether you are angry, happy, sad, etc.

The article demonstrates a computer vision model that we will build using Keras and VGG16 – a variant of Convolutional Neural Network. We will use this model to check the emotions in real-time using OpenCV and webcam. We will be working with Jupyter Notebook to build the model. You can use any other IDE as well.


## What is in this project:
   * Data required for this project is in the subsquent folders (train_data) for training and (validation_data) for validation.
   * Trained VGG model so that we can detect emotions in the **code.ipython** file.
   * Saved model in the **ER1.h5** file.
   * Testing the model realtime based on trained model in **Test.ipython** file.
   
## The Dataset
The name of the data set is fer2013 which is an open-source data set that was made publicly available for a Kaggle competition. It contains 48 X 48-pixel grayscale images of the face. There are seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral) present in the data. The CSV file contains two columns that are emotion that contains numeric code from 0-6 and a pixel column that includes a string surrounded in quotes for each image.

## Softwares and dependancies required:
   * Python3: [link to download python3](https://www.python.org/downloads/)
   * Anaconda: [link to download Anaconda](https://www.anaconda.com)
   * In order to run codes in your system you need install **tensorflow** and **OpenCV** in your system
           **command to install tensorflow** is **pip install tensorflow**
   * command to install **OpenCV** is **pip install opencv-python**        
           
           
  
