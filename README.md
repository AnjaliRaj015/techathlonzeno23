## Hand Gesture Recognition

Hand Gesture Recognition dataset contains images from a variety of different
hands, from different races, ages and genders, posed into Rock / Paper or
Scissors and labeled as such. 

These images have all been generated using CGI
techniques as an experiment in determining if a CGI-based dataset can be used
for classification against real images.

Note that all of this data is posed against a white background.
Dataset contains 2,892 images of diverse hands in Rock/Paper/Scissors poses
as train test and validation data.

Each image is 300×300 pixels in 24-bit color.

A model that classifies the hand gestures.

Steps for building the model:-

Step1: 

Preprocess the dataset. This involves loading the images, resizing them to a common size (e.g., 300x300), normalizing pixel values to the range [0, 1], and splitting the data into training, validation, and testing sets.

Step 2:

Define a CNN architecture using TensorFlow.

Step 3:

After building the model, compile it by specifying the loss function, optimizer, and metrics to monitor during training.

Step 4:

To enhance the model's generalization, apply data augmentation techniques such as rotation, flipping, and zooming to artificially increase the diversity of the training dataset.

Step 5:

Train the model using the preprocessed training data and validation data. One-hot encode the labels before training.

Step 6:

After training, evaluate the model on the test dataset.

Step 7:

Predict gestures using the model.
