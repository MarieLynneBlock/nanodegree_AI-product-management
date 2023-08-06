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

### 🩻 Project: Create a Medical Image Annotation Job

In this project, we designed a product aimed at assisting doctors in quickly identifying cases of pneumonia in children. The goal was to develop a classification system that could:

- Flag serious cases
- Quickly identify healthy cases
- Act as a diagnostic aid for doctors

We started by building a labeled dataset capable of distinguishing between healthy and pneumonia x-ray images. This dataset would later serve as a foundation for machine learning engineers to construct a classification product.

We used the [Chest x-ray dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia), with labels removed, and every data point is a chest x-ray image. The images vary in size and exposure times.

<div align="center">
  <p>A typical, labeled image is shown below:</p>
  <img src="images/annotated-chest-xray.png" alt="healthy annotated-chest-xray example" width="500">
</div>

<br>

The challenge in this project lies in the fact that it is not always clear when pneumonia symptoms are present in an image. Thus, the system is not intended to replace a doctor, but rather to aid in quickly identifying healthy patients and highlighting potential cases of pneumonia.

To address this challenge, we designed a data annotation job suitable for a non-expert to identify more noticeable cases of pneumonia. We planned for uncertainty in data labels and incorporated test questions to capture this uncertainty.

Below are some visual examples demonstrating the characteristics of a healthy image and symptoms of pneumonia:

<div align="center">
  <p>Characteristics of a healthy image: a clear lung area.</p>
  <img src="images/healthy-example.png" alt="healthy xray example" width="500">
</div>

<br>

<div align="center">
  <p>Examples of pneumonia symptoms: (Left) a concentrated, opaque area in the lungs, (Right) multiple, smaller opaque areas throughout the lung area and any diaphragm shadow is obscured:</p>
  <img src="images/pneumonia-examples.png" alt="pneumonia xray examples" width="1000">
</div>

<br>

Our main deliverables for this project were an HTML file of a complete job Preview, which includes instructions for annotation and example test questions, and a Proposal document discussing the job's design and quality assurance steps.

In our annotator instructions, we acknowledged the challenging nature of the classification task and provided clear examples and instructions to potential annotators. We offered an 'Unknown' or 'Other' option to account for uncertainty in an annotation and allowed annotators to indicate their confidence level in the presence of pneumonia symptoms on a numerical scale.

This project was a valuable experience in dataset creation, annotation job design, handling uncertainty, and planning for quality assurance.
