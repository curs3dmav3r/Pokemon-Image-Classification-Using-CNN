# Pokemon-Image-Classification-Using-CNN

This project uses a Convolutional Neural Network (CNN) to classify Pokemon images. The goal is to build a model that can accurately predict the species of a Pokemon based on its image.

## Project Overview

In this project, a custom CNN model is trained to classify Pokemon images into their respective categories. The model is trained on a dataset of labeled Pokemon images, and we utilize image preprocessing techniques to ensure that the dataset is clean and ready for training.

### Features
- **Custom CNN architecture**: A Convolutional Neural Network (CNN) with multiple layers.
- **Image Preprocessing**: Includes image resizing, normalization, and RGB conversion.
- **Data Augmentation**: The model utilizes Keras' ImageDataGenerator for training and validation data splitting.
- **Model Checkpointing**: The best-performing model is saved during training.

## Requirements

To run this project, you'll need the following:

- Python 3.x
- TensorFlow
- Keras
- Matplotlib
- PIL (Pillow)
- Other dependencies specified in `requirements.txt`

### Installing Dependencies

You can install the required dependencies using pip. First, create a virtual environment (optional but recommended):

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
