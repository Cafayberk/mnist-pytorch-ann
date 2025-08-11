# mnist-pytorch-ann
MNIST Classification with PyTorch

This project implements a simple neural network using PyTorch to classify handwritten digits from the MNIST dataset. 
The model takes 28x28 grayscale images as input and outputs predictions for digits 0 through 9.

Contents:
- mnist_train.ipynb : Jupyter notebook for training and testing the model.
- mnist_train.py : Python script version of the training code.
- requirements.txt : List of required Python packages.

Technologies Used:
- Python 3
- PyTorch
- Torchvision
- Matplotlib

Model Architecture:
- Input layer: 784 neurons (28x28 pixels flattened)
- First fully connected layer: 128 neurons, ReLU activation
- Second fully connected layer: 64 neurons, ReLU activation
- Output layer: 10 neurons (one for each digit class)

Setup Instructions:
Install the required packages using pip:

    pip install -r requirements.txt

Running the Code:
To train the model using the Python script, run:

    python mnist_train.py

Alternatively, open and run the Jupyter notebook in an environment such as Google Colab.

Results:
The model achieves over 97% accuracy on the MNIST test set after 5 training epochs.

License:
This project is licensed under the MIT License.

