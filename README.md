# Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds

This project is part of Udacity's 'AI Programming with Python' Nanodegree.

## Project Overview

In this project, I created an image classifier using a pre-trained model to identify different dog breeds. The classifier takes an input image and predicts the breed of the dog present in the image. The project consists of the following main components:

1. Data Preparation: The project uses a dataset of dog images, which is divided into three sets: training, validation, and testing. The dataset is preprocessed and organized into the appropriate directories.

2. Pre-trained Model: A pre-trained deep learning model, such as VGG16, ResNet50, or InceptionV3, is used as the base for the image classifier. The pre-trained model is loaded and the final layers are replaced with custom fully connected layers.

3. Training the Classifier: The custom classifier is trained using the training set of dog images. The pre-trained model is used as a feature extractor, and only the weights of the custom layers are updated during training.

4. Evaluating the Classifier: The trained classifier is evaluated using the validation set of dog images. The accuracy of the classifier is calculated to assess its performance.

5. Testing the Classifier: The final step is to test the trained classifier using the testing set of dog images. The classifier predicts the dog breed for each test image, and the results are compared with the ground truth labels to measure the accuracy of the model.
