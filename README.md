# Mobile Price Classification
# Overview
This project aims to classify mobile phones into different price ranges based on their features. The goal is to build a predictive model that can help in determining the price range of a mobile device given its specifications.

# Table of Contents
    Introduction
    Dataset
    Installation
    Usage
    Models
    Model Accuracy
    Results
    Contributing
    License
# Introduction
Mobile phones come with various features that determine their market price.By analyzing these features, we can build a machine learning model to predict the price range of a mobile phone. This can be particularly useful for manufacturers, retailers, and consumers to understand pricing strategies and market positioning.

# Dataset
The dataset used in this project is sourced from Kaggle. It contains information about different mobile phone specifications such as 
battery power, Bluetooth connectivity, clock speed, dual SIM capability, and more. Each record is labeled with a price range:

0: Low cost
1: Medium cost
2: High cost
3: Very high cost
# Features
    battery_power: Total energy a battery can store in one time measured in mAh
    blue: Has Bluetooth or not
    clock_speed: Speed at which microprocessor executes instructions
    dual_sim: Supports dual SIM or not
    fc: Front Camera mega pixels
    four_g: Has 4G or not
    int_memory: Internal Memory in Gigabytes
    m_dep: Mobile Depth in cm
    mobile_wt: Weight of mobile phone
    n_cores: Number of cores of the processor
    pc: Primary Camera mega pixels
    px_height: Pixel Resolution Height
    px_width: Pixel Resolution Width
    ram: Random Access Memory in Megabytes
    sc_h: Screen Height of mobile in cm
    sc_w: Screen Width of mobile in cm
    talk_time: Maximum time that a single battery charge will last when you are talking
    three_g: Has 3G or not
    touch_screen: Has touch screen or not
    wifi: Has wifi or not

# Models
Various machine learning models were tested for this classification task, including:

    Logistic Regression
    Support Vector Machine (SVM)
    K-Nearest Neighbors (KNN)
The best-performing model was chosen based on accuracy and other relevant metrics.

# Model Accuracy

# Logistic Regression
     62%
# KNearest Neighbors (KNN)
     95%
# Support Vector Machine (SVM)
     97%

# Results
The final model achieved an accuracy of X% on the test set. Detailed performance metrics and confusion matrix are available in the results directory.

# Contributing
Contributions are welcome! If you have any ideas or improvements, feel free to open an issue or submit a pull request.

Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a pull request
# License
This project is licensed under the MIT License
