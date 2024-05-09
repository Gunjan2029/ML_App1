
Will a Customer Accept the Coupon?

**Goal**
The goal of this project is to use visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

**Data:**
As stated in the Program Module: "This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks people whether they will accept the coupon if they are the driver. Answers given that the users will drive there “right away” or “later before the coupon expires” are labeled as “Y = 1”, and answers “no, I do not want the coupon” are labeled as “Y = 0”. There are five different types of coupons—less expensive restaurants (under $20), coffee houses, carry out and take away, bars, and more expensive restaurants ($20–$50)."

**Scope:** Out of 5 different types of Coupons, my analysis will focus on Bar & more expensive restaurants ($20–$50) Coupons.

**Link to the Notebook:** https://github.com/Gunjan2029/ML_App1/blob/main/ML_Coupons.ipynb

**Link to the Data:** https://github.com/Gunjan2029/ML_App1/tree/main/Data

**Summary of Findings**
**Bar Coupon Summary:**
* The more a user visits bar on a monthly basis, they are most likely to accept bar Coupons.

* There is a strong correlation between acceptance rate and Bar frequency of users.

* Passengers does influence bar visits and users are more likely to accept coupon when they are not traveling with a kid.

* The __Target Audience__ for this coupon are drivers above 25, not traveling with kids and who visit bar more than 3 monthly visits.

**More expensive restaurants ($20–$50) Coupons Summary:**
* Users with Kids are more likely to accpet Restaurant Coupons in the afternoon and early eve around 6 PM.

* If a User is traveling alone, time of the day matters a lot. As you see above, there is no acceptance rate at 10 AM & 2 PM. They are most likely to go skip expensive restaurants.

* Coupon Acceptance chances are higher when offere to Users traveling with Partner, Friends or Kids during Lunch hour and around 5 PM when a User is traveling alone.

* Based on income of the User(s) or the monthly visits, direction has very little impact on coupon acceptance rate. There is an equal chance of them accepting the coupons if offered.
  
* The Restaurant 20-50 Coupons and Bars have similar acceptance rate when it comes to monthly visits.

* The __Target audience__ for this Coupon are drivers who are not alone, and are traveling around lunch hours (1-2 PM) and early dinner Hours (5-7 PM)

**Refer to the Linked Jupyter Notebooks for Code & Visualizations.**



