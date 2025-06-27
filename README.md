# Soc
Summer of code 25
Digit Recognition using CNN

This project implements a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset using TensorFlow and Keras.

Dataset

MNIST: 70,000 grayscale images (28x28 pixels) of digits 0 through 9
Split into:
60,000 training images
10,000 testing images
Model Architecture

Conv2D (32 filters, 3x3) + ReLU
MaxPooling2D (2x2)
Conv2D (64 filters, 3x3) + ReLU
MaxPooling2D (2x2)
Flatten
Dense (128) + ReLU
Dense (10) + Softmax (for 10 digits)
Results

Accuracy after 5 epochs: ~98% on validation and test set
Run the Code

Install requirements:

pip install -r requirements.txt
Run the script:

python main.py
Sample Output

The script displays the first few predictions with the actual labels and the predicted digit.

Requirements

See requirements.txt, or use:

pip install tensorflow matplotlib

