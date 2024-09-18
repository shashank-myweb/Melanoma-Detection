# Melanoma Detection assignment
> Multi classification assignment based on CNN


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This assignment is about Multi Classification in ML where expectation is to create CNN Model which does the Image classification into one of the 9 Cancer types
- Build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
- Create a solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

## Conclusions
- The dataset had class imbalances because of occurrence of each cancer type and hence the images in the dataset were having imbalance
- Seborrheic keratosis has the least sample size in the dataset
- Pigmented benign keratosis has the dominant sample size
- Data augmentation and Dropout were requird to balance this imbalance


## Technologies Used
- pathlib
- tensorflow
- matplotlib
- numpy
- pandas
- os
- Google Colab


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->


1. Create a multi-classification model
2. Use prefetch dataset
3. 3. 2 or 3 convolv layers and then max pooling and fc layer
4. create 1D array as output of flattening layer
5. stochastic or Adam optimizer
6. categorical entropy loss by summation of P log P
7. Findings in terms of overfitting or underfitting
8. then use data augmentation like zoom, flip, rotate (atleat 2 to 3 by tf.keras.layers)
9. tf.keras.sequential([
layer.experimental.preprocessing().
random.flip
or random.rotation
or random.zoom



    ])
  from trainds get1 image and apply this keras to this image and then show the visualize outcome and show the graph and then explain for all the 9 different class
then do it for the model
11. https://stackoverflow.com/questions/66570789/keras-experimental-randomflip-and-randomrotation-do-not-work-with-map
12. use dropout after convolv layers
13. for imbalance sanity check - take trainds and then do a count of images for all 9 different classes and explain the findings like img domination and minimum imaging sample
14. and write in finding
15. then install augmentor pip install augmentor
16. normalization in top layer like convolv layer
