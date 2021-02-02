# Diagnosing Pneumonia
Reducing Costs in Healthcare - Project 2

# Team Members
Eli Holden,
Valentina Buritica,
Fazle Hameem,
Emmanuel Korlewala,
Matthew Musgrave

# Project Summary

In order to reduce costs associated with diagnosing pneumonia, a deep learning machine model was built to evaluate x-ray images and predict, with a high degree of accuracy, whether or not the patient has pneumonia. This is a highly relevant application given the prominence of pneumonia today brought on by COVID-19. The team also conducted research to identify at risk countries that experience a greater percentage of pneumonia today. The Deep Learning Model that the team developed is a Convolutional Neural Netowrk (CNN) deep learning model that is able to analyze images and make predictions based on key attributes within that image. This is a supervised model that is trained by evlauating x-ray images of normal lungs and lungs with pneumonia.

# Model Summary

The Convolutional Neural Network (CNN) is a supervised learning algorithm that learns characteristics of an image and then can predict outputs of new images that are passed through the model. See below details of how to run the model:

* The data/images used to train the model were pulled form a public repository from Kaggle that contained x-ray images showing normal lungs and lungs with pneumonia.

* The trained model is titled "advanced_100_model-1-20-21." This will be the model that is loaded into a new jupyter notebook where an x-ray image can be loaded and run through the model in order for the model to predict whether or not the image shows lungs with pneumonia or not.

* The Jupyter Notebook titled "Model.ipynb" shows the steps that were taken to train the model to identify key attributes within the x-ray images that would identify whether or not the image shows a set of lungs with pneumonia. The pseudocode within that file describes how the model was trained and what the inputs were.

# Cost Analysis

We peformed an analysis using a variety of healthcare data in order to determine how our model could be deployed to save money in regions that are disproportionately affected by pneumonia. That analysis and detail is contained within the Jupyter Notebook file titled "Financial_Aspect.ipynb" Our conclusions were drawn from extrapolationg the costs of diagnosing pneumonia, in the traditional sense, vs. utilizing our model which would be distributed for free.

# Heatmap Visual

In order to model how the CNN evaluates images to make predicitons, we worked to develop a visual representation in the form of a heatmap that shows how the CNN focuses on key aspects of an image to make predictions. See the document titled "heatmap_analysis.ipynb" which includes the code that was developed in order to create a visual representation of the CNN in action. Instructions for how to run the code are pseudocoded within the notebook file.

# Lex ChatBot

In light of the pandemic, we created a chatbot using Amazon Lex and Lamabda to create a chat bot that consumes various patient data and x-ray images to help diagnose whether or not the patient has Penumonia or not. The Lex files are within the "Amazon Lex Bot" folder that is saved within the project 2 Github repository.

**Amazon Lambda Function:**
project_two_lambda_function.ipynb

**Exported Bot:** 
PneumoniaAdvisor_Export.json

**Exported Intent:** 
MedicalRecommendation_Export.json

**Exported Slots:** 
coronavirus_Export.json, covid_risk_Export.json, travel_Export.json, x_rays_Export.json, highRisk_Export.json, second_highRisk_Export.json, third_highRisk_Export.json, fourth_highRisk_Export.json, 

