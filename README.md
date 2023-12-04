# Project Name
> Multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

Business Goal 

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


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Training and Validation Accuracy:
The training accuracy seems to be steadily increasing, which indicates the model is learning from the training data. The validation accuracy is also increasing but is quite volatile and generally lower than the training accuracy. This suggests that while the model is learning, it may not be generalizing as well to new, unseen data.

Training and Validation Loss:
The training loss is decreasing, which is expected as the model's predictions become more accurate on the training data. The validation loss decreases as well but shows significant spikes at certain epochs. These spikes suggest that the model’s performance on the validation set is inconsistent.

Analysis:
There's a gap between training and validation accuracy, with training accuracy being higher. This gap suggests a degree of overfitting because the model performs better on the training data than on the validation data. Overfitting happens when a model learns not only the underlying patterns but also the noise in the training dataset. The volatility in the validation accuracy and the spikes in validation loss indicate that the model may not be stable across different sets of data.

It appears that overfitting is present, rather than underfitting. Underfitting would be indicated by poor performance on both training and validation data, which is not the case here.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupyter Notebook
- Python 3.10.9 | packaged by Anaconda, Inc
- Python library used
    warnings
    numpy
    pandas
    sklearn
    statsmodels
    matplotlib
    seaborn
- Kernel Infomation
Python 3.10.9 | packaged by Anaconda, Inc. | (main, Mar  1 2023, 18:18:15) [MSC v.1916 64 bit (AMD64)]
Type 'copyright', 'credits' or 'license' for more information
IPython 8.10.0 -- An enhanced Interactive Python. Type '?' for help. 


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Referances:
https://www.geeksforgeeks.org/
https://stackoverflow.com/



## Contact
Created by [PrvinGorlewar] - feel free to contact me! pravin.gorlewar@gmail.com


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->