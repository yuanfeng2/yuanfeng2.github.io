---
layout: post
title: Detecting Solar Panels From Satellite Imagery
subtitle: 
cover-img: /assets/img/solar2.png
thumbnail-img: /assets/img/solar2.png
share-img: /assets/img/path.jpg
---

Due to the rising concern over the pollution from the current energy sources, solar power has been regarded as one of the most promising methods to provide energy at low pollution and low environmental footprint. As of the end of 2018, solar power accounted for around 1.6% of the total power consumed in the United States amounting to 64.2 GW. Furthermore, solar power has ranked consistently as the first or second fastest growing power source in the US since 2013. Moreover, unlike nuclear, wind or hydrothermal energy solar energy can be easily harnessed from rooftops using photovoltaic cells. Solar power using photovoltaic solar panels is a quickly growing source of power across US households with increasing rates of adoption. Tracking the installation of solar panels across the nation to study the rates of adoption is often cumbersome and inaccurate - for such methods often involve self-reporting, monitoring sales of solar panels etc. A much more recent technique to track the harnessing of solar panels across the nation involves using machine learning models on satellite imagery. These models use a variety of techniques, both simple and intricate, to accurately identify the existence of solar panels in satellite images with high accuracy.  

<div align="center">
<img src="https://raw.githubusercontent.com/yuanfeng2/yuanfeng2.github.io/master/assets/img/solar.png" >
</div>

In order to obtain a thorough understanding of the current state of individual solar panel installation and usage both on a local and national scale, an automated method of identification is required for classifying the existence of solar panels based on pre-processed satellite images. In the notion of machine learning algorithms, the original model is built on the basis of an educated estimation and exploration of the dataset and trained multiple times on the training data with possible future stages of parameter tuning. The model performance will be evaluated based on its test data, which in this case are images unseen by the model beforehand. The finalized model will be able to provide classification on newly imported images in a scalable fashion. With the implementation of machine learning to solar panel image classification, the cost and time required to identify installed solar panels could be potentially reduced and will help the industry better provide renewable, clean and affordable alternative energy sources.

In this project, we discuss four different approaches to identify and classify solar panels in satellite images. We lay specific emphasis on two different feature extraction methods namely Histogram and Gradients (HOG) and Color Filter Feature Extraction (CFFE). We then use a K-Nearest Neighbour (KNN) Classifier in both cases to classify the images. These methods achieved an area under the curve (AUC) of 0.800 and 0.837 respectively. In our third approach, we develop an ensemble model combining both the earlier described feature extraction methods. The AUC in this case was 0.888. Finally we developed a Convolutional Neural Network (CNN) with an AUC of 0.983. We compare the different approaches and analyze where they performed well and where they can be improved.

The project code can be found [here](https://github.com/yuanfeng2/solar_panel_detection_CNN), and a pdf of the report is located [here](https://github.com/yuanfeng2/solar_panel_detection_CNN/blob/master/Solar%20Panel%20Detection.pdf).
