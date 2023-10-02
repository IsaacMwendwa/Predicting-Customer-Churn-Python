# Marketing Analytics: Predicting Customer Churn in Python

## Introduction
* Customer Churn is when an existing customer, user, player, subscriber or any kind of return client stops doing business or ends the relationship with a company. It can be defined in a variety of ways:

  * **Contractual churn** is when a customer is under contract for a service and decides to cancel their service. This can be found in Cable TV, and SaaS products
  * **Voluntary churn** is when a user voluntarily cancels a service and includes Prepaid Cell Phones, Streaming Subsriptions
  * **Non-Contractual churn** is when a customer is not under contract for a service is the next example of churn, and includes consumer loyalty at a retail location or online browsing
  * **Involuntary churn** is when a churn occurs not at the request of the customer and includes, credit card expiration, or utilities being shut off by the provider.
*  Most likely, you as a customer have cancelled a service for a variety of reasons including: **lack of usage, poor service, or better price**. Being able to leverage this experience as well as your domain knowledge will help guide you in your churn modeling journey

## Problem Definition
* The dataset used here is a Telco Churn Cellular Usage dataset that consists of records of actual Cell Phone customers, and features
* The features of interest include: customer’s cell service (like voice mail and international calling), cost for the service, a customer’s usage, and a feature of whether the customer cancelled their service or not (i.e customer churn)
* Thus, churn here is defined by the "customer cancelling their cellular plan at a given point in time and is encoded in the dataset as no and yes"
* Thus, the goal is to build a model that uses the information about each customer in the dataset to classify whether or not a new customer will churn. This model, therefore, has two outcomes, or classes: Either a customer will churn, or not churn
* You can use exploratory data analysis to identify differences between these two classes that can help you better understand the drivers of customer churn. Do churners call customer service more often? Does one state have more churners compared to another?
* ![image](https://github.com/IsaacMwendwa/Predicting-Customer-Churn-Python/assets/51324520/b21c7058-d5af-4355-9c63-e6208116e4ce)

* ![image](https://github.com/IsaacMwendwa/Predicting-Customer-Churn-Python/assets/51324520/163fad10-2a21-4328-a472-c64c78bfaf11)
