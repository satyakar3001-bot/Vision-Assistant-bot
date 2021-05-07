Problem: 
Visually challenged persons often feel helpless asking for some daily simple jobs and many of them often
afraid to ask unless it is very necessary.

My aim is to provide them a voice assistant which will narrate the situations of the nearby environment.

Specifications:
-> Model has been trained on Flicker 8k dataset from kaggle.
-> Used resnet-50 model to classify the objects of the images.
-> Final model is concatination of LSTM and CNN model to generate the next word sequence.
-> Contains files:
        testing on image.pynb:- To test the project on the sample images (in testing folder).
        using_camera:- Captures images from camera
        
Dependencies:
* Keras
* Pyttsx3
* Numpy
* Matplot
* Pandas
* Json
* Glob

Reference:
CS231n Winter 2016 Lesson 10 Recurrent Neural Networks, Image Captioning and LSTM- 
https://www.youtube.com/watch?v=cO0a0QYmFm8&t=1945s
