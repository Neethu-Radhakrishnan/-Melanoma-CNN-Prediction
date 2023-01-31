# Project Name
  Skin Cancer Classification using CNN


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#general-information)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Briefing on the project:
  To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin    cancer deaths.

- Background:
  Melanoma, the most serious type of skin cancer, develops in the cells (melanocytes) that produce melanin — the pigment that gives your skin its color. It accounts for 75% of skin cancer deaths. Early detection of melanoma is critical to saving lives. However, it is difficult for dermatologists to detect melanoma because it can be difficult to distinguish from other benign skin lesions. In this project, we will build a CNN based model which can accurately detect melanoma.

- Business probem that the project is trying to solve:
  A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- Dataset:
  The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. The data set contains the following diseases:
  * Actinic keratosis
  * Basal cell carcinoma
  * Dermatofibroma
  * Melanoma
  * Nevus
  * Pigmented benign keratosis
  * Seborrheic keratosis
  * Squamous cell carcinoma
  * Vascular lesion


## Conclusions
Model 1: The maximum accuracy is around 87%. However the validation accuracy is about 56%. The gap between the blue line and orange line shows that there is strong evidence of Overfitting. There are no dropput layers.
Model 2: The Overfitting problem has been eradicated.The distance between the blue line and Orange line is much less. The model accuracy is around 53% and the Validation accuracy is around 52%. The model accuracy and validation accuracy are very close to each other but are much less now as compared to before data_augmentation.Dropout layer with 30% Fraction.
Model 3: The batch normalization was used earlier but it worsens the performance of the model such that the Training accuracy and the validation accuracy were far apart. Dropout layer with 30% fraction was added.
It showed that the model underfitted with batch normalisation. Hence it was not used. The highest training accuracy the model showed was 71% which was a big improvement. 
The highest Validation accuracy was about 59%. This is a massive improvement in the model in terms of accuracy. There is a slight case of overfitting but the blue line and orange line are close together, indicating that the model is performing well.
Thus, it can be said that Balancing the data improved the performance of the model. For better performance, the sample size of the data should be increased.

## Technologies Used for CNN
- tensorflow
- keras
- Augmentor
- glob
- other python libraries

## Acknowledgements
- This project was inspired from Upgrad's ML Deep learning course

## Contact
- Schifra Daruwalla
- Neethu Radhakrishnan
- SakshiChopkar
