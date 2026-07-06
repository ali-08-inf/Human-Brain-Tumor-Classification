{\rtf1\ansi\ansicpg1252\cocoartf2870
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 #  Dataset Information\
\
## Overview\
\
This project uses a publicly available Brain Tumor MRI dataset for multi-class image classification. The dataset consists of MRI scans categorized into four classes:\
\
-  Glioma\
-  Meningioma\
-  Pituitary Tumor\
-  No Tumor\
\
The dataset is used to train and evaluate a ResNet-18 model using transfer learning.\
\
---\
\
## Dataset Source\
\
**Name:** Brain Tumor MRI Dataset\
\
**Source:** Kaggle\
\
**Download Link:**\
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset\
\
---\
\
## Dataset Structure\
\
```text\
Brain-Tumor-MRI-Dataset/\
\uc0\u9474 \
\uc0\u9500 \u9472 \u9472  Training/\
\uc0\u9474    \u9500 \u9472 \u9472  glioma/\
\uc0\u9474    \u9500 \u9472 \u9472  meningioma/\
\uc0\u9474    \u9500 \u9472 \u9472  pituitary/\
\uc0\u9474    \u9492 \u9472 \u9472  notumor/\
\uc0\u9474 \
\uc0\u9492 \u9472 \u9472  Testing/\
    \uc0\u9500 \u9472 \u9472  glioma/\
    \uc0\u9500 \u9472 \u9472  meningioma/\
    \uc0\u9500 \u9472 \u9472  pituitary/\
    \uc0\u9492 \u9472 \u9472  notumor/\
```\
\
---\
\
## Usage\
\
1. Download the dataset from the Kaggle link above.\
2. Extract it into the project's `data/` directory.\
3. Update the dataset path in the notebook if necessary.\
4. Run the notebook to train and evaluate the model.\
\
---\
\
## Note\
\
The dataset is **not distributed with this repository**. Users are required to download it separately from the original source to comply with the dataset's licensing terms.}