# Image Recognition for Disease Diagnosis

The project aims to develop a system for image recognition to aid in the diagnosis of various diseases. The system will utilize machine learning algorithms to analyze medical images, such as X-rays, MRIs, and CT scans, and identify patterns or abnormalities indicative of specific diseases or conditions. This technology has the potential to assist healthcare professionals in making more accurate and efficient diagnoses, ultimately improving patient outcomes. The project will involve data collection, algorithm development, and validation through clinical trials to ensure the accuracy and reliability of the system.


This is a high-level introduction into practical machine learning for purposes of medical image classification. 


In this project, we use the Tensorflow framework as it is currently the most actively used and the Keras library, which a high-level application programming interface that simplifies working with Tensorflow.


The Jupyter ipython notebook code is called "HelloWorldDeepLearning.ipynb"

We provide ( 75 images, 38 are chest X-rays, and 37 are abdominal X-rays ). These de-identified PNGs obtained from openI, https://openi.nlm.nih.gov/, a searchable online repository of medical images from published PubMed Central articles

The goal of this project is to build a deep learning classifier to accurately differentiate between the two.

The needs are : a computer with the following installed:

1) Tensorflow (https://www.tensorflow.org)
2) Keras library (https://keras.io)
3) Jupyter (http://jupyter.org)
4) Download the x-rays provided in .zip file 

To make things easier, there is a convenient SIIM docker that has Tensorflow / Keras / Jupyterlab already installed, located here: https://github.com/ImagingInformatics/machine-learning/tree/master/docker-keras-tensorflow-python3-jupyter


 More details and a step-by-step guide for the project can be found in the Journal of Digital Imaging Publication, which is the official journal of the Society of Imaging Informatics in Medicine (SIIM).
