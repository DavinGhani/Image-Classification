# Shoe vs Sandal vs Boot Image Classification

This project focuses on classifying images of shoes into three categories: **Shoe**, **Sandal**, and **Boot**. The goal is to train a deep learning model to accurately classify images of footwear into one of these three categories.

## Project Overview

This project involves:
- **Image Classification**: Building a deep learning model to classify footwear images into Shoe, Sandal, or Boot categories.
- **Data Preprocessing**: Cleaning and transforming the raw image data into a format suitable for model training.
- **Model Training**: Training a convolutional neural network (CNN) or other machine learning models to classify footwear images.
- **Model Evaluation**: Evaluating the model's performance using accuracy, precision, recall, and F1 score.
- **Visualization**: Visualizing the results, including the model’s predictions and evaluation metrics.

### Dataset

The dataset used in this project contains labeled images of footwear, categorized into the following classes:
- **Shoe**: Images of standard shoes.
- **Sandal**: Images of sandals.
- **Boot**: Images of boots.

The dataset is used for training and evaluating the model.

- **Dataset Files**:
  - `[Proyek_Klasifikasi_Gambar_Submission_Akhir_[Davin].ipynb]`: Jupyter notebook for image classification, including data preprocessing, model training, and evaluation.

## Setup Instructions

Follow the steps below to get started with this project.

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/DavinGhani/Image-Classification
cd project-name
```

### 2. Install Dependencies
```
# Create a virtual environment (if you don't have one already)
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
