*Multi-class dog breed identification*

This notebook builds an end-to-end multi-class image classifier using Tensorflow 2.0 and Tensorflow Hub.

1. **Problem** 

Identifying the breed of a dog given an image of a dog.

When I take a photo of a dog, I want to know what breed of dog it is.

2. **Data**

The data we're using is from Kaggle's dog breed identification competition.
https://www.kaggle.com/c/dog-breed-identification/data

3. **Evaluation**

The evaluation is a file with prediction probabilities for each dog breed of each image.
https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

4. **Features**

Some information about the data:
*We're dealing with images (unstructed data) so it's probably best we use deep learning / transfer learning.
*There are 120 breeds of dogs (this means there are 120 diffrent classes). 
*There  are around 10.000+ images in the training set (this images have labels).
*There are around 10.000 images in the test set (this images have no labels, because we'll want to predict them).



