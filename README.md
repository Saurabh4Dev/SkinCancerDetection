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
1. Open **Saurabh_Pandey_nn.ipynb**.
2. Run each cell sequentially.

## Requirements:
- TensorFlow
- Keras
- Matplotlib
- Augmentor
- NumPy

## Conclusions
- Assignment uses a dataset of about 2357 images of skin cancer types.
- Assignment contains the images of 9 skin cancer types.
- Model suffers from class imbalance problem and thus need to use Augmentor library to generate extra images.
- Training and Validation accuracy improves after using augmented images.
- In notebook, the best performing model is Model 5(names as model_aug_with_dropout), which utilizes augmented images with dropout. It uses 6739 files belonging to 9 classes are present. It uses 5392 for training and 1347 files for validation.
- Original data uses 2239 files in training t=dataset belonging to 9 classes. Uses 1792 files for training and 447 files for validation.
- melanoma and pigmented benign keratosishas higher representation. dermatofibroma and seborrheic keratosis has less representation.
- Class distribution for original data set - actinic keratosis has 114 samples, basal cell carcinoma has 376 samples, dermatofibroma has 95 samples, melanoma has 438 samples, nevus has 357 samples, pigmented benign keratosis has 462 samples, seborrheic keratosis has 77 samples, squamous cell carcinoma has 189 samples, vascular lesion has 139 samples.
- Least Represented Class: seborrheic keratosis, Most Represented Class: pigmented benign keratosis.
- Number of overall samples has increased after application of Augmentor library
- Over all 6739 samples belonging to 9 classes are present,  It uses 5392 for training and 1347 files for validation, actinic keratosis has 614 samples, basal cell carcinoma has 876 samples, dermatofibroma has 595 samples, melanoma has 938 samples, nevus has 857 samples, pigmented benign keratosis has 962 samples, seborrheic keratosis has 577 samples, squamous cell carcinoma has 681 samples, vascular lesion has 639 samples.
- Read through comments in notebook for detailed description.
  
## Contact
Created by [@Saurabh4Dev] - feel free to contact me!
