# Image-Processing

resized_images

Performed tasks:
• Pick a basic color, e.g. white, and pad all images that do not have 1:1 aspect ratio
• Reshape, without stretching, to a 128x128x3 pixel array shape
• Each image that the pixel range is from 0 to 255 (inclusive or [0, 255]) which is also called “contrast stretching”. 
• Save the data to disk in a format the team deems appropriate for easily reading back in. 
• Data that it will be used for Classification.

random_forest_classifier

Split the preprocessed image array data from resized_images into train and test sets
Choose an algorithm from scikit-learn documentation
Train the model with the training data from the split
Predict the class of the following piece of gear with the model: here
Evaluate the model with a confusion matrix to see how individual classes performed (use test data from the split)
Output the overall accuracy (use test data from the split)

classification_with_deep_learning
The aim of the model is classification of outdoor equipments using trained model

Architecture:
1. Input Layer (3 channel image input layer)
2. Convolutional (2D)
3. Max Pooling
4. Convolutional (2D)
5. Max Pooling
6. Dense (Output layer)
7. Web service on Flask
