# Computer Vision Using CNN
Using convolutional neural networks and transfer learning to classify images. 

MNIST Image Classification Problem.
  Objective is to classify digits 0-9 from dataset of 70,000 images. 60,000 for training and 10,000 for testing. 
  Model is convolutional neural network, which is ideal for computer vision problems such as this. 
  Use MaxPooling for dimensionality reduction to help make the problem more computationally efficient, increase accuracy score and reduce overfitting. 

Cats & Dogs Classification Problem.
  Objective is to classify whether a given image is a cat or a dog. 
  Limited training size, so I used the pretrained VGG16 model, and combined that with a custom 'head' model to create a very accurate final model, that achieves about 96.2% score.   Used Optuna to search for best hyperparameters, dropout to control overfitting, a learning rate scheduler, and early stopping to find the best possible model. 
