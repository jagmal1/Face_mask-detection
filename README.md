# Helmet-detection
Helmet Detection System 
Introduction
This project implements a neural network-based system to detect whether a person is wearing a face mask. It leverages image preprocessing and classification techniques to distinguish between two classes:

With helmet
Without helmet

Features
Dataset Preparation: Image resizing, labeling, and conversion to a unified format.
Neural Network: A custom-built model for accurate classification.
Predictive System: Real-time or batch prediction capabilities for processed images.

Prerequisites
Python 3.x
Libraries: TensorFlow, NumPy, OpenCV, Matplotlib, etc. (full requirements provided in the requirements.txt)

Installation
Clone this repository:
git clone https://github.com/your-username/face-mask-detection.git
cd face-mask-detection

Install dependencies:
pip install -r requirements.txt

Usage
Prepare your image dataset in the required format (as described in the notebook).
Train the model:
bash
Copy code
python train_model.py
Use the predictive system:
bash
Copy code
python predict.py --image_path /path/to/image.jpg

Results

The trained model achieves high accuracy in detecting face masks, making it suitable for real-world applications like security systems and healthcare monitoring.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

License
This project is licensed under the MIT License.
