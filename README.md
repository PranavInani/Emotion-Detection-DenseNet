# Emotion-Detection-DenseNet
This project implements a deep learning model using DenseNet to classify emotions from facial images. The model is trained on the FER2013 dataset, which contains labeled facial expressions categorized into various emotion classes.
Requirements

To run this project, you'll need the following libraries:
-  PyTorch
- torchvision
- pandas
- numpy
- PIL (Python Imaging Library)

### Dataset Used
FER2013: A publicly available dataset containing labeled facial expressions.

## Model
### Model Architecture
DenseNet: A densely connected convolutional neural network architecture known for its efficiency and performance in image classification tasks.

### Preprocessing
Images are resized and normalized.
    Data augmentation techniques, such as horizontal flipping, are applied during training.

### Training
The model is trained using PyTorch with appropriate loss functions and optimizers.

I have used Transfer Learning to get pretrained DenseNet Model and then trained it on FER2013 dataset. Also have made some helper functions to get output as desiered either in image or video format.
everything is reproducable in jupyter notebook. you just need to upload your kaggle json file.
