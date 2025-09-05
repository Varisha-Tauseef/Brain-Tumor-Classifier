# Brain Tumour Classifier

This project implements a **CNN-based Brain Tumour Classifier** that classifies brain MRI images into different tumour types.

## Overview
- The notebook trains and evaluates three models (Custom CNN, MobileNetV2, and EfficientNet) for brain tumour classification. Users need a Kaggle account and must download their Kaggle API token. Once the token is uploaded to the notebook, the dataset is automatically downloaded from Kaggle, and all preprocessing, training, and evaluation steps for all models run without interruptions.

## How to Use
1. Open the notebook in Jupyter or Google Colab.
2. Run all cells. The third cell will prompt you to upload your Kaggle API token.
3. After uploading the token, the notebook will access the dataset and execute all remaining steps automatically for all three models.
4. The notebook will train and evaluate all models, producing results such as accuracy, loss, confusion matrices, and classification metrics for comparison.
