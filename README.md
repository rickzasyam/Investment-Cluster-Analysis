# Mutual-Funds-Cluster-Analysis

# Overview Data 

I. Users Dataset
DATA DICTIONARY - Users Dataset

user_id : Client ID on the platform

register_import_datetime : user register date for the first time

user_gender : gender of user

age : age of user

user_occupation : user's occupation

user_income_range : user's income range

referral_code_used : user's referral code used

user_income_source : user's income source


 II. Transactions Dataset
DATA DICTIONARY - Daily User Balance Sept 2021

user_id : Client ID on the platform
date : Date of the user balance
Saham_AUM : AUM of equity mutual fund held by client to date
Saham_invested_amount : The total price paid by client to buy equity mutual fund to date.
Saham_transaction_amount : Total value of transaction to buy (if positive) or sell (if negative) equity mutual fund on the date. If there's no transaction, the value should be 0 or NA
Pasar_Uang_AUM : AUM of money market mutual fund held by client to date
Pasar_Uang_invested_amount : The total price paid by client to buy money market mutual fund to date
Pasar_Uang_transaction_amount : Total value of transaction to buy (if positive) or sell (if negative) money market mutual fund on the date. If there's no transaction, the value should be 0 or NA
Pendapatan_Tetap_AUM : AUM of fixed income mutual fund held by client to date
Pendapatan_Tetap_invested_amount : The total price paid by client to buy fixed income mutual fund to date
Pendapatan_Tetap_transaction_amount : Total value of transaction to buy (if positive) or sell (if negative) fixed income mutual fund on the date. If there's no transaction, the value should be 0 or NA
Campuran_AUM : AUM of mixed mutual fund held by client to date
Campuran_invested_amount : The total price paid by client to buy mixed mutual fund to date
Campuran_transaction_amount : Total value of transaction to buy (if positive) or sell (if negative) mixed mutual fund on the date. If there's no transaction, the value should be 0 or NA

# Pre Processing

I. cleaning Data 

I check every Outliers only in transaction amount columns for each mutual funds, because if I clean in transaction amount the other amount such as AUM and invested amount will be clean either, this is example one of product.
![image](https://user-images.githubusercontent.com/111065442/218638049-ac326a12-b50a-4c44-ba68-62b068fe2225.png)
