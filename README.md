# Brain Tumor Detection Using CNN

This project is a deep learning-based solution to detect brain tumors from MRI images using Convolutional Neural Networks (CNNs) in TensorFlow/Keras.

## 📁 Dataset Structure

Place your dataset in the following format under `brain_tumor_dataset/`:

brain_tumor_dataset/
├── yes/
│ ├── image1.jpg
│ ├── image2.jpg
│ └── ...
└── no/
├── image1.jpg
├── image2.jpg
└── ...

markdown
Copy
Edit

## 🚀 How to Run

1. Clone this repository or download the files.
2. Ensure you have Python 3.7+ installed.
3. Install required packages:
   ```bash
   pip install -r requirements.txt
Open and run the brain_tumor_from_images.ipynb notebook.

📊 Features
Trains a CNN model on grayscale MRI images.

Uses ImageDataGenerator for data loading and augmentation.

Visualizes training accuracy and confusion matrix.

🧠 Model Architecture
Convolutional layers: 2

Pooling layers: 2

Dense layers: 2

Dropout: 0.5

Activation functions: ReLU, Sigmoid

📦 Dependencies
See requirements.txt
