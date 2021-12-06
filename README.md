# starbucks_capstone_project

**Table of Contents**

1.Installation

2.File Descriptions

3.Problem to be solved

**Installation**

You need an environment for jupyter notebook. 

**File Descriptions**

•	portfolio.json

It consists of the offer details provided by the Starbucks. Like type of offer whether:

o	offer_type: the offer gives discount to customer, or is merely provides informational about new products, or is a Buy One Get One offer.

o	reward: If customer gets any reward when he avails the offer.

o	difficulty: how much the customer needs to spend in order to be eligible for the offer.

o	duration: offer validity period.

o	channels:  the mode through which customer is made aware of the offer.

•	profile.json 

It consists of the customer profiles like age, membership period, gender and their income.

•	transcript.json

It consists of the details of the customer response towards different offers. Some of the attributes include:

o	event: status of the offer sent to the customer, like if the customer has viewed the offer, accepted or availed it.

o	time: the time taken by customer to avail the offer.

o	value: a dictionary consisting of amount spent on the offer, the offer id or reward received by the customer depending on the event.


**Problem to be solved**

The problem to be solved is to analyze the customer behavior towards a particular. So it helps Starbucks in targeting the right customer group with each offer, some customer group might prefer BOGO offers, while others are more inclined towards discounts or some only respond to the offers received through emails and so on.
For this purpose, the whole task is to be divided into three parts:

1.	Data Exploration, Cleaning and Analysis
3.	Data Merging
4.	Machine Learning Classifier



