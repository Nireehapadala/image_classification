# image_classification
🖼️ Image Classification Using CNN
This project focuses on building a Convolutional Neural Network (CNN) to classify images into their respective categories using deep learning. It involves training the model on labeled image data and evaluating its accuracy using unseen test images.

🎯 Project Objective
To train a CNN model that accurately classifies images into predefined categories, demonstrating practical applications of computer vision in real-world tasks.

🧠 Technologies Used
Python

TensorFlow / Keras – model building and training

OpenCV / PIL – image handling

NumPy & Pandas – data preprocessing

Matplotlib – visualization

🗂️ Project Structure
✅ image_classification_training.ipynb
Loads and preprocesses image data

Builds a CNN model using Keras

Trains and validates the model

Uses ImageDataGenerator for data augmentation

📬 Contact Created by Nireeha Padala 
📧 [nireehap@gmail.com] 
🔗 [www.linkedin.com/in/nireeha-padala-6a71ab2a0] | [https://github.com/Nireehapadala]
Saves the trained model for testing

✅ image_classification_testing.ipynb
Loads the saved model

Tests the model on new or unseen images

Visualises prediction results

Prints class predictions with confidence scores

🧪 Model Architecture (Example)
Conv2D → MaxPooling

Conv2D → MaxPooling

Flatten → Dense → Dropout

Output Layer with softmax (for multi-class)

📊 Results
Achieved high validation accuracy (based on training log in your notebook)

Model generalises well to unseen images

Misclassified examples are visualised for analysis

📁 Dataset
Dataset is assumed to be organised in a directory structure like:

dataset/
  ├── train/
  │   ├── class1/
  │   ├── class2/
  ├── test/
  │   ├── class1/
  │   ├── class2/
You can replace class1, class2, etc., with your actual class names (e.g., cat, dog, etc.).

