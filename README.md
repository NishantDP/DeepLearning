# Deep Learning
# Basic implementation of some of the deep learning techniques in Python
## All the projects are from Udacity's Introduction to Machine Learning with TensorFlow Nanodegree Program.

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

### 1.Gradient Descent

In this section, the following basic functions are implemented:

- Sigmoid activation function
- Output (prediction) formula
- Error function
- The function that updates the weights


### 2. NN training steps:

- One-hot encoding the data
- Scaling the data
- Writing the backpropagation step
- Training the 2-layer Neural Network
- Back-propagate the error
- Training the above NN using MSE as error function
- Implementing a hidden layer and back propogation in the above NN with MSE.


### 3. Deep learning with TensorFlow
- Introduction to TensorFlow, tensors, single and multi-layer NN.
- NN with TensorFlow and Keras
	- Creating pipelines
	- Implementing softmax
	- Building NN model
	- Making predictions
	- Other ways of building model- subclassing, adding layers.
- Training the model with training data.
	- Compile the model with necessary parameters (optimizer, loss function and metrics)
	- Fit the model to the training data with multiple epochs.
	- Check the result on testing data
	- Evaluate the performance with accuracy metrics.
- Example: Develop, train and validate a NN model on fashion MNIST dataset.
- Inference and validation
	- Creating validation set and testing on it during training.
	- Inference on training and validation accuracy
	- Avoiding overfitting: Early stopping and dropout.
- Saving and loading models
	- Save and load the model in HDF5 format (Keras).
	- Save and load model as TensorFlow models.
	- Save model during training with 'ModelCheckpoint' callback. (another method to avoid overfitting)
- Working with own image dataset
	- Loading images with TensorFlow
	- Data Augmentation: rescale, rotation_range, width_shift_range, height_shift_range, shear_range, zoom_range, horizontal_flip, fill_mode.
- Transfer Learning
	- Build Image classifier using the pre-trained model 'mobilenet_v2'
	

