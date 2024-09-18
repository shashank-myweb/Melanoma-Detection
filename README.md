# Melanoma Detection assignment
> Multi classification assignment based on CNN


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- This assignment is about Multi Classification in ML where expectation is to create CNN Model which does the Image classification into one of the 9 Cancer types
- Build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
- Create a solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

## Technologies Used
- pathlib
- tensorflow
- matplotlib
- numpy
- pandas
- os
- Google Colab

## Conclusions
- The dataset had class imbalances because of occurrence of each cancer type and hence the images in the dataset were having imbalance
- Seborrheic keratosis has the least sample size in the dataset
- Pigmented benign keratosis has the dominant sample size
- Data augmentation and Dropout were requird to balance this imbalance
  
## Contact
Created by [ShashankMishra] - feel free to contact me!

