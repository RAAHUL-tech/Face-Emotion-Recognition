# Face-Emotion-Recognition
Face emotion Recognition is implemented using different deep-learning frameworks like Pytorch, TensorFlow, and Mxnet. In this project, our objective is to classify each input image as any one of the 7 emotions namely 0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral. 

For our training, we used a famous FER-2013 dataset in Kaggle which contains 28,000 images for training and 4000 images for testing/development. Rather than using the whole dataset, we subsampled the dataset to 9000 images for training and 1000 images for testing.

# Project Research Outcomes
   When trying different optimizers like RMSprop, SGD, Adam, etc our model performed well in RmsProp optimizer with an accuracy of 55%.
   When trying different learning rates like 0.1, 0.001, and 0.0001 our model performs well for 0.001 learning rate.
   The accuracy of our model is 56% after using a learning rate of 0.001, RMSProp optimizer, gradient clipping, and weight decay.



