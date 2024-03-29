# WILDLIFE ALERTING SYSTEM
In the realm of computer vision, this project presents a comprehensive solution for image classification, specifically focusing on the detection of humans in wildlife areas and the identification of diverse animals. The models are carefully crafted to address unique challenges associated with human and animal detection in natural environments. The integration of both models is facilitated through the Gradio library, offering an intuitive and interactive interface for users.
# About the models and interface
# Human Detection Model
The human detection model is trained on a dataset specifically curated for wildlife scenarios. It leverages the MobileNetV2 architecture, a lightweight and efficient convolutional neural network (CNN). The model's pre-trained weights from the ImageNet dataset enable it to capture relevant features, while fine-tuning ensures adaptability to the challenges posed by wildlife environments.

# Animal Detection Model
The animal detection model also employs the MobileNetV2 architecture, benefiting from its real-time capabilities and strong performance in image classification tasks. Pre-trained on the ImageNet dataset, this model is capable of recognizing a wide array of animals. A carefully curated list of animal labels enhances the model's precision in identifying specific species.

# Integrated Gradio Interface:
The Gradio library serves as the backbone for seamlessly combining both human and animal detection models into a unified interface. This interface allows users, including wildlife researchers, conservationists, and enthusiasts, to effortlessly upload images and receive instant feedback on the presence of humans and the identification of animals. The integration aims to democratize access to advanced computer vision capabilities and make them accessible to a broader audience.

# OneAPI

# Introduction

![WhatsApp Image 2024-01-31 at 14 05 04](https://github.com/sabarna06/Wildlife-Alerting-System/assets/155043288/7f88bae9-5c42-4ead-99e8-02bd0c54d3a3)


Before executing the code These commands will ensure that your environment has the necessary libraries installed for the provided code to run successfully.

!pip install gradio

import gradio as gr

import cv2

import numpy as np

import tensorflow as tf

from tensorflow.keras.applications import MobileNetV2

from tensorflow.keras.preprocessing.image import img_to_array


Wildlife Alerting System - Workflow

# Prerequisites:

* Python Environment:

Ensure that you have Python installed on your system. You can download it from python.org.
Recommended Python version: 3.6 or above.
* Jupyter Notebook:

Install Jupyter Notebook for an interactive development environment. You can install it using:
bash
Copy code
pip install notebook
* Required Python Libraries:

Install the necessary Python libraries using the following commands:
bash
Copy code
pip install opencv-python
pip install gradio
pip install tensorflow
pip install scikit-learn
pip install matplotlib
* Kaggle Account:

Create an account on Kaggle (https://www.kaggle.com/).
Generate an API key on Kaggle: Navigate to your Kaggle account settings, scroll down to the API section, and click "Create New API Token." Save the kaggle.json file that is downloaded.
* Google Colab (Optional):

If you plan to run the code on Google Colab, ensure you have a Google account.
Upload your kaggle.json file to your Google Colab environment.
Dataset:

Download the wildlife dataset (human-detection-dataset.zip) from Kaggle: Wildlife Dataset.
Extract the contents of the ZIP file.
* Additional Setup (if using Colab):

Run the provided code snippets for uploading kaggle.json and installing required packages.
Data Preprocessing and Model Training:

* Load and Preprocess Data:

Follow the provided code to load and preprocess the wildlife dataset. Adjust file paths accordingly.
* Human Detection Model:

Train the human detection model using the provided code snippets.
Evaluate the model's accuracy and save the trained model.
* Animal Detection Model:

If you have a separate dataset for animal detection, follow similar steps to train the animal detection model.
Evaluate and save the animal detection model.
* Gradio Setup:

Install Gradio:

Install Gradio using the command:
bash
Copy code
pip install gradio
* Gradio Interface:

Load the trained human detection and animal detection models.
Create a Gradio interface for interactive predictions.
Launch Gradio Interface:

Launch the Gradio interface and test the wildlife alerting system interactively.
* Running the Code:

Execute Steps:

Execute the Kaggle setup steps to download and preprocess the dataset.
Run the Data Preprocessing and Model Training steps for both human and animal detection models.
* Gradio Interface:

Run the Gradio Setup steps to set up the web interface.
Execute the Gradio interface to make predictions interactively.
Ensure to adapt the code and file paths based on your project structure a

Welcome to our advanced Human and Animal Detection project, where we seamlessly integrate the oneAPI AI Analytics Toolkit, specifically leveraging the oneDAL (Data Analytics Library) for optimizing our machine learning models. This project encompasses two distinct models: one designed for detecting the presence of humans in wildlife areas, and another tailored for identifying various animals. The integration of the oneAPI AI Analytics Toolkit enhances the overall performance and efficiency of our models.
# Prerequisites:
# Intel oneAPI Toolkit 
Download and install the latest version of the Intel oneAPI Toolkit.
# Python Environment
Set up a Python environment with the required packages.
# Kaggle API Key
Obtain a Kaggle API key and upload it.
Integration with oneAPI AI Analytics Toolkit
Human Detection Model Optimization
# Include oneDAL Library
Integrate the oneDAL library into the human detection model code. This involves importing oneDAL and updating the code to leverage its APIs.

# Optimized Computations:
Utilize oneDAL for low-level compute optimizations, enhancing the performance of key data processing tasks.

# Parallel Processing with DPC++
Leverage the Data Parallel C++ (DPC++) programming model provided by oneAPI for parallel processing across CPUs, GPUs, and accelerators.

# Memory Optimization:
Implement memory optimization strategies supported by oneDAL, including efficient data layout, minimized data movement, and cache-friendly data structures

# Benefits of Integration
Accelerated Processing: Enjoy accelerated data processing tasks, resulting in faster model execution.

# Resource Optimization
Optimize resource usage, leading to improved performance without compromising accuracy.

# Ease of Implementation
Seamless integration of oneDAL APIs provides a user-friendly solution for enhanced functionality.

# Parallel Processing Capabilities
Leverage the parallel processing capabilities of oneDAL for efficient computation across diverse hardware architectures.

# Conclusion
By integrating the InteloneAPI Analytics Toolkit, we aim to enhance the efficiency and performance of our human and animal detection models. The seamless incorporation of oneDAL's capabilities underscores our commitment to utilizing cutting-edge technologies for optimal predictive accuracy. This integration exemplifies our dedication to staying at the forefront of advancements in data analytics and ensuring that our models operate efficiently and effectively in real-world scenarios.

# System Workflow
![VISUAL REPRESENTATION](https://github.com/sabarna06/Wildlife-Alerting-System/assets/155043288/a4058764-1be3-4932-b325-dc169978b986)

# Output 
# Human detection

<img width="1440" alt="Screenshot 2024-01-30 at 2 14 03 PM" src="https://github.com/sabarna06/Wildlife-Alerting-System/assets/155043288/256c3d57-b9a3-4cce-bc30-b796806b7183">

<img width="1440" alt="Screenshot 2024-01-30 at 2 04 52 PM" src="https://github.com/sabarna06/Wildlife-Alerting-System/assets/155043288/a7e45622-0350-43fa-90ba-4e44dae31a04">


# Animal detection

<img width="1440" alt="Screenshot 2024-01-30 at 8 36 34 PM" src="https://github.com/sabarna06/Wildlife-Alerting-System/assets/155043288/eeba9b5f-5cdd-4a22-8c13-8ac6f9484461">

<img width="1440" alt="Screenshot 2024-01-30 at 8 37 33 PM" src="https://github.com/sabarna06/Wildlife-Alerting-System/assets/155043288/e2fa2cc4-0479-4dd6-9b27-e47b1a3e1aef">

<img width="1440" alt="Screenshot 2024-01-31 at 1 53 56 PM" src="https://github.com/sabarna06/Wildlife-Alerting-System/assets/155043288/bfde7c93-d231-48f2-baa9-6d0b631c2f0f">



# PRESENTATION VIDEO
https://github.com/sabarna06/Wildlife-Alerting-System/assets/155043288/5641126c-888e-41ed-ad85-6d9bdfd8feea

# Future Development

By implementing the aforementioned code, a robust foundation for wildlife detection has been laid. Building upon this, the project can be extended to address critical scenarios such as animal and human intrusion detection in real-time. By integrating live video feeds into the system, the model can continuously analyze the incoming streams. In case of animal detection, immediate alerts can be disseminated to nearby villagers individually to ensure their safety, particularly in regions with wildlife proximity. Simultaneously, alerts can be routed to designated forest authorities or proctoring personnel who can take timely action to mitigate potential threats.

This dual-alert system serves a dual purpose: safeguarding human communities from unexpected wildlife encounters and facilitating wildlife conservation efforts by allowing swift responses to animal activities. The seamless integration of detection capabilities not only enhances the safety of local residents but also empowers wildlife conservationists with valuable insights. The project thus emerges as a versatile solution that contributes to the coexistence of humans and wildlife while fostering a proactive approach to conservation and safety measures.


