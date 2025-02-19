# Project Name
Skin Cancer Detection
To build a multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
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
![image](https://github.com/user-attachments/assets/c74d34e7-41c8-4861-8e6c-1d0c1919b38a)
<ul>
  <li>
    Model does not show overfitting or underfitting.
  </li>
  <li>
    Class rebalancining helped in predicting the different classes better.
  </li>
  <li>
    Achieved a high validation accuracy of 80.6% at 36 epochs.
  </li>
</ul>

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- [Python](https://www.python.org/) - version 3.12.4
- [Matplotlib](https://matplotlib.org/) - version 3.9.2
- [Numpy](https://numpy.org/) - version 2.0.1
- [Pandas](https://pandas.pydata.org/) - version 2.2.2
- [Seaborn](https://seaborn.pydata.org/) - version 0.13.2
- [Tensorflow]([https://www.statsmodels.org](https://www.tensorflow.org/)) - version2.18.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
I would like to thank the IIITB faculty for letting me work on this dataset and gain knowledge on implementation of CNNs and analyze how different techinques such as augmentation and handling class imbalance affects the outcomes of models.



## Contact
Created by [@anu-10] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
