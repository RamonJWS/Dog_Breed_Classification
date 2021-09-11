## Classification of 133 Dog Breeds Using Transfer Learning

### Project Overview

The project uses a specific branch of Deep Learning called Convolutional Neural Networks (CNNs), this architecture is very good at tackeling computer vision problems. 
More specifically, the project uses a pre-trained InceptionNet with transfer learning to acheive a high level of performance. Transfer learning is a technique that allows
to reuse a model across different tasks. The objective is that given an image of a dog, the algorithm will identify an estimate of the canine’s breed. If supplied an image
of a human, the code will identify the resembling dog breed. If the algorithm can't identify the image as a human or dog, it will say so.

### Libraries

Keras
OpenCV
PIL
Matplotlib
Numpy

### File Description

dog_app.ipynb: contains the jupyter notebook used for the development and preprocessing of the model.
dog_app.html: a more readable version of the jupyter notebook.
images: this contains the images used to test the model.
saved_model: this contains the models trained weight and biases.
haarcascades: Xml file for use with the OpenCV face detector class.

### Results

The model achieved a test accuracy of 79.8%, this is impressive considering that there are 133 different classes to choose from.
The model correctly classified the both human faces as being human and then predicted a dog breed that was most similar.
The model correclty predicted that the a cat was not a dog or a human face.
During testing the model predicted one dog breed wrong, however, the predicted dog breed was very similar (true: red setter, predicted: irish setter)
