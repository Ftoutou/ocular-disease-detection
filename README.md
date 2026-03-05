# Ocular Disease Detection using CNN

A Convolutional Neural Network (CNN) model for classifying 10 different ocular diseases from fundus images.

## Dataset
The model is trained on fundus images with the following classes:
- Central Serous Chorioretinopathy [Color Fundus]
- Diabetic Retinopathy
- Disc Edema
- Glaucoma
- Healthy
- Macular Scar
- Myopia
- Pterygium
- Retinal Detachment
- Retinitis Pigmentosa

## Model Architecture
- **Input**: 224x224x3 RGB images
- **Preprocessing**: Resize and rescale (1/255)
- **Data Augmentation**: Random flips, rotation, zoom, and brightness
- **CNN Layers**: Multiple Conv2D + MaxPooling2D layers
- **Output**: Softmax activation with 10 classes

## Requirements
- tensorflow>=2.0
- numpy
- matplotlib
- Pillow
