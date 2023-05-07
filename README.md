# HUMAN ACTION RECOGNITION

### How to Run ?
1. Download the HAR dataset from the given link : https://www.kaggle.com/datasets/meetnagadia/human-action-recognition-har-dataset
2. Entire code is present in Project_HAR.ipynb in the root directory. Run the file
3. The trained model is stored in model.h5 file
4. Results folder contains plots for accuracy and loss wrt to epochs

### Description
1. Human Action Recognition
2. Human Action Recognition (HAR) seeks to comprehend human behaviour and categorise each action. It has a wide range of applications, and as a result, it is gaining traction in the field of computer vision. 
3. The dataset contains 12k+ labelled images of 15 different human activities

### Dataset and Model
1. The dataset contains 12000 labeled images of people with 15 different activities, that include calling, clapping, cycling, texting, hugging , eating etc.,
2. After routine data cleaning, we split it into train and validation sets, and trained a deep convolution neural network
3. Our network predicts the activity, given an image of the person
4. We test out various architectures and tune hyperparameters in order to report the best accuracies on validation set