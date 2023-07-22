# Emotion Recognition

This project recognizes the emotion of a person using imageNet, which will learn how a person's face looks when they show different emotions.

![add image descrition here](direct image link here)

## The Algorithm
For this project, I’ve used ResNet-18, since it can already recognize many things that it is pre-trained to. Each block of code does a different task. It first sets up the camera to make sure it’s running, then lets you define the task and category of the project (in this case it’s “emotions” as the task, and as the categories, different emotions like happy, sad, angry, surprised, and scared.) The next block of code creates the data collection tool widget, which counts the images that you input and sets up the user interface. After this, the neural network (ResNet-18) is defined, and it is made sure that only the number of classes are accepted. The live execution block of code makes sure that you can view the camera feed live. The last two blocks of code set up the training and evaluation, and display the interactive tool. 


## Running this project
To reproduce this project, using the interactive tool and running each block of code would make it work. You can edit the tasks and categories, and train the model to recognize any emotion.

[View a video explanation here](video link)
