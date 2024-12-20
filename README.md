# EARLY-PREDICTION-OF-PNEUMONIA-INFECTION-FROM-CHEST-X-RAY-IMAGES-USING-CNN

This project focuses on building a convolutional neural network (CNN) to detect pneumonia from chest X-ray images. The process begins with data preprocessing, where images from labeled categories ("PNEUMONIA" and "NORMAL") are resized and normalized to ensure uniformity. The dataset is divided into training, validation, and testing subsets for model development and evaluation.

A custom CNN model is designed for binary classification, consisting of convolutional layers for feature extraction, pooling layers for dimensionality reduction, and fully connected layers for prediction. The model is compiled using binary cross-entropy loss and the Adam optimizer, ensuring efficient training.

The system trains the CNN using the processed training data, validates its performance on unseen data, and evaluates accuracy on a test set. Once trained, the model is saved for future use. Key metrics like accuracy and loss are monitored during training and evaluation to ensure reliability.

Additionally, the project integrates a Streamlit-based web interface, allowing users to upload chest X-ray images for real-time pneumonia detection. The app preprocesses the uploaded images, runs predictions using the trained model, and provides diagnostic results with confidence scores, ensuring an accessible and user-friendly experience.
