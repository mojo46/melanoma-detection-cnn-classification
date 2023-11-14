# Project Name
> Skin Cancer Detection Project


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The project focuses on building a convolutional neural network (CNN) to accurately detect melanoma, a type of skin cancer.
- The dataset consists of 2357 images of malignant and benign oncological diseases, categorized into nine classes.
- The goal is to create a robust CNN model for early detection of melanoma, reducing manual effort in diagnosis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model Building & Training: A custom CNN model was built and trained for approximately 20 epochs. The model was evaluated for evidence of overfitting or underfitting.

- Data Augmentation: To address overfitting/underfitting, an appropriate data augmentation strategy was chosen. The model was trained on augmented data for another 20 epochs.

- Class Distribution: The class distribution in the training dataset was examined to identify the least and dominant classes.

- Handling Class Imbalances: Class imbalances were rectified using the Augmentor library. The model was rebuilt and trained on the balanced dataset for around 30 epochs.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

- TensorFlow - version 2.0

- Python - version 3.8

- Augmentor - version 0.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by the need for an effective solution for melanoma detection.

- References: The project implementation followed guidelines and concepts from the TensorFlow documentation and related literature.

## Contact
Created by [@mojo46] - feel free to contact me!

