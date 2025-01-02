# Brain Tumor Detection using Machine Learning 🧠

This repository contains a Python-based implementation of a brain tumor detection system using medical images. The project leverages computer vision techniques for image preprocessing and machine learning models for classification.

## Key Features

### Image Preprocessing:
- Skull stripping, CLAHE contrast enhancement, Otsu thresholding, and normalization.
- Visualization of preprocessing steps for better understanding.

### Feature Extraction:
- GLCM for texture analysis.
- HOG for shape and edge features.

### Machine Learning Models:
- SVM and KNN models optimized using GridSearchCV.
- Ensemble model combining SVM and KNN for improved accuracy.

### Evaluation:
- Metrics: Accuracy, precision, recall, F1-score, and ROC-AUC.
- Confusion matrices for model performance visualization.

## Results
- **Ensemble Model:** 93% accuracy on the test set.
- **SVM:** 93% accuracy.
- **KNN:** 90% accuracy.

## Repository Structure
- `brain_tumor_detection.py`: Main script for preprocessing, feature extraction, and model training.
- `README.md`: Detailed documentation and instructions.
- `requirements.txt`: List of dependencies.

## How to Use
1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run the script to preprocess images, train models, and evaluate performance.

Explore the potential of AI in healthcare with this open-source project. Contributions are welcome! 🌟

