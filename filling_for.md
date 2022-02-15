# Title

End to end Credit scoring

# Author

Ahmad Zaenal

# Email

ahmadzaenal125@gmail.com


# Introduction

Ahmad Zaenal - Ahmad Zaenal is a data scientist with experience in credit scoring, algorithm trading and insurance. He interested in machine learning,data warehouse/lake technology,web application. Currently he work in a start-up that running in food booking business. 


# Keyword

Credit scoring, end-to-end, data.table, plumber


# Abstract

Credit scoring is a most common case in machine learning. It really help financial industry to assess credit worthiness of debtor become faster and efficient. However, until now the reference is still limited. We know that there are books that written about it, but it intended to SAS user. On the internet there also a reference but it mainly covers the machine learning part. As a person who involved in credit bureau industry, the problem was not just machine learning. The are many problems that are not covered in reference such as matching identity, data preparation with snapshot, deploy the model, etc. Thus, in this tutorial I would like to discuss about the end-to-end credit scoring modeling from data wrangling until the model deployment using plumber. Usually, the financial data is huge, this we will focus using data.table package. 

# Intended audience

This tutorial is intended to new R users especially those who have finance background, advanced R user also welcome to join if they would like to know more detail about credit scoring.
The prerequisites is of course knowing and R base at least familiar using the logistic regression model.


# Tutorial Outline

- Introduction
  * credit scoring 
  * data.table
  
- Data wrangling process
  * Good and Bad definition
  * Observation and outcome period
  * Identity matching
  * feature engineering
  * binning
  
- Modeling process
  * split train testing using snapshot based
  * modeling
  * Build scorecard
  * model evaluation
  
- Model Deployment
 * deploy model using plumber
  