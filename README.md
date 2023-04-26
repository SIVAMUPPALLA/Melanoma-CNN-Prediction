# Melanoma-CNN-Prediction

## Problem Statement
In this assignment, you will build a multiclass classification model using a custom convolutional neural network in tensorflow. 

 

#### Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


The collection contains 2357 photos of malignant and benign oncological illnesses from the International Skin Imaging Collaboration (ISIC). using the exception of melanomas and moles, whose photos are somewhat dominating, all images were sorted according to the classification acquired using ISIC, and all subgroups were divided into the same number of images.
The data set contains the following diseases:

1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion
 

NOTE: You don't have to use any pre-trained model using Transfer learning. All the model building process should be based on a custom model.

 

#### Data Reading/Data Understanding Project Pipeline Creating a route for training and testing photos 
- Dataset Creation With a batch size of 32, create a train and validation dataset from the train directory. Also, make sure your photos are 180*180 in size.
- Dataset visualisation Write code to visualise one instance of each of the dataset's nine classes. 
- Model development and training: 
    Create a CNN model that can properly recognise the 9 classes in the dataset. Rescale photos to normalise pixel values between (0,1) when developing the model.
- Select a suitable optimiser and loss function for model training.
- Run the model through 20 epochs.
- After the model fit, write down your findings and look for indications of model overfit or underfit.
- Select a suitable data augmentation approach to address underfitting and overfitting **Model construction and training on enhanced data:** - Create a CNN model that can properly recognise the 9 classes included in the dataset. Rescale photos to normalise pixel values between (0,1) when developing the model.
  - Select a suitable optimiser and loss function for model training.
  - Run the model through 20 epochs.
  - After the model fit, write down your results and check to see if the previous issue has been rectified.
**** Examine the current class distribution in the training dataset - Which class has the fewest number of samples?
  - Which classes have the greatest proportion of samples in the data?
**Handling class imbalances:** Using the Augmentor package, correct class imbalances in the training dataset.
**Model Building & training on the rectified class imbalance data:**
  - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
  - Choose an appropriate optimiser and loss function for model training
  - Train the model for ~30 epochs
  - Write your findings after the model fit, see if the issues are resolved or not?
 

 

The model training may take time to train and hence you can use https://cloud.lambdalabs.com/.
