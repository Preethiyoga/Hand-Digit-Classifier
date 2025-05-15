# Hand-Digit-Classifier
Designed A CNN model to classify the hand gestures as digits

## Objective
To build an ML model that can classify hand digits without relying on pre-built ML libraries or frameworks.  
To implement core logic and mathematical steps to understand the working of ML models. 

## Dataset
I have used Kaggle's dataset containing 1700+ sample images. Link: https://www.kaggle.com/datasets/javaidahmadwani/sign-language-digits-dataset.  

## How it works
The model is built using Convolutional Neural Network(CNN) architecture consisting of Convolutional, Pooling, and Fully connected layers.  
The convolutional Layer can apply 'n' filters to images of size m*m to extract features from images. These filters are initialized with random values and updated during training.  
Max pooling technique can help in keeping prominent features to reduce computational cost and overfitting.  
The final layer is a fully connected layer that predicts and classifies the image. After applying a Linear function to the input image, the softmax activation function is used to convert the output scores into probabilities. The class with the highest probability is selected as the final prediction.  

## Learnings
Learned the importance of "**One-hot encoding**" in Multi- class classification.  
Understood how **Backpropagation** helps the model learn by minimizing the error between predicted and actual output — a key process in training neural networks.  
Experimented with different learning rates across multiple epochs to observe how the combination of learning rate and epoch count influences the model's training behavior, particularly in terms of overfitting and underfitting.  

## Future work
Real-time gesture detection using webcam.
