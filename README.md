# ChurnGuard

E-Commerce Customer Churn: From Raw Data to Business Strategy

Project Motivation

This project started with a simple question: can we use data not only to predict which customers will leave an e-commerce platform but also to understand their story? I wanted to go beyond a simple classification task and complete the full loop from data analysis to actionable business strategy.

Using the popular Olist dataset from Kaggle, I set out to build a solution that could provide real value, answering not just "who?" but "why?" and "what should we do about it?".

My Journey Through the Data

This project was a step-by-step exploration of the customer lifecycle:

    First, I had to decide what "churn" even means in a non-subscription business. I dug into the purchase data to find a natural cutoff point for when a customer has likely been lost for good.

    With a target defined, I spent a lot of time in the data, getting a feel for it (EDA) and building features that I hypothesized would influence a customer's loyalty—things like their recency and frequency, delivery delays, and satisfaction with past orders.

    I then trained a Gradient Boosting model to put my hypotheses to the test, teaching it to distinguish between loyal and churning customers based on the features I'd created.

    For me, a model is only useful if you can learn from it. So, I used SHAP to have the model "explain itself," highlighting the top reasons people were leaving—was it late shipping? A bad product experience? Something else?

    Finally, I took off my data scientist hat and put on my analyst hat, using these insights to sketch out a few targeted retention campaigns that were backed by the data.

Tools of the Trade

    Data Wrangling & Analysis: Pandas, NumPy

    Plotting: Matplotlib, Seaborn

    Modeling & ML: Scikit-Learn, XGBoost, Optuna

    Explainable AI: SHAP
