# Skin Cancer Detection Using ResNet
This project focuses on detecting skin cancer using the ResNet (Residual Neural Network) architecture. Skin cancer is a common and potentially deadly disease, and early detection is crucial for effective treatment. The dataset used for this analysis consists of images of skin lesions, and the goal is to classify these images into different types of skin cancer using deep learning techniques.

## Dataset

The dataset used for this project is sourced from [ https://www.kaggle.com/datasets/fanconic/skin-cancer-malignant-vs-benign]. It contains images of skin lesions, along with corresponding labels indicating the type of skin cancer present in each image.

## Project Workflow

1. **Data Preprocessing**
   - Loading and preprocessing the image data.
   - Augmenting the images to increase the diversity of the dataset.

2. **Model Architecture**
   - Building the ResNet model with the following layers:
     - Convolutional layers with ReLU activation.
     - Batch normalization layers.
     - Residual blocks for learning residual functions.

3. **Model Training**
   - Compiling the model with appropriate loss function and optimizer.
   - Training the model on the training data.

4. **Model Evaluation**
   - Evaluating the model on the test data to determine its accuracy and performance.
   - Generating a confusion matrix to visualize the model's performance.

## Tools and Technologies

- **Python Libraries:** TensorFlow and Keras for building and training the model.
- **Image Processing Libraries:** OpenCV for image loading and preprocessing.
- **Model Visualization:** Matplotlib for visualizing model performance.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/skin-cancer-detection.git
