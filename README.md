# Analysis-and-prediction-of-online-shoppers-purchasing-intention-using-various-algorithms-CAPSTONE

In this project, we aim to construct a real-time prediction machine learning system for online shopping environment. We use an online retailer data to perform the experiments. In order to predict the purchasing intention of the visitor, we use aggregated page view data kept track during the visit along with some session and user information as input to machine learning algorithms. Oversampling/Undersampling and feature selection pre-processing techniques are applied to improve the success rates and scalability of the models. 

Our findings support the argument that the features extracted from clickstream data during the visit convey important information for online purchasing intention prediction. The findings show that choosing a minimal subset of combination of clickstream data aggregated statistics and session information results in a more accurate and scalable system.

Keeping last mile goal of having predictive model in mind, we used different data cleansing, data balancing imputation methods to arrive at dataset fit for development of predictive models. The project includes creation of various analytical models for predicting and classifying users as Revenue or Non-revenue generating using Logistic Regression, Ensemble methods, Bagging, Boosting techniques etc. The base models are benchmarked against Hyperparameter tuned model outputs and considering all factors and final goal in mind best model is advised.


Techniques: Predictive Modelling, Machine learning, Hyperparameter tuning
Tools: Python, Tableau
Domain: Marketing and Retail Analytics

Analysis shows that it is possible to predict a site visitors buying behavior within a certain level of confidence based on the features we were able to pull from the data set. Considering the real time usage of the proposed system, achieving better or similar classification performance with minimal subset of features is an important factor for the e-commerce companies since a smaller number of features will be kept track during the session. XGBoost model turned out to be the best model overall.
