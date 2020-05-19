# Predictive_Analytics
Heterogenouse Treatment Effects with Causal Machine Learning 
Project for the Predictive Analytics Seminar at Humboldt Universitat zu Berlin SoSe 2020 


# Dataset Description:
This dataset contains 64,000 customers who last purchased within twelve months. The customers were involved in an e-mail test.
1/3 were randomly chosen to receive an e-mail campaign featuring Mens merchandise.
1/3 were randomly chosen to receive an e-mail campaign featuring Womens merchandise.
1/3 were randomly chosen to not receive an e-mail campaign.
During a period of two weeks following the e-mail campaign, results were tracked. Your job is to tell the world if the Mens or Womens e-mail campaign was successful.

Historical customer attributes at your disposal include:
Recency: Months since last purchase.
History_Segment: Categorization of dollars spent in the past year.
History: Actual dollar value spent in the past year.
Mens: 1/0 indicator, 1 = customer purchased Mens merchandise in the past year.
Womens: 1/0 indicator, 1 = customer purchased Womens merchandise in the past year.
Zip_Code: Classifies zip code as Urban, Suburban, or Rural.
Newbie: 1/0 indicator, 1 = New customer in the past twelve months.
Channel: Describes the channels the customer purchased from in the past year.
Another variable describes the e-mail campaign the customer received:
Segment
Mens E-Mail
Womens E-Mail
No E-Mail
Finally, we have a series of variables describing activity in the two weeks following delivery of the e-mail campaign:
Visit: 1/0 indicator, 1 = Customer visited website in the following two weeks.
Conversion: 1/0 indicator, 1 = Customer purchased merchandise in the following two weeks.
Spend: Actual dollars spent in the following two weeks.
