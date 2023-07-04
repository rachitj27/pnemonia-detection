# pneumonia-detection
After experimenting with various AI models. Found the best models and parameters to use in order to accurately detect pneumonia from a given chest x-ray image. 
# Introduction
We were given inputs of various chest X-rays. Some of which were pneumonia positive and some of which were negative. For the computer to successfully read these X-rays, we must break the image down into pixels within separate RGB color channels. The dataset contains about 2400 images. 80% of it was used to train our models and the last 20% was to test the model.
# Using a Convolutional Neural Network:
We then trained a Convolutional Neural Network (CNN) with the provided dataset to help predict whether the X-ray is positive or negative. After many experimentations, it gained about 82% accuracy on the test set. But when tried on a completely new set of field data. The model was performed with 72% accuracy.
# Augmentation
This issue was mainly because the data in the field set consisted of rotated X-rays that our model had not seen before. To fix this we augmented our data by rotating our training data. After augmentation, our model was back to about 82% accuracy. 

Credits-Project Idea/Project Help: Inspirit AI 
