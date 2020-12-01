# Starbucks-targeted-Marketing---Model-to-predict-propensity-of-customers-to-complete-offer
Dataset downloaded from kaggle : https://www.kaggle.com/blacktile/starbucks-app-customer-reward-program-data
## Project description:
This machine learning model can be used to predict whether a customer will respond to a purchase offer sent by Starbucks through their mobile app. The model is based on a customer level dataset and will include demographic attributes related to the customer such as age, gender etc. and will also utilize the behavioral attributes of the customer, which are customer responses to offers sent. The model also utilizes offer level attributes such as offer type. The model outputs propensity of customer for different offer usage levels, from which top ranked customers can be picked for targeted marketing. Since tree based and deep learning models are used, the final selected model can also tell us the driving factors of customer propensity to convert, which in turn will help the company to devise strategies to send offers to different class of customers.
## Description of Files/Folders
### Dataset:
data - Folder contains 3 datasets in JSON format, mentioned below:
1. Portfolio: This file contains metadata of the 10 unique offers provided by Starbucks
2. Profile: This file contains the demographic data for the Starbucks app customers. This contains data for 17,000 unique app customers
3. Transcript: This file contains user activity data pertaining to the offers given to the app customers and the event/response associated with the offer for a particular customer, such as offer viewed, offer completed etc.
### Python scripts:
1. Starbucks propensity to convert_Autokeras.ipynb - Deep neural network model using Autokeras (open source NN alternative to Google's AutoML)
2. Starbucks propensity to convert_CatBoost.ipynb - Catboost model
3. Starbucks propensity to convert_DNN.ipynb - Deep neural network model with manually added layers
4. Starbucks propensity to convert_LightGBM WITH SHAP.ipynb - LightGBM model with SHAP (SHapely Additive exPlanations) for model explainability
5. Starbucks propensity to convert_XGBoost.ipynb - XGBoost model
