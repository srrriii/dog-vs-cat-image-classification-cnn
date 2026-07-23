# dog-vs-cat-image-classification-cnn
Deep Learning image classification project using Convolutional Neural Networks (CNNs) in TensorFlow to classify cat and dog images from the CIFAR-10 dataset.
🐶🐱 Dog vs Cat Image Classification using CNN
A Deep Learning project that classifies images as either Cat or Dog using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

The model is trained on filtered images from the CIFAR-10 dataset, demonstrating the complete image classification pipeline, including preprocessing, model training, evaluation, prediction, and visualization.

🚀 Features
Binary image classification (Cat vs Dog)
CIFAR-10 dataset preprocessing
Data normalization
CNN model built using TensorFlow/Keras
Model training and validation
Performance evaluation using accuracy
Single image prediction
Model saving for future inference
Visualization of sample images and predictions
🛠️ Technologies Used
Python
TensorFlow
Keras
NumPy
Matplotlib
📂 Project Structure
dog-vs-cat-image-classification-cnn/
│
├── dog_cat_classifier.py
├── dog_cat_cnn_model.h5
├── requirements.txt
├── README.md
├── .gitignore
└── assets/
    ├── sample_images.png
    ├── prediction.png
    └── training_accuracy.png
⚙️ Installation
Clone the repository:

git clone https://github.com/yourusername/dog-vs-cat-image-classification-cnn.git
Navigate to the project folder:

cd dog-vs-cat-image-classification-cnn
Install the dependencies:

pip install -r requirements.txt
▶️ Run the Project
python dog_cat_classifier.py
📊 Workflow
Load the CIFAR-10 dataset
Filter images to keep only Cats and Dogs
Normalize image pixel values
Build a Convolutional Neural Network
Train the model
Evaluate performance on the test set
Save the trained model
Predict the class of a new image
🧠 CNN Architecture
Layer	Details
Conv2D	32 Filters (3×3), ReLU
MaxPooling2D	2×2
Conv2D	64 Filters (3×3), ReLU
MaxPooling2D	2×2
Conv2D	64 Filters (3×3), ReLU
Flatten	Converts feature maps to vector
Dense	64 Neurons, ReLU
Output	1 Neuron, Sigmoid
📈 Evaluation
The model is evaluated using:

Binary Cross-Entropy Loss
Classification Accuracy
Example output:

Test Accuracy: 0.83
(Accuracy may vary depending on training.)

🔍 Sample Prediction
Input Image:

Cat Image
Prediction:

Predicted: Cat
Confidence: 0.12
🚀 Future Improvements
Train on the Microsoft Cats vs Dogs dataset
Apply data augmentation
Add dropout and batch normalization
Fine-tune with transfer learning (MobileNetV2, ResNet50, EfficientNet)
Hyperparameter tuning
Confusion matrix and classification report
Streamlit web interface
Flask/FastAPI deployment
TensorFlow Lite conversion for mobile devices
📚 Learning Outcomes
Image preprocessing
Convolutional Neural Networks (CNNs)
Binary image classification
TensorFlow & Keras
Deep Learning workflows
Model evaluation
Computer Vision fundamentals
📄 License
This project is licensed under the MIT License.
