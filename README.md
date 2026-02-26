# Loan Borrowers Reliability Analysis

## Introduction

The customer for this project is the bank’s credit department. The task is to determine whether a client’s marital status and number of children affect their ability to repay a loan on time. The dataset provided by the bank contains statistics on customer creditworthiness.

The findings from this analysis will later be used to improve a credit scoring model - a specialized system that assesses a potential borrower’s ability to repay a loan to the bank.

## Prerequisites

- Jupyter Notebook
- Python 3

## Data Description

- `children` - number of children in the family,
- `days_employed` - total work experience (in days),
- `dob_years` - client's age (in years),
- `education` - client's educational level,
- `education_id` - education level identifier,
- `family_status` - marital status,
- `family_status_id` - marital status identifier,
- `gender` - client's gender,
- `income_type` - employment type,
- `debt` - was there any debt on repayment of loans,
- `total_income` - monthly income,
- `purpose` - purpose of the loan.

## Notes

`data.csv` is private and cannot be shared. Example of data:

```csv
children,days_employed,dob_years,education,education_id,family_status,family_status_id,gender,income_type,debt,total_income,purpose
1,-8437.673027760233,42,высшее,0,женат / замужем,0,F,сотрудник,0,253875.6394525987,покупка жилья
1,-4024.803753850451,36,среднее,1,женат / замужем,0,F,сотрудник,0,112080.01410244203,приобретение автомобиля
0,-5623.422610230956,33,Среднее,1,женат / замужем,0,M,сотрудник,0,145885.95229686378,покупка жилья
3,-4124.747206540018,32,среднее,1,женат / замужем,0,M,сотрудник,0,267628.5503294142,дополнительное образование
```
