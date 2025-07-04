🏏 Cricket Pitch Classification using Machine Learning
This project presents a machine learning-based approach to classify cricket pitches as grassy or non-grassy, and also predicts the pitch type as batting-friendly, bowling-friendly, or neutral based on physical parameters such as soil moisture, temperature, compaction, and grass coverage.

📁 Contents
Pitch_Image_Classifier.ipynb – A CNN-based model using PyTorch to classify pitch images into grassy or non-grassy.
Pitch_Feature_Classifier.ipynb – A tabular-data model using XGBoost and LightGBM to classify pitches based on environmental features.
/Dataset – Organized image data with grassy/ and non_grassy/ folders.
/Test – Contains test images for evaluation.

🔧 Technologies Used
Python
PyTorch
TensorFlow (for deployment)
scikit-learn
LightGBM, XGBoost
OpenCV & PIL
Jupyter Notebook

📊 Key Features
Image Classification using transfer learning with MobileNet v4 Small.
Feature-Based Classification using ensemble methods.
Custom Green-Pixel Factor metric to enhance classification of grassy pitches.
Model evaluation with accuracy and confusion matrix.
Real-time test image prediction pipeline.
