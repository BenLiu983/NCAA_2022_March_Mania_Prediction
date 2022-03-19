# NCAA 2022 March Mania Prediction

## 1. Introduction

Kaggle competition

Another year, another chance to predict the upsets, call the probabilities, and put your bracketology skills to the leaderboard test. In our eighth annual March Machine Learning Mania competition, Kagglers will once again join the millions of fans who attempt to predict the outcomes of this year's US men's college basketball tournament. But unlike most fans, you will pick the winners and losers using a combination of rich historical data and computing power, while the ground truth unfolds on television.

You're provided data of historical NCAA games and are encouraged to use other sources of publicly available data to gain a winning edge.

## 2. Code and Packages

* Python Version: 3.9

* Packages: pandas, numpy, sklearn, matplotlib, seaborn, lightgbm

## 3. Objectives

<img width="723" alt="goal" src="https://user-images.githubusercontent.com/64850893/159124819-c0ec08e9-f85d-4edc-9037-9631e05bd184.png">

## 4. Data Sources

mens-march-mania-2022.zip

## 5. Data Preparation and EDA

### 5.1 Train set

* Seeds
* Season Stats
* Computer Ratings
* Metric difference

<img width="1251" alt="df_train" src="https://user-images.githubusercontent.com/64850893/159125378-5592d54d-7693-4095-aaee-d9cf2eefc7fc.png">

### 5.2 Test set

* Seeds
* Season Stats
* Computer Ratings
* Metric difference

<img width="1227" alt="df_test" src="https://user-images.githubusercontent.com/64850893/159125184-92c2f0d4-409b-4811-bc8d-be16c29cb8c0.png">

## 6. Modelling (LightGBM)

### 6.1 Procedure

* Train-test-split
* Cross validation
* Oversampling
* Machine learning algorithms (Logistic Regression and Random Forest)
* GridSearchCV

### 8.2 Model Performance:

<img width="1011" alt="model_sum" src="https://user-images.githubusercontent.com/64850893/155891672-6e74397d-6133-4c9e-966d-d56be9b4a38c.png">

* Considering the prediction accuracy as well as the model simplicity, Logistic Regression in Case 2 would be the optimal model, since it is more straightforward to interpret, with relevantly high prediction accuracy.

### 8.3 Confusion Matrix (Logistic Regression): 

<img width="470" alt="cm_git" src="https://user-images.githubusercontent.com/64850893/155891735-bcfcc378-3bc3-4f0b-9d32-8691ab1ed777.png">

### 8.4 Feature Importance (Logistic Regression): 

<img width="921" alt="lr fea c2" src="https://user-images.githubusercontent.com/64850893/155887997-5a75e3d5-f43c-4752-b055-c1db284e5c3c.png">

* Positive features – previous brand as MJN, negative features – previous brand as other brands.
* If the previous brand is "Abbott Specialty", it plays a positive impact on current MJN Stage 2 brand choice.
* Number of children is negatively influencing the MJN Stage 2 brand selection .

## 9. Conclusion

* Drive MFB members to become Stage 1 users, due to the fact that the previous brand is a primary indicator.
* Maintain/boost the quantity/quality of email campaigns, since the email performance is an essential driver.
* Conduct experimentation to market users with only 1 child, because this metric negatively impact the outcome.

## 10. Next Steps
 
* Modify the output and input variables to tailor other business use cases.
* More experimentation in terms of variables and models.
