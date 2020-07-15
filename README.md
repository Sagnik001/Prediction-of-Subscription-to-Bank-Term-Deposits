# Prediction of Subscription to Bank Term Deposits
# Problem Statement
  Client is a retail banking institution. Term deposits are a major source of income for a bank. A term deposit is a cash investment held at a financial institution. 
  Consumer's money is invested for an agreed rate of interest over a fixed amount of time, or term.

  The bank has various outreach plans to sell term deposits to their customers such as email marketing, advertisements, telephonic marketing and digital marketing.
  Telephonic marketing campaigns still remain one of the most effective way to reach out to people. However, they require huge investment as large call centers are hired 
  to actually execute these campaigns. Hence, it is crucial to identify the customers most likely to convert beforehand so that they can be specifically targeted via call.

  So In this project I will predict if a client will subscribe (yes/no) to a term deposit therefore this is defined as a classification problem.

# Data-Set
  This project will utilize a dataset of 45211 consumers and distributed by the UCI Machine Learning Repository. Here is the URL :      https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

  age--Age of the client (numeric) <br/>
  job--Type of job (categorical: admin/blue-collar/entrepreneur/housemaid/management/retired/selfemployed/services/student/technician/unemployed/unknown) <br/>
  marital--Marital status of the client (categorical: divorced/married/single/unknown ; note: 'divorced' means divorced or widowed) <br/>
  education--Education level (categorical: basic.4y/basic.6y/basic.9y/high.school/illiterate/professional.course/university.degree/unknown) <br/>
  default--Credit in default (categorical: no/yes/unknown)<br/>
  housing--Housing loan  (categorical: no/yes/unknown) <br/>
  loan--Personal loan (categorical: no/yes/unknown) <br/>
  contact--Type of communication (categorical: cellular/telephone) <br/>
  month--Contact month (categorical: jan/feb/mar/..../nov/dec) <br/>
  day_of_week--Day of week of contact (categorical: mon/tue/wed/thu/fri) <br/>
  duration--Contact duration (numeric) <br/>
  campaign--Number of contacts performed during this campaign to the client (numeric,includes last contact) <br/>
  pdays--Number of days that passed by after the client was last contacted (numeric; 999 means client was not previously contacted) <br/>
  previous--Number of contacts performed before this campaign (numeric) <br/>
  poutcome--Outcome of the previous marketing campaign (categorical: failure/nonexistent/success) <br/>
  Subscribed(target)--Has the client subscribed a term deposit?(binary: yes/no) <br/>



# Important note: 
1. Duration attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

2. There is no missing values
