🧠 Multi-Class Image Classification using CNN
📌 Overview

This project implements a Convolutional Neural Network (CNN) to perform multi-class image classification across 6 categories. The model learns hierarchical visual features such as edges, textures, and complex object patterns to accurately classify images.
The project covers the complete deep learning workflow including data preprocessing, model building, training, evaluation, and optimization, making it a strong end-to-end AI/ML portfolio project.

🚀 Key Features
✅ Custom CNN architecture built using TensorFlow and Keras
✅ Multi-class classification (6 classes)
✅ Data augmentation for improved generalization
✅ Dropout regularization to reduce overfitting
✅ Early stopping for optimal training
✅ Evaluation using accuracy, precision, and recall

🏗️ Model Architecture
The CNN model is designed with increasing feature complexity:

🔹 Feature Extraction Layers
Conv2D (32 filters) + ReLU + MaxPooling
Conv2D (64 filters) + ReLU + MaxPooling
Conv2D (128 filters) + ReLU + MaxPooling
Conv2D (256 filters) + ReLU + MaxPooling
🔹 Classification Layers
GlobalAveragePooling2D
Dense (128 neurons, ReLU)
Dropout (regularization)
Output Layer (6 neurons, Softmax)

👉 This design helps in learning both low-level and high-level visual features efficiently.

📊 Training Results
Metric	Value
Training Accuracy	~80–82%
Validation Accuracy	~82–83% (Best)
Precision	~85%
Recall	~80%

📌 Observations
The model achieved strong generalization performance
Best performance observed around Epoch 7
Some fluctuations in validation loss indicate mild overfitting

⚠️ Challenges Faced
Initial overfitting (high training accuracy, low validation accuracy)
Unstable validation loss in some epochs
Sensitivity to dataset size and augmentation strategies

🛠️ Solutions Implemented
✅ Applied Dropout (0.5–0.7) to reduce overfitting
✅ Used Data Augmentation (rotation, zoom, flipping)
✅ Implemented EarlyStopping to capture best model
✅ Tuned architecture and training parameters

📈 Evaluation Metrics Explained
Accuracy → Overall correctness of predictions
Precision → Out of predicted positives, how many are correct
Recall → Out of actual positives, how many were detected

