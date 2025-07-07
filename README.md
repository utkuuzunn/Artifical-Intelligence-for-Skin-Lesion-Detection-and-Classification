# Artificial Intelligence for Skin Lesion Detection and Classification

This project presents a deep learning-based approach for the detection and classification of skin lesions using Convolutional Neural Networks (CNNs). The model was trained and tested on the HAM10000 dermatological image dataset, which contains high-resolution dermatoscopic images labeled across seven skin lesion categories. Leveraging the ability of CNNs to extract spatial features from images, the model learns to distinguish between different types of lesions, contributing to improved diagnostic accuracy. The entire pipeline—from data acquisition and preprocessing to training and evaluation—was implemented in Python and executed on Google Colab. Performance was assessed using standard metrics such as accuracy, precision, recall, and F1-score, indicating the model’s potential to support clinical decision-making in dermatology.

## Dataset

[HAM10000 - Kaggle Dataset](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)

## Skin Lesion Categories

The dataset includes seven types of skin lesions, each annotated as either benign or malignant:

| Label   | Description                                  | Type       |
|---------|----------------------------------------------|------------|
| akiec   | Actinic keratoses and intraepithelial carcinoma | Malignant  |
| bcc     | Basal cell carcinoma                         | Malignant  |
| bkl     | Benign keratosis-like lesions (e.g. seborrheic keratosis, solar lentigo) | Benign     |
| df      | Dermatofibroma                               | Benign     |
| mel     | Melanoma                                     | Malignant  |
| nv      | Melanocytic nevi (common moles)              | Benign     |
| vasc    | Vascular lesions (e.g. angiomas, hemangiomas) | Benign     |


## How to Run

1. Open the notebook in Google Colab.  
2. Run the first cell to automatically download the dataset from Kaggle (Kaggle API key setup required).  
3. Continue executing the notebook cells to perform data preprocessing, model training, and evaluation.

> Note: To access the dataset programmatically, you must have a Kaggle account and upload your `kaggle.json` API key to Colab.

## Evaluation Metrics

The model’s performance was evaluated using the following metrics:

- **Accuracy:** 0.9123
- **Precision (Weighted):** 0.9056
- **Recall (Weighted):** 0.9123
- **F1-Score (Weighted):** 0.9089


## Repository Contents

- `Skin-Lesion-Detection-and-Classification.ipynb`: Main Jupyter Notebook containing the full workflow including data loading, preprocessing, model building, training, and evaluation.

