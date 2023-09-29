# Mango Disease Classifier

Welcome to the Mango Disease Classifier! This web application is designed to help you classify mangoes as either healthy or diseased based on uploaded images. Whether you are a mango enthusiast or a farmer looking to detect diseases early, this tool can assist you in identifying potential issues with mangoes.

## How to Use

Upload an Image: To get started, click the "Upload an image" button. You can upload images in JPG, PNG, or JPEG formats.

## Prediction

Once you upload an image, our model will analyze it and classify the mango as either "Healthy" or "Diseased." The result will be displayed below the uploaded image.

## Disease Classes

The model can classify mangoes into the following categories:

Anthracnose: Disease
Bacterial Canker: Disease
Cutting Weevil: Disease
Die Back: Disease
Gall Midge: Disease
Healthy: Healthy
Powdery Mildew: Disease
Scooty Mould: Disease
Technical Details
This application is built using Streamlit, a Python library for creating web applications with minimal code. It utilizes a pre-trained deep learning model to make predictions on uploaded images.

The model used in this application is loaded from the "final_model\mango_leaf_disease_ResNet50.h5" file. 
It has been trained to recognize various diseases that affect mangoes and determine if a mango is healthy or diseased.

## About Mango Diseases

Mangoes are susceptible to various diseases that can affect their growth and quality. Early detection of diseases can be crucial for farmers to take preventive measures and ensure a healthy mango harvest.

## Acknowledgments

The model used in this application was trained on a dataset of mango images.
Enjoy using the Mango Disease Classifier! If you have any questions or feedback, please don't hesitate to reach out.





