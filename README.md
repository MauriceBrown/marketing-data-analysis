# iFood CRM data

This data is from iFood, a food delivery app in Brazil

The data consists of 2240 rows of customer details (income, number of children, education etc) for customers selected for a marketing campaign. There is also a variable ("Response") indicating wether or not the customer accepted the offer from the campaign. The github repo and project brief are linked below.

[GitHub repo](https://github.com/MauriceBrown/marketing-data-analysis)

[Project brief and data dictionary](https://github.com/MauriceBrown/marketing-data-analysis/blob/main/iFood%20Data%20Analyst%20Case.pdf)

[This Notebook](https://github.com/MauriceBrown/marketing-data-analysis/blob/main/iFood%20CRM.ipynb) is split into **four** sections:

1. **Data import and cleansing**
    - Import data and remove missing values
    - Create aggregations of data so that models contain fewer variables
2. **Data exploration**
    - Grouping the data by several variables and using the dependent variable ("Repsonse") to check whether there is a meaningful difference between the groups    
3. **Modelling**
    - Creating a model to predict the customer response based on variables chosen from the exploration phase
    - Two models are created:
        1. A random forest classifier (**more accurate**)
        2. A logistic regression classifier (**more easily interpretable**)
4. **Frequency, recency, monetary value (FRM) analysis**

There are "stream of consciousness" notes throughout the notebook to give an indication of the thought behind specific actions (data groupings, chart creation etc).

[Click here to view the notebook](https://github.com/MauriceBrown/marketing-data-analysis/blob/main/iFood%20CRM.ipynb)
