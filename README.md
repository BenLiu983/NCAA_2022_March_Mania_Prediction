# NCAA 2022 March Mania Prediction

## 1. Introduction

Kaggle competition

Goal: Predict the outcomes of this year's US men's college basketball tournament. Pick the winners and losers using a combination of rich historical data and computing power, while the ground truth unfolds on television.

## 2. Code and Packages

* Python Version: 3.9

* Packages: pandas, numpy, sklearn, matplotlib, seaborn, lightgbm

## 3. Metric of Interest

<img width="723" alt="goal" src="https://user-images.githubusercontent.com/64850893/159124819-c0ec08e9-f85d-4edc-9037-9631e05bd184.png">

## 4. Data Sources

mens-march-mania-2022.zip

## 5. Data Preparation and EDA

### 5.1 Train set

* Seeds
* Season Stats
* Computer Ratings
* Metric difference

<img width="1121" alt="df train 3" src="https://user-images.githubusercontent.com/64850893/159127735-120eca04-e81d-410c-8805-4bf59cf4a76a.png">

### 5.2 Test set

* Seeds
* Season Stats
* Computer Ratings
* Metric difference

<img width="1121" alt="df test 2" src="https://user-images.githubusercontent.com/64850893/159127628-79a14a75-3c99-46be-858c-2e70ad54de87.png">

## 6. Modelling (LightGBM)

### 6.1 Procedure

* Train-test-split
* Cross validation
* Model implementation

### 6.2 Model Performance

<img width="559" alt="model output" src="https://user-images.githubusercontent.com/64850893/159127293-4223facc-71ee-4f1d-ae73-38db0e6559ca.png">

The submission log loss is 0.42.

### 6.3 Feature Importance

<img width="1129" alt="fea imp" src="https://user-images.githubusercontent.com/64850893/159127392-5a3fea2c-faa0-4640-9a48-9c86a8b7668a.png">

* Computer rating and avg scoring margin are the top 2 critical features.

## 7. Future Steps

* Incorporate more features.
* Experiment various models.


