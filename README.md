# Emotion-Detection


This model detects 7 type of emotions, namely [Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise].
Training Dataset contains 28109 images of these 7 different classes.

# Packages Used
pandas, numpy, matplotlin, Tensorflow, Keras, OpenCV

#
ResNet50 is used in the current implementation, I also tried DenseNet169, VGG16, VGG19. But ResNet50 Gave the best accuracy of 60% on training set while training on kaggle GPU.
Data Augmentation is done by using ImageDataGenerator of Tensorflow Keras.

I have saved the model in .h5 file as model_emotion.h5 file.
Link to the training dataset, test dataset and saved model: - https://drive.google.com/drive/folders/1QxFpFJ3sMq-HyaOerqCTY6-o-Upm2AUB?usp=sharing

#
But I will suggest to use this model as this has 71% accuracy on training set, https://www.kaggle.com/code/aayushmishra1512/emotion-detector
