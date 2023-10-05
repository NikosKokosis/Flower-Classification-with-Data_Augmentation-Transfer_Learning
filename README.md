# Flower Classification with CNN and Transfer Learning

## Project Overview

Welcome to the Flower Classification project! In this project, I've developed a cutting-edge flower classification system using Convolutional Neural Networks (CNNs) and Transfer Learning techniques. The goal of this project is to create a highly accurate model for classifying various flower species.

## Project Highlights

Here are the key highlights of this project:

- **Data Augmentation**: I employed Data Augmentation techniques to enrich the dataset, enabling the model to recognize flowers under various conditions, replicating real-world complexities.

- **Transfer Learning**: I fine-tuned a pre-trained Convolutional Neural Network (CNN) model to achieve state-of-the-art classification accuracy.

## Project Structure

This project consists of two main Jupyter Notebook files:

1. **[Data Augmentation](Code/Data_Augmentation.ipynbData_Augmentation.ipynb)**: This notebook covers the Data Augmentation process, where we enhance the dataset to improve model robustness.

2. **[Transfer Learning](Code/TransferLearning.ipynb)**: In this notebook, I implement Transfer Learning, fine-tuning a pre-trained CNN model for accurate flower classification.

## Conclusions

This project showcases the power of Convolutional Neural Networks (CNNs) and Transfer Learning in achieving remarkable accuracy in flower classification. The model's ability to recognize diverse flower species under various conditions makes it a valuable tool for botanists and flower enthusiasts.

## Dependencies

To run this project, you'll need the following libraries installed:

- [pathlib](https://docs.python.org/3/library/pathlib.html): Library for image processing and display.
- [cv2](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_gui/py_image_display/py_image_display.html): Library for computer vision tasks.
- [os](https://docs.python.org/3/library/os.html): Library for interacting with the operating system.
- [PIL](https://pillow.readthedocs.io/en/stable/index.html): Library for image processing and display.
- [collections.Counter](https://docs.python.org/3/library/collections.html#collections.Counter): Used for counting elements in the dataset.
- [tensorflow](https://www.tensorflow.org/): An open-source machine learning framework.

You can install these libraries using `pip`:

```bash
pip install pathlib opencv-python-headless Pillow tensorflow

## Download Dataset

The dataset used for this project can be found [here](https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz).