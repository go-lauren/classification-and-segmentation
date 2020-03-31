The code for the classifer cnn is contained in Proj4-p1.ipynb.
The code for the segmentation cnn is contained in Proj4-p2.ipynb.

Proj4-p1.ipynb will import packages, setup DataLoaders for training, testing, and validation, define the neural network, train the model, test the net on the test set and training set, plot the validation vs training accuracy, visualize the model's filters, and display sample images and predictions on the test set.

Proj4-p1.ipynb contains the following functions:
    save: save the current net and epoch
    load: load the net and epoch at path
    validate: score the accuracy of the net on a dataset

Proj4-p2.ipynb will import packages, define a CNN, setup DataLoaders for training, testing, and evaluation, and train the network. It will also produce output images for the test set, plot a training vs validation loss graph, and output the result of the net on "london.JPG".
The code for setting up google drive for running in google colab is commented out on the top.

Proj4-p2.ipynb contains the following functions:
    save_label: saves labelled images
    train: train the neural network
    test: compute avg loss of model on a datset
    cal_AP: compute the average precision of a model on a dataset
    get_result: output the predictions of a model on a datset
These functions were part of the starter code.

dataset.py contains the code for the FacadeDataset used in segmentation.
