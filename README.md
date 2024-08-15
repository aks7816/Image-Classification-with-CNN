In the project, I am assiging a label to an image from a predefined set of categories. To do so, I have chosen to use convolutional neural networks (CNN), which is a class of deep neural networks. 

## Summary 
Libraries : Used libraries such as numpy, PIL.Image, and PyTorch libraries, which is an open-source deep learning framework for developing models
Data Preparation: Applied transformation to preprocess images from the CIFAR-10 dataset. The images were converted to tensors and normalized. Added data loaders to provide data in batches for training and testing (Evaluation)
Model Definition: Defined the CNN model. This model has 2 convolutional layers, 1 pooling layer, 3 fully connected layers
Training: The model is trained over 30 epochs. The loss is calculated with the loss function. The model's parameters are repeatedly updated through an optimizer
Evaluation: The model is evaluated against the test data to determine its accuracy. 
