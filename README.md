# Explainable-Customer-Churn-Prediction

This repository contains the code for Predicting customer churn in a subscription-based business such as a telecom or an online streaming service with predictions based on explainable AI techniques. This peoject is done as a part of coursework for the course Dependable AI under Dr. Richa Singh, IIT Jodhpur

## What is the project about

Losing clients or customers is referred to as customer attrition, customer churn, customer turnover, or customer defection.

Because keeping an existing customer costs much less than acquiring a new one, companies that provide telephone services, Internet services, pay TV, insurance, and alarm monitoring services frequently use customer attrition analysis and customer attrition rates as one of their key business metrics. Because reclaimed long-term consumers can be worth far more to a firm than newly recruited clients, companies from these sectors frequently have customer service units that work to win back departing customers.

By determining a customer's propensity for risk of churn, churn prediction models used in predictive analytics can forecast customer churn. These models are useful for concentrating customer retention marketing activities on the segment of the customer base that is most susceptible to churn because they produce a short prioritized list of possible defectors.

We wanted to conduct a customer churn analysis for this project and create a model that can forecast client attrition. Additionally, we have created a Flask app that can be used to determine a customer's estimated lifetime value and the reasons why they would cancel a subscription.

## How to run the code

Step 1: Clone the repository

    $ git clone https://github.com/ayushabrol13/Explainable-Customer-Churn-Prediction.git

Step 2: Select the directory

    $ cd Explainable-Customer-Churn-Prediction

Step 3: Install the required libraries

    $ pip install -r requirements.txt

Step 4: Run the app.py file

    $ flask --app app run

Step 5: Open the link in the browser

    $ http://127.0.0.1:5000/

## Final Customer Churn Prediction Flask app

![image](https://github.com/ayushabrol13/Explainable-Customer-Churn-Prediction/blob/master/images/website.png)

## Explainablity of the model

We have compared the explainability of Random Forest Classifier and a deep learning neural network MLP Classifier. We have used SHAP values to explain the predictions of the model. SHAP values interpret the impact of having a certain value for a given feature in comparison to the prediction we'd make if that feature took some baseline value.

We have explained and understood the Random forest model and the MultiLayerPerceptron model using explainable AI modules such as Permutation Importance, Partial Dependence plots and Shap values.

We see that the neural net model is way more complex than the random forest model and hence it is difficult to explain the neural net model. The random forest model is much simpler and hence it is easier to explain the random forest model.
This is due to the fact that the neural net model has a lot of hidden layers and a lot of neurons in each layer. This makes the model very complex and hence it is difficult to explain the model.

## Feature Importance Plots

### MultiLayerPerceptron


