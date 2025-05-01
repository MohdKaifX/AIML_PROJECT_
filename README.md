# AIML_PROJECT_
Dataset Link - https://www.kaggle.com/datasets/msambare/fer2013

😄 Emotion Detection System using CNN, VGG16 & ResNet50
This project focuses on building an Emotion Detection System using deep learning models including a custom CNN, CNN with Augmentation, and pretrained models like VGG16 and ResNet50. It classifies human facial expressions into various emotion categories such as Happy, Sad, Angry, Surprise, Neutral, etc.

🧠 Overview
Emotion recognition is an important field of computer vision and human-computer interaction. This project implements and compares multiple models:

Custom CNN

CNN with Image Augmentation

Transfer Learning with VGG16

Transfer Learning with ResNet50

📊 Dataset
The project uses the FER2013 dataset which consists of grayscale facial images (48x48) categorized into 7 emotion classes:

Angry 😠

Disgust 🤢

Fear 😨

Happy 😄

Sad 😢

Surprise 😲

Neutral 😐

🧬 Model Architectures
1. Custom CNN
Built using Conv2D, MaxPooling2D, Dropout, and Dense layers.

Designed to be lightweight yet effective.

2. CNN + Augmentation
Same as Custom CNN but includes:

Rotation

Zoom

Horizontal Flip

Width/Height Shift

Brightness Adjustment

3. VGG16
Transfer Learning using pretrained VGG16 (without top layers).

Custom Dense layers added for classification.

4. ResNet50
Transfer Learning using pretrained ResNet50.

Efficient in deeper learning of features.

