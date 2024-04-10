# Credit-EDA

### <i>PROJECT OVERVIEW</i>
This case study aims to identify patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study.


### <i>Data Sources</i>
This dataset has 3 files as explained below: 

1. 'application_data.csv'  contains all the information of the client at the time of application.
The data is about whether a client has payment difficulties.
2. 'previous_application.csv' contains information about the client’s previous loan data. It contains the data on whether the previous application had been Approved, Cancelled, Refused or Unused offer.
3. 'columns_description.csv' is data dictionary which describes the meaning of the variables.


### <i>Tools</i>
Python Notebook

### <i>Data Cleaning/Preparation</i>
In the initial data preparation phase, the following tasks are performed:
1. Data loading and inspection
2. Handling missing values
3. Data Cleaning and formatting


### <i>Exploratory Data Analysis</i>

Using EDA to analyse the patterns (such as Outliers, Data Imbalance, etc.) present in the data.
When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. It contains two types of scenarios:
1. The client with payment difficulties: he/she had late payment more than X days on at least one of the first Y instalments of the loan in our sample.
2. All other cases: All other cases when the payment is paid on time.

When a client applies for a loan, there are four types of decisions that could be taken by the client/company):
Approved, Cancelled, Refused and Unused offer

In this case study, EDA is used to understand how consumer attributes and loan attributes influence the tendency to default.


### <i>Data Analysis</i>
The below analysis is used to solve the right problem and draw insights which is coherent with the needs of the business. The analysis has a clear structure and the flow is easy to understand.
1. Univariate analysis
2. Segmented Univariate analysis
3. Bivariate analysis

### <i>Presentation and Recommendations</i>
- The presentation has a clear structure, is not too long, and explains the most important results concisely in simple language.
- The recommendations to solve the problems are realistic, actionable and coherent with the analysis.

## <i>CONCLUSION</i>
<b>1. Banks should focus less on the following groups as they have higher unsuccessful payments rate-</b>
- Clients with 'Secondary/Secondary Special' education qualification.
- Clients who are 'Young', especially with 'Low' Income..
- Clients whose loans have been 'Refused', 'Cancelled'.

<b>2. The following have successful payment rates and highly recommended groups -</b>
- Clients with 'Approved Consumer' loans.
- 'Tourism' goods category have highest success payment rate.
- 'Senior Citizen' age group have the most success payments.
