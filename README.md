# COVID-19 Chest X-ray Classification

This repository contains code for classifying chest X-ray images using deep learning models. The project uses the [COVID-19 Radiography Database](https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database) from Kaggle and implements two models:
- A custom Convolutional Neural Network (CNN)
- A pretrained ResNet-18 (from torchvision)

## 📂 Dataset

The dataset used is the COVID-19 Radiography Database from Kaggle, which includes X-ray images categorized into:
- COVID
- Normal
- Viral Pneumonia
- Lung Opacity

Download it manually from Kaggle or use `kagglehub`:
```python
from kagglehub import dataset_download
path = dataset_download("tawsifurrahman/covid19-radiography-database")
