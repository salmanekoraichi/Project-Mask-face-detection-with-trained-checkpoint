# Face Mask Detection Using CNN

A deep learning project that uses Convolutional Neural Networks (CNN) to detect whether a person is wearing a face mask or not. The model achieves over 90% accuracy in classification using TensorFlow/Keras.

## Features

- Binary classification (with mask/without mask)
- Built with TensorFlow and Keras
- CNN architecture with multiple convolutional and dense layers
- Data preprocessing and augmentation
- Model evaluation and visualization
- Easy-to-use prediction function

## Requirements

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib
- OpenCV
- Pillow
- scikit-learn

## Dataset Structure

The dataset should be organized as follows:
```
data/
├── with_mask/
│   └── with_mask_*.jpg
└── without_mask/
    └── without_mask_*.jpg
```

## Model Architecture

- Input Layer: 128x128x3
- 2 Convolutional Layers with MaxPooling
- Multiple Dense Layers with Dropout
- Output Layer: 2 classes (mask/no mask)

## Usage

1. Install dependencies:
```bash
pip install tensorflow numpy matplotlib opencv-python pillow scikit-learn
```

2. Train the model:
```python
python main.py
```

3. Make predictions using the `maskPrediction()` function:
```python
maskPrediction("path/to/image.jpg")
```

## Model Performance

- Training Accuracy: ~92%
- Validation Accuracy: ~92%
- Test Accuracy: ~90%

## Saved Model

The trained model is saved as 'path_to_my_model.h5' and can be loaded for inference.


## Contributing

Feel free to submit issues and enhancement requests!
