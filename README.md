# Emotion-Detection


This model detects 7 type of emotions, namely [Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise].
Training Dataset contains 28109 images of these 7 different classes.

# Packages Used
pandas, numpy, matplotlin, Tensorflow, Keras, OpenCV

#
ResNet50 is used in the current implementation, I also tried DenseNet169, VGG16, VGG19. But ResNet50 Gave the best accuracy of 60% on training set while training on kaggle GPU.
Data Augmentation is done by using ImageDataGenerator of Tensorflow Keras.
