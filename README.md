# Identification-of-Geometric-Shapes-and-Estimating-its-size-through-CNN-

# Overview
This project uses a Convolutional Neural Network (CNN) to classify images of geometric shapes: triangle, circle, square, and star. Built with TensorFlow and Keras, the model achieves high accuracy in shape classification.

# Data
Source: (https://www.kaggle.com/datasets/smeschke/four-shapes)
Shapes: Triangle, Circle, Square, Star
Image Size: 200x200 pixels, grayscale
# Model
Architecture: CNN with Conv2D, MaxPooling2D, Flatten, Dense layers, and Dropout
Optimizer: Adam
Loss Function: Categorical Crossentropy
Epochs: 30
Performance
Accuracy: 100% on validation set
Loss: Minimal
# Files
ttrained_model.h5: Trained model
Getting Started

# Clone the Repository:
git clone https://github.com/yourusername/your-repository.git
#Install Dependencies:
pip install tensorflow opencv-python-headless numpy pandas matplotlib plotly
Run the Model: Follow the scripts to preprocess data, train the model, and visualize results.
