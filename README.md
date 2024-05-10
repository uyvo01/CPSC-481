# CPSC-481
Handwritten Digit Recognition
## Group members: 
### Gina Lee
### Uy Vo
## Describe the problem
Handwritten digit recognition is a fundamental problem in the field of machine learning and computer vision. It involves the task of accurately identifying and classifying handwritten digits from images into their respective numerical representations (0 through 9).
The problem is typically approached as a supervised learning task, where a model is trained on a dataset containing labeled examples of handwritten digits. Each example consists of an image of a handwritten digit along with the corresponding label indicating which digit it represents.
## Programming language
This project at first is in need of the software of python. The packages have been imported and the algorithm created which is done by installing the new packages from online in python3.
Apart from that the total project is online compiled or ran and done by the software provided by the Google Colab free version and Jupyter Notebook.
## Datasets 
This project uses the MNIST dataset. This is a dataset of 60,000 28x28 grayscale images of the 10 digits, along with a test set of 10,000 images.
https://keras.io/api/datasets/mnist/
## Algorithm being applied / approach
The project will apply regular neural networks to recognize handwritten digits using one dataset from MNIST which is a widely used benchmark dataset. Here's a high-level overview that we will do:
### Data Preparation: 
Obtain a dataset of handwritten digits from MNIST.  Split the dataset into training, validation, and testing sets.
#### Preprocessing images: 
Preprocess the images to make them suitable for training the neural network. We used OpenCV library to read, convert, and normalize four images which we wrote on our laptop to matrices of numbers from 0 to 1.
#### Model Architecture: 
Design the architecture of the neural network model for handwritten digit recognition. We have four matrices of numbers converted from the previous step for the input layer. Then, we used ReLu activation function for hidden layer, and sigmoid activation function for output layer
#### Training: 
Train the neural network using the training data from the first step. This involves feeding batches of preprocessed images into the network, computing the loss between the predicted and true labels. Monitor the performance of the model on the validation set during training to avoid overfitting.
## Description of the software
### Programming language
This project at first is in need of the software of python. The packages have been imported and the algorithm created which is done by installing the new packages from online in python3 version 3.12.
Apart from that the total project is online compiled or ran and done by the software provided by the Jupyter Notebook.
### Datasets 
This project uses the MNIST dataset. This is a dataset of 60,000 28x28 grayscale images of the 10 digits, along with a test set of 10,000 images.
We have done some research on the internet about the algorithm, model building processes, and neural network applications in handwritten digit recognition. We will reference discrete instructions about Jupyter, neuron network, etc. to complete our code without using any existing code.

