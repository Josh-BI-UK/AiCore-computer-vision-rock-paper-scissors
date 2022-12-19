<font size = 3> AiCore Project </font><br> 
<font size = 2> Python Data Science Project by: [Joshua Payne](https://github.com/Josh-BI-UK) </font>

# Computer Vision - Rock, Paper, Scissors Game Documentation


> In my AiCore Bootcamp course, I had to create a "Rock - Paper - Scissors" game that was based on (Deep Learning)[^1].For those not familiar with "Rock - Paper - Scissors (RPC)" you can find a general explanation of the classic hand game [here](https://github.com/Josh-BI-UK/AiCore-computer-vision-rock-paper-scissors/Game-Rules.md).

### **Technology\framework used:**<br>

> In this project you will be using:
> + Python 3.10 or higher
> + VS Code
> + Terminal
> + cv2 (Python library
> + keras (Python library
> + numpy (Python Library)
> + Mininconda (Python ditrbustion/package manager)


> This project aims to intoduce new data-scienents, ai-engineers, data-engineers etc. to Deep Learning concepts through the pratical application of training a neral network using familar game like rock, papaer, scissors (RPC)

We were provided a template *.py script whihc importted teh nesseary librarires and proccsed a kares model created through (Teachable Machine)[^2]]. I'm not sure if the template uses an official/best pratice framework, however, I intended to do a bit of resreach into possible frameworks/bestpratice project set-up to see if useable templates exist which I can use in future projects.
>

### **Learning Objective:**
Using a webcam streaming video image, build a deep learning model that recognizes a player's gestures (e.g. either Rock, Paper, Scissors) and correctly analyses them.

### **End Goal:**
Create a Python-based "Rock, Paper Scissors" game against the computer using the above logic.


[^1]: Link title (https://docs.microsoft.com/en-us/azure/machine-learning/concept-deep-learning-vs-machine-learning#:~:text=Deep%20learning%20is%20a%20subset%20of%20machine%20learning%20that%27s%20based%20on%20artificial%20neural%20networks.%20The%20learning%20process%20is%20deep%20because%20the%20structure%20of%20artificial%20neural%20networks%20consists%20of%20multiple%20input%2C%20output%2C%20and%20hidden%20layers.)

[^2]:Link title (https://teachablemachine.withgoogle.com/train)

---
%%%%%%
Go to Teachable-Machine  to start creating the model. Each class is trained with images of yourself showing each option to the camera. The "Nothing" class represents the lack of option in the image. Remember that the more images you train with, the more accurate the model will be

Milestone 1: Set-up the environment
Milestone 2: Create the computer vision system:

The first task consists of creating a computer vision system - also known as a model - that detects whether the user is showing Rock, Paper, or Scissors to the camera.

Task 1: Create an image project model with four different classes: Rock, Paper, Scissors, Nothing


Task 2: Download the model
Download the model from the "Tensorflow" tab in Teachable-Machine. 
The model should be named 'keras_model.h5' and the text file containing the labels should be named 'labels.txt'.

The files you are downloading contain the structure and the parameters of a deep learning model.  They are not files that can be run, and they do not contain anything readable if you look inside. Later, you will load them into your Python application in the next milestone. Make sure you push the model and labels to your GitHub repository after committing.

00_Template
01_Dev
02_Test
03_Solution

%%%%%%%%

---
The project deliverables have been broken up into units of work called "milestones", which in turn are divided into tasks as follows:<br>
<br>
<br>

## Milestone 1 - Set up the environment
The main objective of milestone 1 was to set-up our development enviroment.
<br>

### **Task 1:**  In this project, we'll use GitHub to track changes to our code and save them online in a GitHub repo.

Follow the instructions in the [Setup-guide.ipynb](/Setup-guide.ipynb) notebook found in the root directory.

As we will be using virtual enviroments as our means of creating isolated workspace set-up with the right depanacies and envirment configarion especial for the project you will also need to install and set miniconda. A guide to set-up miniconda can be found [here](www.replace-with-guide-url.com).
<br>

---
<br>

## Milestone 2: Create the computer vision system
The first task consists of creating a computer vision system - also known as a model - that detects whether the user is showing Rock, Paper, or Scissors to the camera.
<br>

### **Task 1:** Create an image project model with four different classes: Rock, Paper, Scissors, Nothing<br>
- **1.1** The first task consists of creating a computer vision system - also known as a model - that detects whether the user is showing Rock, Paper, or Scissors to the camera
<br>

Go to [Teachable-Machine](https://teachablemachine.withgoogle.com)" Teachable-Machine to start creating the model. Each class is trained with images of yourself showing each option to the camera. The "Nothing" class represents the lack of option in the image. Remember that the more images you train with, the more accurate the model will be.


### **Task 2:** Download the model <br>
- **1.2**  Download the model 
Download the model from the "Tensorflow" tab in Teachable-Machine. 
The model should be named `keras_model.h5` and the text file containing the labels should be named `labels.txt`<br>

The files you are downloading contain the structure and the parameters of a deep learning model.They are not files that can be run, and they do not contain anything readable if you look inside. Later, you will load them into your Python application in the next milestone.
<br>
Make sure you push the model and labels to your GitHub repository after committing.


### **Task 3:** Begin documenting your experience<br>
- **1.2**
- **1.3** Now that you have created your model and downloaded it, add documentation to your README file following this guide .

Talk about the model and how you will use it for this project. <br>
<br>