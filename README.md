# Startup-Campus-Assignment-1
Assignment 1: Foundation for Artificial Intelligence Artificial Intelligence Track • Startup Campus, Indonesia

## Deskripsi Tugas

### B.2 Tugas Kelompok (Soal Nomor 2 dan Nomor 3)

#### SOAL NOMOR 2

Background

I Want to Withdraw All My Savings in Cash!
As we know, in Indonesia there are several denominations of money as follows:
Paper Money:
Rp 100,000 Rp 50,000
Rp 5,000

Rp 20,000
Rp 2,000

Rp 10,000

Coins:
Rp 1,000 Rp 500 Rp 200 Rp 100
*To make it easier, we assume that all Rp. 1000 denominations are coins.
There are circumstances where the bank must liquidate all customer savings in the form of money, if the
customer requests it.
And imagine this is happening right now in front of you, help the bank to calculate how many
denominations of money are needed.

Here is the rule:
1. Banks must prioritize the largest denominations first to be issued.
2. If there is a balance that cannot be cashed, the bank must inform it.
3. Bank must calculate how many number of Paper Money needed and Coins needed.
4. Banks can only disburse a maximum amount of 1 billion Rupiah.

Task
Make a python code that receives an integer number of customer savings from 0 - 1 Billions.
The output is telling the bank:
1. How many Rp 100,000 , Rp 50,000 , Rp 20,000 and so on needed to fulfill the request.
2. How many number of Paper Money and Coins needed (sum of paper money and coins).
3. What is the amount that cannot be cashed.
   
Example:
Input
>> 2000000000
Output
>> Maximum Saving is 1000000000

Input
>> -100
Output
>> Please input the correct number
Example Correct Answer:
Input
>> 1245123
Output
>> amount of currency Rp 100,000: 12
>> amount of currency Rp 50,000: 0
>> amount of currency RP 20,000: 2
>> amount of currency Rp 10,000: 0
>> amount of currency Rp 5,000: 1
>> amount of currency Rp 2,000: 0
>> amount of currency Rp 1,000: 0
>> amount of currency Rp 500: 0
>> amount of currency Rp 200: 0
>> amount of currency Rp 100: 1
>> Total Paper Money: 15
>> Total Coins: 1

>> Cannot be cashed out: 23
Example False Answer:
Input
>> 1245123
Output
>> amount of currency Rp 100,000: 12
>> amount of currency Rp 50,000: 0
>> amount of currency RP 20,000: 0
>> amount of currency Rp 10,000: 4
>> amount of currency Rp 5,000: 1
>> amount of currency Rp 2,000: 0
>> amount of currency Rp 1,000: 0
>> amount of currency Rp 500: 0
>> amount of currency Rp 200: 0
>> amount of currency Rp 100: 1
>> Total Paper Money: 17
>> Total Coins: 1
>> Cannot be cashed out: 23
*even the total is correct, but it passes the largest denomination of money on top of Rp 10,000.
You need to prioritize Rp 20,000 first.

#### SOAL NOMOR 3

Background
HR professionals generally lag behind with respect to analytics and data visualization competency. Thus,
Dr. Carla Patalano set out to create their own HR-related dataset, which is used in one of the graduate
MSHRM courses called HR Metrics and Analytics, at New England College of Business. He created this
data set.
We will use the data set to analyze the data and make some prediction models.

Dataset
(link dataset)

Tasks
1. Answer multiple aggregations questions using Pandas. (please refer to .ipynb for detailed
questions)
2. Perform EDA on the target to find out how many feature variables are related to the
termination of an employee's employment. (Most reasons, by department, by gender, etc.)

Create data visualization according to EDA Steps (minimum 5 visualizations). Give us an insight
from this step.
3. Answer this question:
a. Is there any relationship between who a person works for (their manager) and their
performance score?
b. What are our best recruiting sources if we want to ensure a low ratio of termination?
