---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /about
---

{% include base_path %}

## <span style = "font-family: Georgia;"> MNIST Digit Recognizer </span>

[MNIST Digit recognizer](https://github.com/sonamtripathi/MNIST_digit_recognizer)

<span style="font-family: Georgia;"> This project focuses on identifying the hand-written digits in real-time using the 3 Models(Logistic Regression, Simple Neural network, Deep Learning Model) 

**Softmax Regression:**
First we have use Simple Multinominal Logistic Regression or Softmax Regression. It is a generalization of Logistic regression for those cases where we want to handle multiple classes.In Logistic Regression we assumed that the labels are binary: . We used such a classifier to distinguish between two kinds of hand-written digits.Softmax Regression allows us to handle  where K is the number of Classes.In the softmax regression, we are interested in multi-class classification and so the label y can take K different values, rather than only two. Thus, in our training set , we now have that .In our MNIST digit recognition task, we would have K = 10 different classes.

**Simple Neural Network:**
Second we have also implemented Simple feed forward neural network for classificationwe have used softmax layer for classifying the digits to one of the 10 categories.

**Deep Learning Model:**
Lastly we have used Deep Neural model with "ReLU" activation function and "softmax" loss function.

-------

## <span style = "font-family: Georgia;"> Identifying Entities in Healthcare Data </span>

[Identifying Entities in Healthcare Data](https://github.com/sonamtripathi/NLP_Named_Entity_Recognition)

<span style="font-family: Georgia;"> The data is taken from a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.

Example:- “The patient was a 62-year-old man with squamous cell lung cancer, which was first successfully treated by a combination of radiation therapy and chemotherapy.”

As you can see in this text, a person with a non-medical background cannot understand the various medical terms. We have taken a simple sentence from a medical data set to understand the problem and where you can understand the terms ‘cancer’ and ‘chemotherapy’.

Suppose you have been given such a data set in which a lot of text is written related to the medical domain. As you can see in the dataset, there are a lot of diseases that can be mentioned in the entire dataset and their related treatments are also mentioned implicitly in the text, which you saw in the aforementioned example that the disease mentioned is cancer and its treatment can be identified as chemotherapy using the sentence.

But, note that it is not explicitly mentioned in the dataset about the diseases and their treatment here we have identified it using NER technique. </span>

-------

## <span style = "font-family: Georgia;"> Frontal Face Detection using haar cascade</span>

[Frontal Face Detection using haar cascade](https://github.com/sonamtripathi/frontal_face_detection_using_haar_cascade)

<span style="font-family: Georgia;"> In this project we have implemented Frontal Face Detection Using Haar Cascade(Viola-Jones Algorithm)

Viola-Jones is the first object detection algorithm used primarily for solving Face Detection Problem.

The Algorithm works in 4 Stages.

- Haar Feature Selection
- Creating an Integral Image.
- Adaboost Training
- Cascading Classifiers

Here we have implemented it using Opencv library Dependency: Haar Features xml file,OpenCv ,Python3

Run the "Face_Detection_OpenCV.py" file but before that download the Haar Cascade(xml files).

-------
