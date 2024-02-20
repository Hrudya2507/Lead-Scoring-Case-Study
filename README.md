# Lead-Scoring-Case-Study
Case study for UpGrad

# Problem Statement:
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%. 

Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone.

# Goals:
1. To build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads.
2. To adjust to if the company's requirement changes in the future so you will need to handle these as well.

# Approach:
The method used in this case study is Logistic Regression. Logistic Regression is a supervised classification model. It allows you to make predictions from labelled data, if the target (output) variable is categorical.

In this data set, our target variable is “Converted”, which implies whether a potential lead got converted as payable customer or not.

# Steps:

1. Importing libraries and Understanding data : Imports necessary libraries, understands and read the given data.
2. Data Cleaning : Check for missing values and dropping the columns which are not useful for analysis.
3. Data Visualization: Univariate and Bivariate analysis using sns and matplotlib
4. Data Preparation: Creating dummy variables for categorical variables with multiple levels.
5. Train – Test Split : Splitting the data into train and test datasets.
6. Feature Scaling: Scaling using MinMaxScaler() to ensure all the variables are of same scale.
7. Correlation: Checking the correlation using heat map.
8. Model building: Using RFE method as the number of variables are huge in number.
9. Model evaluation: Evaluating the model build on train dataset.
10. Plotting ROC Curve
11. Finding optimal cut-off point
12. Making predictions on test datasets



