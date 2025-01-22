# Melonama Detection
In this project, we have built a multiclass classification model using a custom convolutional neural network in TensorFlow. 

Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
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



#Results:
Accuracy Trends:

Training Accuracy increased consistently, starting at 21.16% and reaching 89.6% in 30th epoch. Validation Accuracy improved steadily, starting from 38.1% and reaching 85.5% in 30th epoch.

Loss:

Training Loss decreased significantly, indicating better performance and reduced error as training progressed. Validation Loss Validation loss initially improved but showed minor fluctuations after epoch 16, possibly due to slight overfitting.

Evaluation:

It has been seen that training and validation accuracies have improved significantly from previous two attempts. The training loss and validation loss are also decreasing consistently, indicating the model is learning well.

We can say that performance and accuracy of the model has improved significantly after implementing Data Augmentation and Class Rebalancing.

There is indication of slight overfitting but the good part is that Validation and training metrics are close.

#Platform Used: 
Jupyter Notebook with GPU processing.

#Python packages: 
tensorflow, numpy, pandas, matplotlib, pathlib, os etc.

Developed By: Satyam Singh
