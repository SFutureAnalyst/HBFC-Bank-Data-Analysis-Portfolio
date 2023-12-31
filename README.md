# HBFC-Bank-Data Analysis Project - Portfolio
<br>
<br>

<img src = "https://images.unsplash.com/photo-1501167786227-4cba60f6d58f?q=80&w=1000&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8YmFua3xlbnwwfHwwfHx8MA%3D%3D">


# Table of Contents:
  - [Problem Statement.](#problem-statement)
  - [Data Description..](#data-description)
  - [Objective Task](#objective-task)
  - [Observation.](#observation)

## Problem Statement:

The goal of HBFC bank is to sell more personal loans to their savings account holders. The bank wishes to launch a campaign to sell personal loans, but first wishes to analyze previous marketing campaign data in order to better understand the profile of potential loan customers. This will assist them in future targeted approaches to prospective customers. The bank has approached you to assist them with the analysis of previous campaign data.

The bank basically has two customers,
• Liability customers – They deposit the money in the bank and pays interest against 
the deposited money.

• Asset customers - They borrow money (take different types of loan) from the bank 
and the bank charges interest against the borrowed money.

The bank currently has a small number of asset/loan customers. The bank wishes to increase its revenue by expanding its customer base of "asset customers." Last year, the bank conducted a
They successfully converted 9% of their existing "liability customers" to "asset customers" through this campaign. This has encouraged the bank to implement a more targeted marketing campaign in order to increase the success ratio while spending the least amount of money.



## Data Description

The file contains data of 5000 customers. It includes, 

• Customer demographic information (age, income, etc.), 

• Relationship with the bank (mortgage, securities account, etc.) 

• Customer response to the last personal loan campaign (Personal Loan). 

 • Among the 5000 customers, only 480 (9.6%) customers have accepted the personal loan in the last year campaign.


![image](https://github.com/Ginga1402/HBFC_Bank_Analysis/assets/130181481/e355356d-1c9f-4b94-8882-64a92785aea8)
![image](https://github.com/Ginga1402/HBFC_Bank_Analysis/assets/130181481/1478b072-ce21-4c6b-9f38-7ac447913ad1)



## Objective Task:

• As a consultant, you must perform preliminary data analysis (EDA) and visualization to  understand the profile of customers having savings account, who took personal loan in the last marketing campaign VS customers who didn’t take it up.

• Using EDA identify profile of customers whom bank can target for selling personal loan.

In order to do this analysis, you are expected to solve these questions:

1) What percentage of the bank’s customers (according to the data) have availed  Personal Loans vs the ones who have not availed it?

2) Generate a table with min, max, median & average for all numeric variables (age, experience, income, family members, CCAvg, Mortgage)

3) Create a new categorical variable for Experience using 4 categories –

         -  0 to 10 years 

         -  11 to 20 years 

         -  21 to 30 years 

         -  30+ years.

Plot a bar graph for this new categorical variable

[Hint – You may make use of if else/nested if statements to accomplish this task. You  can refer how Income_Category has been created in the dataset]


4) Create a scatter plot of the Age and the Experience variable. What do you observe?

5) What are the top 3 areas (ZIP Codes) where the bank’s customers are located?

6) How many customers have a combination of Fixed Deposits and Credit Cards but not Personal Loan?

7) What is the median income of the customers who have availed personal loans and compare it with the median income of those customers who have not availed personal loans? What do you infer?

8) Create 4 separate Pivot Tables. Summarize your data by percentage values.

      • Education vs Personal Loan

      • TD Account Vs Personal Loan

      • Online vs Personal Loan

      • Income_Category vs Personal Loan

[Hint: Please drag Personal Loan to the Columns area while creating the Pivot Table to get the required values]

9) Analyze the Pivot tables created in the previous question and state any anomaly that you observe. Which categorical variables appear most important for your further study if you want to analyze which customers are most likely to take personal loans and why?

10) In the last campaign, bank reached out to 5000 customers out of which 480 customers accepted the personal loan offer. The bank incurred a huge cost in running a marketing campaign to reach out to so many customers. This is where you as a strategic business consultant step in. You are tasked to optimize the cost of this campaign by identifying 
the correct target base (without significant reduction in number of acceptances of offers). The bank can then send Personal Loan offers to these target customers who have a higher chance of accepting the offer. Based on your analysis, what strategy would you suggest to the management of HBFC bank?

## Observation:

 Referring to the analysis and the source data provided I realized that:
                                                                                                                             
1. In order to efficiently use our resource & get our product sold to the customer's, we need to target some specific groups of customers instead of putting all our resources at whole population. 

2. Considering the Education Criteria we should focus on graduates & professional's . If we observe the maximum customers as classified on education criteria are undergraduates but the conversion rate is the least in this. So we should focus on graduates & Professionals.

3. The customers earning more than $100,000  have the maximum chances of buying our product.                 

4. While analyzing, I came to find out that the customers who are not using online banking  tend to take more personal loan rather than the one's who are using online banking.We should focus more on them .


A table is presented in the worksheet which will help you to have a more clear picture of my analysis.

With respect to maximizing  our  resources & convert Liability Customers to Asset Customers we should focus on the above samples of customers rather than the whole population.
