# Nanodegree: AI Product Management 🎓

This repository tracks my journey as I progress through the [Udacity Nanodegree in AI Product Management](https://www.udacity.com/course/ai-product-manager-nanodegree--nd088). 

The course provides a comprehensive overview of how AI technologies can enhance and inform product management. It covers everything from creating datasets and building models, to measuring impact and continuously updating models.

<br>

## Course Layout 📚 

### 🌟 Introduction to AI in Business

In this module, we delve into the fascinating world of AI and its applications in business. We learn how AI technologies can analyze and learn from data, leading to improved decision-making and more effective product management. 

### 📝 Creating Datasets

In this part of the course, we explore how to build custom datasets, which form the foundation of machine learning models. We also learn how to annotate datasets effectively to ensure accurate and meaningful results.

#### skills:
- Dataset building
- Data fit & annotation
- Data cleaning
- Job design
- CML
- Result auditing
- Planning for failure & longevity


### 🧠 Building Models

This module introduces us to the process of training and evaluating neural networks, which are at the heart of many AI technologies. We also learn about automated machine learning tools that can simplify and accelerate the model-building process.

### 📈 Measuring Impact and Updating Models

In the final part of the course, we learn how to improve machine learning models and AI products. We discuss strategies to mitigate bias and explore how to scale AI/ML products. The module also covers the importance of continuously updating models to ensure they remain effective and relevant.

<br>

## Course Projects 🏗️

### 🩻 Create a Medical Image Annotation Job

Project Overview
Your goal, as a product owner is to build a product that helps doctors quickly identify cases of pneumonia in children. You'll want to build a classification system that:
- Can help flag serious cases
- Quickly identify healthy cases
- And, generally, act as a diagnostic aid for doctors
As such, this project is designed to test your ability to build a labeled dataset that distinguishes between healthy and pneumonia x-ray images; this can be used by ML engineers later on down the line to build a classification product. Your main task will be to create a data labeling job.

##### The Data
[Chest x-ray dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia), with labels removed. Every piece of data is a chest x-ray image. You may see images taken that are slightly different in size and taken under slightly different exposure times. A typical, labeled image is shown below:

TODO -->


A labeled, healthy, chest x-ray image. Pay close attention to the two lungs and diaphragm (below the lungs).
What Does Pneumonia Look Like?
This is a challenging task because it is not always clear when pneumonia symptoms are present or not in an image. As such, your system is not meant to be a replacement for a doctor, only to aid in quickly identifying healthy patients and surfacing potential cases of pneumonia.

You should design a data annotation job, such that a non-expert can identify more noticeable cases of pneumonia. Since you are designing for a non-expert annotator, you should design for failure; this means including some way to capture uncertainty in your data labels and test questions.
So, what indicates pneumonia and what kind of advice and examples can we give potential annotators?
There are a few different visual symptoms that indicate pneumonia. The most important areas to have annotators pay attention to are the lungs and the diaphragm.

A normal, healthy image will depict clear lungs without any areas of abnormal cloudiness/opacity; there may be structured, web-like vasculature in the lungs but otherwise that area should be clear. In healthy images, you are also more likely to see a diaphragm shadow.
A pneumonia image may include a few things: areas of cloudiness/opacity in several concentrated areas or one large area. You may also see a general pattern of opacity that obscures the structure of the lungs, heart and diaphragm.

Some characteristics of a healthy image: a clear lung area.

Examples of pneumonia symptoms: (Left) a concentrated, opaque area in the lungs, (Right) multiple, smaller opaque areas throughout the lung area and any diaphragm shadow is obscured.
Note: You may download the above images for use in your annotator Instructions, if you want to.
Designing a Data Labeling Job
One of your biggest tasks will be to design an appropriate data labeling job using Appen's platform. You will need to submit an HTML file of a complete job Preview, which includes: 1. Instructions for annotation and 2. Example test questions. You will also need to submit a Proposal document that discusses the design of the job and steps you'll take for quality assurance.

You will not need to launch the annotation job; you are only creating one to demonstrate your ability to create a dataset.

Good Annotator Instructions (Handling Uncertainty)
This is a very challenging classification task and so you should provide clear examples and instructions to potential annotators.

You may choose to have annotators try to label an image as pneumonia or not (binary classification); if this is the case, you should include an Unknown or Other option to account for uncertainty in an annotation.
You may also choose to have annotators describe how likely they think a case of pneumonia is in a given image, and you could measure this on a numerical scale; 0-n for their confidence that an image contains pneumonia symptoms or not. A scale like this automatically includes room for low-confidence and uncertainty.
In your Proposal document, you will discuss your design choices and methods for quality assurance.
It is suggested that you start with an Appen job-template, and customize it to this particular task. And you can read more about the platform, next.



