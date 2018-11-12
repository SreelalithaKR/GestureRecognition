# GestureRecognition
# Project as part of PG Diploma Course in ML and AI from Upgrad/IIITB

Convolutional Network to do gesture recognition
This is a feature that can be included in a smart TV to be able to recognise gestures to control the TV without a remote.
The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

Thumbs up:  Increase the volume
Thumbs down: Decrease the volume
Left swipe: 'Jump' backwards 10 seconds
Right swipe: 'Jump' forward 10 seconds  
Stop: Pause the movie

Each video is a sequence of 30 frames (or images)

For analysing videos using neural networks, two types of architectures are used commonly. 
One is the standard CNN + RNN architecture in which you pass the images of a video through a CNN which extracts a feature vector for 
each image, and then pass the sequence of these feature vectors through an RNN. 
The other popular architecture used to process videos is a natural extension of CNNs - a 3D convolutional network.
