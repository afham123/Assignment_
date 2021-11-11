# Lung Cancer image classifier

We have taken this dataset from [kaggle](https://www.kaggle.com/andrewmvd/lung-and-colon-cancer-histopathological-images) consisting of 25000 images of lungs tissue cells. We are visualizing the Data and Processing for Tumor Detection in the lungs.  Our main goal is to predict to which class does the image belongs.

## Reason for choosing the dataset

Lung cancer is currently one of the most vital diseases in society, and patients are more likely to be cured if the disease is spotted earlier. This project will show the use of Machine Learning to be one of the efficient solutions in healthcare. Radiologists’ workloads have increased significantly in recent years. Some studies found that the average radiologist must interpret an image every 3-4 seconds to meet demand. So with the help of the ml algorithm, I have trained on previously captured radiographic images to recognize the early development of tumors in the lungs.

Algorithms have been trained to recognize complex patterns in radiographic imaging data. They can detect lung cancer from mammograms with remarkable accuracy. The model is showing an accuracy of 91%  and will help to provide diagnostic information 30 times faster than a human. This will also help to also decrease the need for biopsies. 

## About the dataset

This dataset contains 15,000 histopathological images with 3 classes. All images are 768 x 768 pixels in size and are in jpeg file format.
The images were generated from an original sample of HIPAA compliant and validated sources, consisting of 750 total images of lung tissue (250 benign lung tissue, 250 lung adenocarcinomas, and 250 lung squamous cell carcinomas) and 500 total images of colon tissue (250 benign colon tissue and 250 colon adenocarcinomas) and augmented to 25,000 using the Augmentor package.  
There are three classes in the dataset, each with 5,000 images, being:  
* Lung benign tissue
* Lung adenocarcinoma
* Lung squamous cell carcinoma

In this project, We will be using the deep learning neural network architecture to implement lung cancer image classification.
