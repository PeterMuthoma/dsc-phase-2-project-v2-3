# Predicting-House--Prices-in--King County-Washington
---

> Project Contibutors: 

> Date: 06/09/2023

![cutomer churn header](https://raw.githubusercontent.com/GayasuddinMohd/House-Price_Prediction/main/House%20Image.avif)

---

### Table of Contents
- [Understanding The Context](#understanding-the-context)
- [Project Deliverable](#project-deliverable)
- [Recording the Experimental Design](#recording-the-experimental-design)
- [Summary Of Findings](#summary-of-findings)
- [Recommendations](#summary-of-findings)
- [Challenging your Solution](#challenging-your-solution)

---

## Understanding The Context

If you want to work for a top company in Seattle, you might be curious about how much it costs to live in King County. This is the largest and most populated county in Washington State, where Seattle and its suburbs are located. About 10 Fortune 500 Companies have their headquarters here, such as Starbucks, Nordstrom, Alaska Airlines, Costco, Expedia, Microsoft, and Amazon. Microsoft and Amazon are among the Big Five tech companies that many people aspire to join.

But finding a house in King County is not easy. There are many factors that affect the price, such as the number of bedrooms, bathrooms, and floors. You might have a different preference than someone else. Wouldn't it be nice if you could estimate the price of your ideal house based on the features you want? That way, you could plan ahead and make your dream house a reality.

#### Technologies and Tools

- Python
- Pandas
- Numpy
- Matplotlib
- Scikit-Learn

[Back To The Top](#Predicting-House--Prices-in--King County-Washington)

---

## Project Deliverable
- A non-technical presentation
- A Jupyter Notebook
- A GitHub repository

[Back To The Top](#Customer-Churn-Predicition--Classification-Analysis)

---

## Recording the Experimental Design
1. Load libraries and dataset.
2. Deal with duplicates and missing data.
3. Find and deal with other anomalies.
4. Drop unnecessary columns.
5. Perform univariate and bivariate analysis.
6. Test for multicollinearity.
7. Data modelling.
8. Summarize findings.
9. Make recommendations.
10. Challenge solution.

[Back To The Top](#Customer-Churn-Predicition--Classification-Analysis)

---

## Summary Of Findings
* This dataset is very biased: it has disproportionate numbers of those houses vs those without international plans, and of those who churned vs those who didn't. Also, this dataset had more records of customers from Area Code 415. Hence, the results cannot really be trusted.

* However, from our analysis, we see that customers who made at least 2 calls to customer service are likely to churn.

[Back To The Top](#Customer-Churn-Predicition--Classification-Analysis)

---

## Recommendations
The company should come up with a solution that caters to customers that make two or more calls to customer service. They should also collect more data, preferably those that will make the current dataset more balanced, e.g., more customers from Area Codes 408 and 510, more customers who churned, and more customers subscribed to the international plan.

[Back To The Top](#Customer-Churn-Predicition--Classification-Analysis)

---

## Challenging your Solution
* Firstly, a balanced dataset needs to be obtained, where the differences between the distinct values in the 'international_plan' and 'churn' variables are not so great.

* Secondly, all other assumptions need to be met, such as no influential values (outliers)in predictor variables before applying logistic regression.

* Finally, hyperparameter tuning should be carried out on the current models to improve them.

[Back To The Top](#Customer-Churn-Predicition--Classification-Analysis)

---


[Back To The Top](#Customer-Churn-Predicition--Classification-Analysis)



