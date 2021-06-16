# Find High-Risk Customers
## Overview

The subject of this analysis was a Credit Scoring dataset describing more than 200 hundred customers who took a loan in a bank. The dataset contains information about their age, gender, education, work experience, family and financial situation, and even their loan purposes. The project's main goal was to find a connection between specific customers' features and repaying their loans on time.

In the first step of the project, I obtained general information about the dataset and its variables and identified the main issues that should have been fixed before the analysis. Then I preprocessed the dataset and prepared for the exploratory analysis, working on all the dataset's flaws discovered at the previous stage. Finally, I found the riskiest category of customers by analyzing connections between repaying a loan on time and customer's number of children, marital status, level of income, their loan purposes.

## Data and Questions

The dataset is a CSV file [credit_scoring_eng.csv](https://github.com/aquamila/Find_High_Risk_Customers/blob/main/credit_scoring_eng.csv). 

Data Dictionary:

- __children__ - the number of children in the family
- __days_employed__ - how long the customer has been working
- __dob_years__ - the customer’s age
- __education__ - the customer’s education level
- __education_id__ - an identifier for the customer’s education
- __family_status__ - the customer’s marital status
- __family_status_id__ - an identifier for the customer’s marital status
- __gender__ - the customer’s gender
- __income_type__ - the customer’s income type
- __debt__ - whether the customer has ever defaulted on a loan
- __total_income__ - the customer’s income
- __purpose__ - a reason for taking out a loan

The following questions were investigated:   
 
- Is there a connection between having kids and repaying a loan on time?
- Is there a connection between marital status and repaying a loan on time?
- Is there a connection between income level and repaying a loan on time?
- How do different loan purposes affect on-time loan repayment?

## Technologies Used

- Jupyter Notebook
- Python with the following libraries and modules:
  - NumPy
  - pandas
  - Matplotlib
  - Seaborn
  - SciPy
  - NLTK
