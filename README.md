# Malaria Detection System

## Overview
This project is a **Malaria Detection System** that classifies cell images as either **infected** or **uninfected** using deep learning. The model leverages **convolutional neural networks (CNNs)** trained on image datasets to automate malaria diagnosis.

## Dataset
The dataset is taken form kaggle where it consists of photos of FOV (Field of view ) of microscope lenses observing blood slides . These photos were taken using a mobie camera. There are around 3.9k images
Link for dataset:
```
/kaggle/input/lacuna-malaria-detection-dataset/Train.csv
/kaggle/input/lacuna-malaria-detection-dataset/Test.csv
```
It contains labeled images categorized as infected or uninfected.

## Features
- **Data Preprocessing**: Extracts image paths and checks for validity.
- **Image Augmentation**: Uses `ImageDataGenerator` to improve model performance.
- **Deep Learning Model**: Implements **VGG19-based CNN** for feature extraction.
- **Model Training**: Uses TensorFlow/Keras to train and validate the model.
- **Evaluation**: Measures accuracy and loss on test data.

## Technologies Used
- **Python**
- **TensorFlow & Keras** (for deep learning)
- **Pandas & NumPy** (for data handling)
- **Matplotlib** (for visualization)
- **PIL (Pillow)** (for image processing)

## Installation
Clone the repository:
```bash
 git clone https://github.com/yourusername/malaria-detection.git
 cd malaria-detection
```
Install dependencies:
```bash
pip install -r requirements.txt
```
Run the system:
```bash
jupyter notebook malaria-detection.ipynb
```

## Future Improvements
- Train on **larger datasets** for better accuracy.
- Implement **real-time image detection**.
- Deploy the model as a **web application or API**.

## License
This project is open-source under the **MIT License**.

