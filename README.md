
# This is starbuck challenge data science capstone project for Udacity Data science nano degree program.
## Starbucks Capstone Challenge
Project in Data Scientist Nanodegree of Udacity

### Table of Contents
1. Installation
2. Project Motivation
3. File Descriptions
4. Results
5. Licensing, Authors, and Acknowledgements
6. Installation

<h2>Installation</h2>
I would recommend to use anoconda and jupyter libraries.

<h2>Project Motivation</h2>
It is the Starbuck's Capstone Challenge of the Data Scientist Nanodegree in Udacity. We get the dataset from the program that creates the data simulates how people make purchasing decisions and how those decisions are influenced by promotional offers. We want to make a recommendation engine that recommends Starbucks which offer should be sent to a particular customer.

We are interested to answer the following two questions:

Which offer should be sent to a particular customer to let the customer buy more?
Which demographic groups respond best to which offer type?
File Descriptions
The notebook available here showcases work related to the above questions.

<h2>File Descriptions</h2>

profile.json
Rewards program users (17000 users x 5 fields)

gender: (categorical) M, F, O, or null
age: (numeric) missing value encoded as 118
id: (string/hash)
became_member_on: (date) format YYYYMMDD
income: (numeric)
portfolio.json
Offers sent during 30-day test period (10 offers x 6 fields)

reward: (numeric) money awarded for the amount spent
channels: (list) web, email, mobile, social
difficulty: (numeric) money required to be spent to receive reward
duration: (numeric) time for offer to be open, in days
offer_type: (string) bogo, discount, informational
id: (string/hash)
transcript.json
Event log (306648 events x 4 fields)

person: (string/hash)
event: (string) offer received, offer viewed, transaction, offer completed
value: (dictionary) different values depending on event type
offer id: (string/hash) not associated with any "transaction"
amount: (numeric) money spent in "transaction"
reward: (numeric) money gained from "offer completed"
time: (numeric) hours after start of test


<h2>Result</h2>
The main findings of the code can be found at the post available here.

Customers income ranges from 30,000 and 120,000 with most of the customers’ incomes fall between 50,000 and 75,0000.

According to the available data, There are three ‘gender’ categories into which the customers falls in ( M, F and O).

The most common offer type among all age groups is the BOGO , followed by the Discount Offers. Whereas, the least common offer to be sent is the informational offers. I believe that BOGO offers are more attractive compared to other offers provided by Starbucks.

Customers with High income (Above 90,000) are mostly female customers. Whereas, Average Income(30,000 - 60,000) customers are mostly males.

Males and Females are pretty close when it comes to the time spent to complete an offer. Both males and females take about 17 days to da so.

2017 was the best year for Starbucks in terms of the number of new members. Around %38 of all the customers on our dataset regiseterd as members on this specific year.

Both genders like BOGO and Discount offers and they have the same reaction toward Informational offers, they both seem to be not interested to it.

The mean time it takes a customer to complete an offer is less than 16 days (372 hours).

Females completed around 75% of the offers they viewed, it is 16% more than males who just completed 58% of the offers they viewed. 

Feamles seems to be convinced by the promotion easier than males.

<h2>Licensing, Authors, Acknowledgements</h2>

Must give credit to Stakbucks for the data.

### Author
Saphal Adhikari

