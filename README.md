# Waste Classification Using Transfer Learning

**IBM AI Engineer Professional Certificate - Deep Learning with Keras and TensorFlow**

## Project Overview
Automated waste classification system that distinguishes between recyclable and organic waste using transfer learning with a pre-trained VGG16 model.

## Key Features
- **Transfer Learning**: Leverages VGG16 pre-trained on ImageNet for efficient feature extraction
- **Fine-Tuning**: Unfreezes and retrains specific layers to improve accuracy on waste classification task
- **Image Classification**: Binary classification (Recyclable vs. Organic) with 150x150 pixel images
- **Data Augmentation**: Real-time augmentation for improved model generalization

## Technologies Used
- TensorFlow & Keras
- Python
- NumPy, Matplotlib, Scikit-learn
- ImageDataGenerator for data preprocessing

## Model Architecture
1. **Extract Features Model**: VGG16 base + Dense layers with Dropout regularization
2. **Fine-Tuned Model**: Unfrozen block5_conv3 layer for improved performance

## Results
- Training with early stopping and learning rate scheduling
- Evaluation on test set with classification metrics
- Visual predictions on test images

## Skills Demonstrated
✓ Transfer learning implementation
✓ Deep neural network design
✓ Image preprocessing and augmentation
✓ Model compilation and training
✓ Performance evaluation and visualization

---
*Completed as part of IBM AI Engineer Professional Certificate*
