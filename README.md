# Credit Card Analysis of Czech Bank


## Description

> The bank managers want to know, who is a good client (whom to offer some additional services) and who is a bad client (whom to watch carefully to minimize the bank loses). Fortunately, the bank stores data about their clients, the accounts (transactions within several months), the loans already granted, the credit cards issued the bank managers hope to improve their understanding of customers and seek specific actions to improve services. 


## Dataset

> https://webpages.charlotte.edu/mirsad/itcs6265/group1/domain.html 


## Outline

- Data Extraction
- Data Cleaning
- Exploratory Data Analysis
- Data Preprocessing
- Cluster Analysis


## Objective

> Using agglomerative and kmeans clustering algorithms to analyse the bank data in order to extrapolate from it the type of customer who makes a good candidate for a credit card.


## Summary of Findings
- cluster 0: ***Insufficient credit history***
    - young age
    - moderate loan amount
    - moderate duration
    - all gender
    - mostly non-cc holders
    - the majority of loan statuses are 'no loan', 'no problems', and 'OK thus far'
    - withdrawal
    - mostly household and insurance payments
- cluster 1: ***student loans***
    - the youngest age
    - the largest loan amount
    - long duration
    - all gender
    - mostly non-cc and junior card
    - the majority of loan statuses are 'no problems', 'OK thus-far', and 'loan not payed'
    - withdrawal
    - mostly household and loan payment
- cluster 2: ***secured debt holders***
    - young age
    - moderate loan amount
    - moderate duration
    - all gender
    - mostly classic and gold card 
    - the majority of loan statuses are 'no problems' and 'OK thus-far'
    - withdrawal
    - mostly household and insurance payments
- cluster 3: ***fall behind on payments***
    - oldest age
    - the lowest loan amount
    - short duration
    - all gender
    - mostly non cc
    - no loan status
    - collection from another bank
    - credit
    - pension
- cluster 4: ***young debtor women***
    - young age
    - the lowest loan amount
    - short duration
    - women
    - mostly non cc and junior card
    - no loan status
    - withdrawal
    - mostly household
- cluster 5: ***young debtor men***
    - young age
    - the lowest loan amount
    - short duration
    - men
    - mostly non cc and junior card
    - no loan status
    - withdrawal
    - mostly household


## Business Recommendation
- cluster 0: ***Insufficient credit history***
  - Good candidates
  - Ask to use credit card
- cluster 1: ***Student loans***
  - Need to watch carefully
- cluster 2: ***Secured debt holders***
  - Good clients
  - Ask to add credit card
- cluster 3: ***Fall behind on payments***
  - Offer to help with financial planning
- cluster 4: ***Young debtor women***
  - Offer some additional services
- cluster 5: ***Young debtor men***
  - Offer some additional services


## Codes


## Results


## Developer

> **NUR INNA ALFIANINDA**

> http://cv.alamazed.com/
