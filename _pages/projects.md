---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /about
---

{% include base_path %}


## <span style = "font-family: Georgia;"> Identifying Entities in Healthcare Data </span> 👩‍🔬 💊 

[Identifying Entities in Healthcare Data](https://github.com/sonamtripathi/NLP_Named_Entity_Recognition)

<span style="font-family: Georgia;">
▶︎ Here the objective is to identify the diseases and predicted treatment using a custom NER from the text data which is taken from a web platform which allows doctors to list their services and manage patient interactions and provides services for patients.

▶︎ After processing the 3k doctor and patient’s interaction text data which is given in the form of tokens and then we identify all the words from the corpus that have a POS tag of NOUN or PROPN (nouns) and prepare a dictionary of their counts which was further used in the CRF model.

▶︎ We have trained the custom NER model using CRF which was successfully able to identify 91% of the disease and their treatments from the given text data.

Example:- “The patient was a 62-year-old man with squamous cell lung cancer, which was first successfully treated by a combination of radiation therapy and chemotherapy.”

As you can see in this text, a person with a non-medical background cannot understand the various medical terms. We have taken a simple sentence from a medical data set to understand the problem and where you can understand the terms ‘cancer’ and ‘chemotherapy’.

-------

## <span style = "font-family: Georgia;"> Topic Modeling Complaints using Non-Negative Matrix Factorization </span> 📚📚 

[Topic Modeling Complaints using Non-Negative Matrix Factorization](https://github.com/sonamtripathi/NLP-Project)

<span style="font-family: Georgia;"> 

▶︎ Build different models (Logistic Regression, Naive Bayes, Decision Tree and Random Forest) for a financial company’s customer complaints data which is successfully able to classify 93% of the customer complaints text based on the product/services.

 ▶︎ The proposed model significantly resolved the complaints processing time, which bring down customer dissatisfaction to a minimum and retain them with stronger loyalty.
 
-------

## <span style = "font-family: Georgia;"> MNIST Digit Recognizer </span>  4️⃣  2️⃣  🔍

[MNIST Digit recognizer](https://github.com/sonamtripathi/MNIST_digit_recognizer)

<span style="font-family: Georgia;"> 

This project focuses on identifying the hand-written digits in real-time using the 3 Models(Logistic Regression, Simple Neural network, Deep Learning Model) 

**Softmax Regression:**
First we have use Simple Multinominal Logistic Regression or Softmax Regression. It is a generalization of Logistic regression for those cases where we want to handle multiple classes.In Logistic Regression we assumed that the labels are binary: . We used such a classifier to distinguish between two kinds of hand-written digits.Softmax Regression allows us to handle  where K is the number of Classes.In the softmax regression, we are interested in multi-class classification and so the label y can take K different values, rather than only two. Thus, in our training set , we now have that .In our MNIST digit recognition task, we would have K = 10 different classes.

**Simple Neural Network:**
Second we have also implemented Simple feed forward neural network for classificationwe have used softmax layer for classifying the digits to one of the 10 categories.

**Deep Learning Model:**
Lastly we have used Deep Neural model with "ReLU" activation function and "softmax" loss function.

-------

## <span style = "font-family: Georgia;"> Frontal Face Detection using haar cascade</span> 🙍🏻‍♀️ 

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

## <span style = "font-family: Georgia;"> Corona Virus(Covid-19) Impact in India </span>  💊💊

[Corona Virus(Covid-19) Impact in India](https://www.kaggle.com/code/geekysaint/corona-virus-covid-19-impact-in-india)

<span style="font-family: Georgia;"> 
▶︎ Here we have taken the dataset from John Hopkinson's university on the Covid dataset and studied the overall impact (deaths, cases, recovery rate of covid) across various parts of India over the period of time.

▶︎ Here we have taken the dataset from John Hopkinson's university on the Covid dataset and studied the overall impact (deaths, cases, recovery rate of covid) across various parts of India over the period of time.

[How Covid has spread across different states in India](https://github.com/user-attachments/assets/2889f6cd-f613-489d-96b6-0db7a42d7f2f)

-------
