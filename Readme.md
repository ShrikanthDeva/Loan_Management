# Loan Management System

+ It's a user-friendly loan management application that lets customers easily request and pay back loans.
+ TECH STACK USED: Python, Django, SQLite3, JavaScript, HTML, CSS

## Features Of LMS

+ **Registration/Authentication of user** 
+ **Apply Loan**
+ **Loan Payments:**
+ **Loan Statements**

## 2 APPS
    + Loan App
    + Login App

## Loan App
### loanCategory -> 
    ( loan_name, creation_date, updated_date )
### loanRequest ->
    ( customer, category, request_date, status, amount, year, interest_rate, next_due, due_amount, paid_months, paid_amount )
  + FUNTIONS:
      + get_customer_income
      + get_customer_credit_score
      + get_loan_category
      + calculate_emi
      + update_due_date
      + pay_emi
      + isPaid
### loanTransaction ->
    (customer, loan, transaction, payment, payment_date)

## LOGIN APP


### CustomerSignup -> 
    ( user, aadhar_id, annual_income,  credit_score)
### Transaction -> 
    ( aadhar_id, date, transaction_type, amount )
### Tasks
    + FUNTIONS
      + calculate_credit_score
      + import transactions