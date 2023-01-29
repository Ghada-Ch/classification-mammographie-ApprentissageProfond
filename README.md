# classification-mammography-Deep Learning
## Purpose :
Build a deep learning model for the classification of
mammography images in three categories (Normal, benign, malignant).
We will have a graphical interface from which we can test
different images to know the relevance of the system.
## Step 1: Defining the architecture of the model:
We need to define what our model will look like and this requires
answer questions such as:
● How many convolutional layers do we want?
● What should be the activation function of each layer?
● How many hidden units should each layer have?
## Step 2: Model training:
We will decompose our database into images
workouts and their corresponding true labels and Images of
test with their corresponding true labels
We also define the number of epochs in this step. For
start, we will run the model for 10 epochs (you
can change the number of epochs later).
## Step 3: Image prediction:
We load the test data (images) and go through the step of
preprocessing here too. We then predict the classes for these images
using the trained model.

## Step 4: Estimating model performance
Finally, you generate a confusion matrix as well as display the accuracy of
your model
Environment :
You can use the environment and programming language of your
choice.
### Database :

You must use a general database of at least 1000 images.
Here is the link of the DDSM database which contains mammograms
"normal", "benign", "malignant" and which you can download for free:
https://drive.google.com/file/d/10bJ75CJnSQSgya0HXKP3difeiKChxfYi/view
