# Medical Imaging: Pneumothorax Segmentation
This repository contains the project work for the "Medical Imaging" course as part of the Master of Science program in Data Science at Università degli Studi di Milano-Bicocca. The project utilizes deep learning techniques, specifically [U-Net](https://arxiv.org/abs/1505.04597) architectures, for segmenting pneumothorax from chest X-ray images, as part of the [SIIM-ACR Pneumothorax Segmentation competition](https://www.kaggle.com/competitions/siim-acr-pneumothorax-segmentation/overview).

Due to limited computational resources, the U-Net model was trained on half of the dataset, both with and without class balancing.

# Results Overview
Below are examples of the Ground Truth and the model's predictions before and after class balancing:
## Before Class balancing
**Groung Truth**
![image](https://github.com/user-attachments/assets/c8612969-4aca-41db-9182-36cdcafac051)

**Prediction**
![image](https://github.com/user-attachments/assets/fae79657-07cc-4320-b8e6-b2eb198b5f03)


## After Class balancing
**Groung Truth**
![image](https://github.com/user-attachments/assets/c8612969-4aca-41db-9182-36cdcafac051)

**Prediction**
![image](https://github.com/user-attachments/assets/906e681c-46ff-4a44-a134-544af0fc73db)
