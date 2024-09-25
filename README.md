# Multimodal-MRI-Clinical-Survival-Prediction-in-Glioma-using-CNN-and-transfer-learning
Contributors: Qianwen Li, Ninghui Hao, Shuhua Xu, Taiyang chen

<a id="contents"></a>
## Table of content
- [**Part 1. Motivation, context, and framing of the problem**](#part1)
    - [Project Introduction](#intro)
    - [Motivation and Problem Statement](#motivation)
- [**Part 2. Description of the data**](#part2)
    - [Clinical data](#clinic)
    - [MRI image data](#image)
- [**Part 3. Feature Engineering and Comprehensive EDA Review**](#part3)
    - [Clinical data](#clinic_eda)
    - [MRI image data](#image_eda)
- [**Part 4. Baseline models and result assessment**](#part4)
    - [2D CNN baseline model](#2dcnn)
    - [Transfer Learning](#transfer)
    - [Classifier for clinical data](#classifier_clinic)
    - [Transfer learning with clinical data](#transfer_clinic)
    - [Autoencoder](#autoencoder)
    - [3D CNN Selection and Justification](#3dcnn)
    - [3D CNN without the black regions](#3dcnn_new)
- [**Part 5. Final Model and discussion**](#part5)
    - [Flow Chart of our model](#flow_chart)
    - [Steps for our final model](#steps)
    - [Conclusion](#conclusion)
    - [Discussion](#discussion)

  ### Flow Chart of our model<div id='flow_chart'></div>
![Model framework](/Model_framework.png)
  
