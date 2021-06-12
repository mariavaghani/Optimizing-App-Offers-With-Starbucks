# Project Motivation
Starbucks is a multi-billion dollar company that has mullions of customers. In order to increase sales, Starbucks is conducting an experimental study using their company app. It is assumed that all the app users are either existing Starbucks customers or potential customers, since they have downloaded the app. Starbucks is looking to convert app interactions into sales by sending out different kinds of offers. They track limited demographics information about each customer and transactions made during the study.

The app stores age, income, and gender about each customer, as well as their transactions and interactions with the offers. Each customer received a different set of offers over time. After the study was completed, Starbucks sets forward a question, whether or not we could predict the likelihood of a given customer to complete an offer in an official way (aka, not accidentally).

The business does not want to send out offers, if the customer would have made a purchase anyway, they also do not want to send offer, if the customer does not bother to follow through. People do not want too much information flooding their apps. Having too many notifications, they may delete the app and the company may lose them as customers. So Starbucks would like to know what offers to send to a customer so the offer would get completed.

One of the biggest challenges of this project is that the system marks each offer as complete, even if the customer has not seen the offer, but made a purchase anyway. Starbucks would not prefer to send offers to these customers, since the sale would happen regardless of the offer, but the company had to give out the reward. The goal of this project is to process the data to exclude these kind of completions and predict the customers who would actually get influenced by the offer to make a purchase.

The article accompanying this project is available [here](https://maria-vaghani.medium.com/customer-segmentation-of-starbucks-customers-19332b9b7c92)

# Libraries Used:
- pandas
- numpy
- math
- json
- datetime
- collections, defaultdict
- tqdm
- seaborn
- matplotlib
- sklearn
- xgboost

# Overview
I. Data Pre-Processing
  Creating additional features and reformating data into customer-offer pairs
II. Exploratory Data Analysis
  Answering some business questions:
  1. What is the age distribution of Starbucks customers?
  2. What is the income distribution of Starbucks customers?
  3. How many people joined Starbucks membership each year?
  4. How many people abandoned each kind of offers? Which offer gets abandoned the most? Least?
  5. What is the rate of completion for each offer? How do they compare within each offer type?
  6. What is the general demographic of people who ignore offers, not viewing them?
  7. What is the general demographic of people who complete offers by accident?
  8. What is the distribution of total rewards and total amount spend by customers?
  9. What is the most popular offer? What is the least popular offer?
  
III. Machine Learning Algorithm and GridSearch
  Implementation and Machine Learning Model, selection of the best performing one, and its improvement, followed by evaluation of the model.

# Files
- Starbucks_Capstone_notebook.ipynb - project script
- README.md
- data/portfolio.json - json data provided by Udacity and Starbucks
- profile.json - json data provided by Udacity and Starbucks
- profile_df.csv - pre-processed and reformatted data frame used to implement Machine Learning model
- transcript.json - json data provided by Udacity and Starbucks

# Acknowledgements
This project was completed as part of Udacity Data Scientist Nanodegree. The data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app.

I would like to thank Udacity for the provided guidance and training, and thank Starbucks for providing such an amazing dataset.
