# Skin Cancer Detection using CNN

## Overview
This project builds a **CNN model** to classify **9 types of skin cancer** using **deep learning techniques**.

## General Information
- This project focuses on developing a Convolutional Neural Network (CNN)-based model to accurately detect melanoma, a type of skin cancer that is highly fatal if not detected early. 
- Melanoma is one of the most dangerous types of skin cancer and accounts for 75% of skin cancer-related deaths worldwide. Early detection of melanoma greatly increases survival rates.
- Dermatologists rely on manual visual inspection and biopsy results for melanoma diagnosis, which takes time, delays critical treatment, requires expertise.
- Detection can be costly, especially in regions with limited healthcare facilities.
- The dataset used in this project is ISIC - The International Skin Imaging Collaboration Dataset: ISIC Skin Cancer Database.

## Solution
- Develop an AI-powered model that automatically analyzes skin lesion images and predicts whether a lesion is melanoma or benign
## Steps:
1. **Data Understanding**: Load and inspect the dataset. Uses Google Colab and Google drive for execution and storage of images.
2. **Dataset Creation**: Split into **train** and **validation** datasets.
3. **Data Visualization**: Display sample images from each class.
4. **Model Training**: Train a CNN model using image rescaling.
5. **Overfitting Handling**: Apply **Data Augmentation**.
6. **Class Imbalance Handling**: Use **Augmentor** library.
7. **Final Model Training**: Train a robust model for 30 epochs.
8. **Final Model Evaluation**: Evaluate best model for 30 epochs.

## How to Run:
1. Open **Saurabh_Pandey.ipynb**.
2. Run each cell sequentially.

## Requirements:
- TensorFlow
- Keras
- Matplotlib
- Augmentor
- NumPy

## Conclusions
- Assignment uses a dataset of about 2357 images of skin cancer types.
- Assignment contains the images of 9 skin cancer types respectively.
- Model suffers from class imbalance problem and thus need to use Augmentor library to generate extra images.
- Training and Validation accuracy improves after using augmented images.

## Contact
Created by [@Saurabh4Dev] - feel free to contact me!
