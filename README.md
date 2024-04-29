# Digit Recognition

## Project Description
This project focuses on the recognition of handwritten digits using a machine learning model trained on the MNIST dataset. The core of the project is a Jupyter Notebook that guides users through the process of loading the dataset, preprocessing the images, training the model, and evaluating its performance. The implementation leverages popular Python libraries such as TensorFlow and Keras, making it an excellent resource for educational purposes and for those looking to start with machine learning applications.

## Features
- **Data Visualization**: Includes scripts to visualize the MNIST dataset images, providing insights into the dataset used.
- **Preprocessing Tools**: Implements image normalization and resizing to prepare data for model training.
- **Model Training**: Utilizes a convolutional neural network (CNN) architecture for effective learning of features from handwritten digits.
- **Evaluation Metrics**: Provides accuracy and loss metrics to assess model performance, along with confusion matrix visualization to understand classification errors.
- **Interactive Predictions**: Allows users to test the model with their own handwritten digit images.

## Installation

To set up this project locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/Gawad1/Digit-Recognition.git
cd Digit-Recognition

# Install required Python packages
pip install numpy pandas matplotlib jupyter tensorflow keras

#Run code
jupyter notebook Digit_Recognizer.ipynb
