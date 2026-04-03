# Parkinson Prediction from Wave Drawing
This project aims to predict Parkinson’s disease from hand-drawn wave images using deep learning techniques. The model analyzes drawing patterns to identify potential motor impairments associated with Parkinson’s disease.
## Problem 
Parkinson’s disease affects motor control, which can be reflected in hand-drawn patterns. This project explores how image-based deep learning models can be used to detect such patterns for early prediction.
## Dataset
https://www.kaggle.com/datasets/kmader/parkinsons-drawings 
- Type: Hand-drawn wave images
- Task: Binary classification (Parkinson / Healthy)
## Methodology
### Image Preprocessing
- Inverse color transformation
- Morphological operations (dilation) to enhance stroke clarity
### Data Augmentation
- Applied transformations to increase dataset size and variability
### Models Used
- CNN (Custom)
- MobileNetV2
- ResNet50
## Results
| Model        | Validation Accuracy |
|-------------|--------------------|
| CNN         | 95.03%                |
| MobileNetV2 | 94.00%                 |
| ResNet50    | **96.00%**         |

- Best model: ResNet50
- Achieved high accuracy in classifying Parkinson’s patterns from images
## Tech Stack
- Python
- NumPy
- TensorFlow / Keras
- OpenCV
- Matplotlib
