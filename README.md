# Early detection of Alzheimer’s disease: Deep Learning approach

# Abstract
With the aim of improving the early detection of Alzheimer’s disease, this article focuses on the use of advanced algorithms, such as Deep Learning, to analyse large amounts of image data. To achieve this goal, the article proposes using a Convolutional Neural Network (CNN) model, which is a type of Deep Learning algorithm that excels in image analysis. By training a CNN on a large dataset of medical images, the model can learn to automatically identify patterns and features that are indicative of Alzheimer’s disease. The ultimate goal is to develop a web application that can detect Alzheimer’s disease in its early stages with high accuracy.

# Design
In the context of detecting Alzheimer’s disease, Computer Vision, Image Classification and Deep Learning come together by using Convolutional Neural Networks to classify brain MRI scans to predict the presence/absence of Alzheimer’s disease.

### Dataset
The dataset comes from [Kaggle](https://www.kaggle.com/datasets/sachinkumar413/alzheimer-mri-dataset) and consists of 6400 pre-processed brain MRI images:

**Class - 1**: *Mild Demented* (896 images)

**Class - 2**: *Moderate Demented* (64 images)

**Class - 3**: *Non Demented* (3200 images)

**Class - 4**: *Very Mild Demented* (2240 images)


### Tools
`os` and `cv2` are used for image processing and handling;

`matplotlib` and `seaborn` are used for data visualization;

`sklearn` is used for machine learning algorithms;

`tensorflow` and `keras` are used for building and training deep learning models;

`streamlit` is used for creating web-based applications to visualize and interact with the trained models.

### Streamlit App
After training and evaluating our model, we deploy it in a Streamlit App that allows users to upload brain MRI scans and obtain predictions on whether the patient has Alzheimer’s disease.

[You can try the App here](https://ismailhuseynov-alzheimer-s-detection-appmy-test-app-wvmbiy.streamlit.app/)


Thank you for your interest in our article "On the early detection of Alzheimer's disease using a Deep Learning approach". You can access the article through the following link, which is published on Medium.com:

https://medium.com/@ismailhuseynov6666/early-detection-of-alzheimers-disease-deep-learning-approach-b96378e4a904

We value your feedback and would be grateful to hear your thoughts on our research.
