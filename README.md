# Melanoma-detection-assignment
This assignment will focus on building a multiclass classification model using a custom convolutional neural network in TensorFlow.


## Table of Contents
* [General Info]
* [Technologies Used]
* [Conclusions]
* [Acknowledgements]


## General Information
- Data set and background

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion


## Technologies Used
*Python
*Tensorflow
*Keras
*Augmentor
*Matplotlib
*NumPy


## Conclusions
The final output shows a training accuracy of 93% and a validation accuracy of 81%. This slightly shows an overfit as the training accuracy is really high. However, this model is comparatively better than the results obtained from the previous methods. This shows that the class imbalances have played a big role also on the batch normalization since it was not used before. However, as drawbacks, there is a high variance in the validation accuracy as seen in the graph and also on the validation loss there is a big variation with high spikes.


## Contact
Created by [@shenalk] - feel free to contact me!
