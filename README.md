# Product Image Classifier

This project aims to classify product images into different categories using deep learning techniques. The classifier is designed to distinguish between different types of fashion items in images.

## Dataset

The dataset used for training and testing the classifier can be found [here](https://www.kaggle.com/datasets/vikashrajluhaniwal/fashion-images). Since the dataset is too large to include directly in this repository, please download it from the provided link.

## Project Overview

The project consists of two main parts: data organization and model training.

### Data Organization

The provided Python script (`organize_data.py`) organizes the dataset into separate folders for each class/category. The script assumes that the dataset is initially stored in a single folder and then organizes it into a structured format suitable for training the classifier.

### Model Training

The deep learning model is built using TensorFlow and Keras. The provided Python script (`train_model.py`) defines and trains a Convolutional Neural Network (CNN) model for classifying product images. It consists of several convolutional and pooling layers followed by fully connected layers for classification.

## Usage

1. Download the dataset from the provided link and place it in the appropriate location.
2. Organize the dataset using the `organize_data.py` script.
3. Train the classifier using the `train_model.py` script.
4. Use the trained model to classify product images.

## Output Example

![output](https://github.com/Mohammed20037/Product-Image-Classifier/assets/113844625/48e55c55-0df0-4121-8733-50f218a50ec2)


## Code Walkthrough

Watch the video below for a walkthrough of the code:

[![Code Walkthrough](video_thumbnail.png)](https://github.com/Mohammed20037/Product-Image-Classifier/assets/113844625/c9107cc2-199c-45fb-8b06-772a8c4b5d53)

## Dependencies

- Python 3.x
- TensorFlow
- Keras
- Matplotlib

## Acknowledgments

- Dataset: [Fashion Images Dataset](https://www.kaggle.com/datasets/vikashrajluhaniwal/fashion-images)
- Inspiration: This project was inspired by the need to classify fashion product images for various applications.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
