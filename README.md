# 🚗 Driver Distraction Detection System

A deep learning-based system that detects distracted driving behaviors using computer vision. This model can identify 10 different types of driver activities with high accuracy.

## 🎯 Project Overview

This system uses Convolutional Neural Networks (CNN) to classify driver behaviors into different categories, helping improve road safety by detecting distracted driving in real-time.

## 📊 Classification Categories

0. Safe driving
1. Texting (right hand)
2. Talking on phone (right)
3. Texting (left hand)
4. Talking on phone (left)
5. Operating radio
6. Drinking
7. Reaching behind
8. Hair and makeup
9. Talking to passenger

## 🛠️ Technical Stack

- **Python 3.11+**
- **Key Libraries**:
  - TensorFlow/Keras for deep learning
  - OpenCV for image processing
  - NumPy for numerical operations
  - Pandas for data manipulation
  - Matplotlib for visualization

## 📈 Model Performance

- Input Image Size: 224x224x3
- Training Dataset: 22,424 images
- Multiple classes of distracted behavior
- High accuracy in predicting driver activities

## 💻 How to Use

1. Clone the repository:
```bash
git clone https://github.com/Amitjangir010/Distracted_Driver_classification_model.git
```
2. Run the Jupyter notebook:
```bash
jupyter notebook Project_Driver.ipynb
```

## 📸 Dataset Structure

```
imgs/
├── train/
│   ├── c0/  # Safe driving
│   ├── c1/  # Texting - right
│   ├── c2/  # Talking on phone - right
│   └── ...
└── test/
    └── [test images]
```

## 🔄 Model Pipeline

1. **Data Preprocessing**
   - Image resizing (224x224)
   - Normalization
   - Data augmentation

2. **Model Architecture**
   - CNN-based architecture
   - Multiple convolutional layers
   - Dropout for regularization
   - Softmax activation for classification

3. **Training Process**
   - Batch processing
   - Learning rate optimization
   - Model checkpointing

## 📊 Sample Predictions

```python
# Example prediction
model.predict(image)
# Output: Class probability distribution for 10 activities
```

## 🎯 Future Improvements

- [ ] Real-time video processing
- [ ] Mobile deployment
- [ ] Night vision capability
- [ ] Integration with car systems
- [ ] Alert system implementation

---
Made with ❤️ by Amit Jangir
