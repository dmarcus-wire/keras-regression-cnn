# CNN
- Regression with Keras and CNNs — training a CNN to predict house prices from image data
- Our CNN takes input from multiple images of the inside and outside of a home and outputs a predicted price using Keras and regression.
  
## Improvement from Regression
- Removing the fully-connected softmax classifier layer typically used for classification
- Replacing it with a fully-connected layer with a single node along with a linear activation function.
- Training the model with a continuous value prediction loss function such as mean squared error, mean absolute error, mean absolute percentage error, etc.

## Dataset
> https://github.com/emanhamed/Houses-dataset

The numerical and categorical attributes include:
- Number of bedrooms
- Number of bathrooms
- Area (i.e., square footage)
- Zip code

Four images of each house are also provided:
- Bedroom
- Bathroom
- Kitchen
- Frontal view of the house