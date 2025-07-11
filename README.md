## 🐾PawNet-Classifier
This project showcases how to classify images of dogs and cats using Transfer Learning with Keras. It demonstrates:

* Feature Extraction without Data Augmentation

* Feature Extraction with Data Augmentation

* Fine-Tuning for Improved Accuracy

## 🚀 Technologies Used
Python

TensorFlow / Keras

Matplotlib

Kaggle Dataset: Dogs vs. Cats

## 📂 Project Structure

📦 Dogs-vs-Cats-TransferLearning
 ┣ 📁 dataset
 ┣ 📁 saved_models
 ┣ 📄 feature_extraction_no_aug.ipynb
 ┣ 📄 feature_extraction_with_aug.ipynb
 ┣ 📄 fine_tuning.ipynb
 ┣ 📄 README.md
 ┗ 📄 requirements.txt
 
## 📌 Key Features
✅ Transfer Learning with pre-trained models (e.g., VGG16, ResNet50)
✅ Feature Extraction (with and without Data Augmentation)
✅ Fine-Tuning to boost accuracy
✅ Visualization of Training & Validation Loss/Accuracy

## How to Run
1. Clone this repository:
 git clone https://github.com/SpringPixels/PawNet-Classifier.git
 cd Dogs-vs-Cats-TransferLearning
 
2. Install required libraries:
pip install tensorflow matplotlib

3. Run the Jupyter notebooks step by step.

## 📊 Results
Approach	                            Validation Accuracy
Feature Extraction (No Augmentation)	   91%
Feature Extraction (With Augmentation)	 92%
Fine-Tuning	                             95%

## Acknowledgements
Kaggle for the dataset
TensorFlow/Keras for pre-trained models
