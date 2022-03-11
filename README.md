# Churn at Flatiron Communications

![image](https://user-images.githubusercontent.com/96458808/157768617-494374d0-7b78-40cf-ac06-bb6bef64a0ff.png)

Authors:  [Chris Helmerson](https://github.com/chris161011), [Richard Hinds](https://github.com/RH3421), and [Olamide Olayinka](https://github.com/olamide-h)

## Business Problem
The stakeholder is Flatiron Communications.  The stakeholder has approached us to find out how they can reduce churn with their company. So we are tasked with 
building a classifier to predict whether a customer will ("soon") stop doing business with our stakeholder. Optimize to reduce amount of money lost due to churn. This is a binary classification problem.

So what is the layout of the cellular market and what is “Churn”? There is currently massive competition between 6 major cellular providers. “Churn” is a jargon term that effectively means customer turnover. There is a major problem with churn within the industry as new cellular customers are arriving at an all time low and with an average Churn Rate 22% per year.  9 out of 10 customers have churned in the last 5 years with about 1/2 of that Churn being attributed to nonpayment. Given that 1 in 4 customers are churning each year, retaining those existing customers has never been more important.

## Data and Preparation
Our data for this project was sourced from kaggle : https://www.kaggle.com/jpacse/datasets-for-churn-telecom. The data set contained 58 columns and a totoal of 51047 entries  with our target column being churn. After importing the data set, we continued with data cleaning and filtering. We dropped the null values in the dataset as well as drop columns that did not fall within our business problem. Futhermore, we converted the 'Service Area' column to Zipcode. In additon to converting our cartergorical columns to numeric values to allow for modeling going forward. This cleaning resulted in us having a total of 49752 entries with 51 columns. 35507 entries classified as customers who did not churn, while 14245 entries classified as customers who did churn. 


### Methods
Our dataset comes from an anonymous top 6 cellular provider and contains information on approximately 50,000 customers, collected through 2014. As stated previously, about half of churn is due to nonpayment, though our dataset only contains data of those who churned voluntarily. 
We used Scikit Learn as well as Sci-py to validate that our model. 


## Modeling

### Baseline Model



### Model 1



### Model 2




### Model 3





### Model 4


### Final Model




### Conclusions 

We identified the 3 most impactful predictors of churn from our analysis:

  1. Customers are 1.45x times as likely to churn for every day that they hold the same cell phone.
  2. Customers are 1.23x times as likely to churn for every additional subscriber added onto a plan.
  3. Customers are 1.16x times as likely to churn for every 1% increase in charges.

### Recommendations

Based on our analyses we recommend our stakeholder implement 3 targeted approaches to reduce churn:

  1. Offer discounted or complimentary cell phone upgrades for loyal customers to receive the latest devices. 
  2. Create  a loyalty program to reward multiple subscriber customers.
  3. Control customer charges by avoiding increasing fees on customers bills. 

### Next Steps
In the near Future, we want to develop a team tasked with proactively addressing churn. This team would be tasked with handling all the predictors that can be seen to contribute to churn. Furthermore, we want to feature engineer our data towards regions. This would allow us to develop localized deals based on a customer's service area. This would come down to using Zip code data as well State data.

## For More Information
View the full analysis via the [Jupyter Notebook](https://github.com/chris161011/P3_Project/blob/main/Main%20Notebook.ipynb).

