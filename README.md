# Facial Recognition in Keras using CNN
#
Dataset Details:
ORL face database composed of 400 images of size 112 x 92. There are 40 people, 10 images
per person. The images were taken at different times, lighting and facial expressions. The faces
are in an upright position in frontal view, with a slight left-right rotation.

Steps followed:
1. Imported the required Python libraries
2. Loaded the dataset and normalized images
3. Split the train dataset into train and validate sets in 90 to 10 ratio 
4. Transform the images to equal sizes to feed in CNN
5. Build a CNN model that has 3 main layers:

i. Convolutional Layer
ii. Pooling Layer
iii. Fully Connected Layer

Total 10 layers; 3 conv2d, 3 maxpoolings, 2 dense and 1 each of flatten and dropout.

Total parameters 900,626, all trainable.

Classification Report, Confusion Matrix, Roc Curves with Auc values and Precision-Recall curves for all 20 classes.

Displayed Training, Testing and  Misidentified Faces.

Accuracy of the Model is 95.6 % after training for 150 epochs.



