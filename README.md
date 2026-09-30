# Fruit Classification using CNN

A multi-class fruit image classification project built in Google Colab using
TensorFlow/Keras.

## Dataset
9 fruit classes with approximately 360 images.

## Approach
- Dataset inspection and cleaning
- RGB conversion and image resizing
- Train/validation split
- Pixel normalization
- Data augmentation
- CNN from scratch
- Model comparison
- Transfer learning using MobileNetV2
- Fine-tuning
- Confusion matrix and classification report

## Models

| Model | Validation Accuracy |
|---|---:|
| CNN from scratch | ~54% |
| Smaller CNN | ~29% |
| MobileNetV2 | ~87.5% |
| Fine-tuned MobileNetV2 | ~87.5% |

## Best Model
MobileNetV2 with transfer learning achieved approximately 87.5%
validation accuracy on the validation set.

## Tech Stack
Python, TensorFlow, Keras, NumPy, Matplotlib, Scikit-learn

## Notebook
The complete implementation is available in the Jupyter/Colab notebook.
