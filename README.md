# deep-learning-architectures
Keras Implementation of various deep learning architectures. Current supported architectures are,
- AlexNet (Keyword: 'alex_net')
- VGG16 (Keyword: 'vgg16_net')
- InceptionV1 (Keyword: 'inception')
- ResNet50 (Keyword: 'resnet50')
- MobileNetV2 (Keyword: 'mobilenetv2')

## Basic Usage
```
from architectures import return_model
model, checkpoint_callback, checkpoint_filepath, early_stopping = return_model(name='alex_net', patience=30, classes=2)
```
