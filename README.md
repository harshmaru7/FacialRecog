## Gender and Ethnicity Classification and Generation using Deep Learning in Heterogeneous Face Recognition

### Abstract

- Soft biometric traits are physical, behavioral and human characteristics such as gender,
ethnicity, height, weight and skin color. Some soft biometric traits such as height, weight and
age, change over time. However, traits such as gender and ethnicity are permanent and stable.

- Predicting these soft biometric traits can be done reasonably well by human observers.
However, when having to deal with large datasets this process needs to be performed fast,
automatically and efficiently.

- Convolutional Neural Networks or CNNs are examples of discriminative models meaning that
they are designed to predict a target label given an observation (i.e. an image) as their input.
CNNs will be used to address the first objective of this project, the one of predicting gender and
ethnicity from static face images.

- The second objective concerns the synthesis of new face images with the required labels (i.e.
gender and ethnicity). This problem cannot be solved with discriminative models, but instead, it
requires the usage of generative ones. The goal of conditional generative models is the
synthesis of face images with the required gender and ethnicity conditions rather than
generating arbitrary faces.

### Current Progress :
* Achieved accuracy of 97.5% over 9778 test face
images without Data Augmentation.
* Used 'same' Paddings,NO strides. Model Architecture similar to ResNet .
* Increased dropouts . Added Batch Normalisations , Regularizers .
* Use of contour filters, like canny, and laplace filters to enhance the face image features before feeding to the model.
* Image processing using OpenCV : Applied data pre-processing techniques like contrast and local color normalisation, background
cropping .
* Phase 2: GANs for synthesis of face images . 
* Improving performance : ( Groupwise Curve Alignment ) Dynamic time warping (DTW) is an
essential point-to-point matching algorithm, which provides a solution
to the global optimal alignment path.
