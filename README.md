# A/B Testing Project
This project was made as I was taking part in School of Analytics Hackathon 2023. In the following, you'll see the spec of the case.

## Introduction
AdTech agency TechDesign, which provides solutions in the field of advertising technologies, has developed a new model for calculating the rate (i.e. cost per click) for ads for an advertising campaign. As an alternative to the existing “Maximum Bet” bidding model, the company introduced a new advertising solution – the “Average Bet” bidding model.
After introducing the new option, the eStore company, which is one of the agency’s clients and conducts a retargeting advertising campaign using the “Maximum Bid” model, decided to test an alternative calculation model.
In order to make a comparison between the “Average Rate” and “Maximum Rate” calculation models, eStore conducted A/B testing over the next month. As part of this case, I will have to analyze the results of A/B testing and submit an analytical report to the company’s management. I have received data with the results of an A/B test and want to make sure that the experiment was carried out correctly and the result was statistically reliable.

# My Steps 
First things first, I have determined the following steps for myself (which all can be viewed in .ipynb file): <br>
Task 1. Checking the division of observations into experimental and control groups based on data obtained after the experiment. <br>
Task 2. Calculation of metrics based on data obtained after the experiment. Checking normality of distribution. <br>
Task 3. Formulating a hypothesis. Selection of a statistical criterion for testing a hypothesis. <br>
Task 4. Defining parameters for A/B groups. Conducting an A/A test to evaluate parameters. Checking the representativeness and homogeneity of samples <br>
Task 5. Calculating key metrics. Assessment of the statistical significance of the results obtained. Estimation of errors of the first and second types. 

# Data
Data collected within 30 days of the start of the experiment is contained in the file “test_group.csv”. The file "control_group.csv" contains data of users included in the control group. The description and data type of the variables are given in the table below:

Name | Data Type | Description
Campaign Name | object | division into experimental and control groups Date object # date of the advertising campaign
Total Advertising Spend (USD) | int64 | advertising costs
Total Impressions Count | int64 | user viewing an advertisement
Total Reach Count | int64 | unique users who viewed the ad
Total Clicks on Website | int64 | users who accessed the site via a link in an advertisement
Total Searches Initiated | int64 | the user performs a search on the site
Total View Content Actions | int64 | user viewing product details
Total Add to Cart Actions | int64 | user adding an item to the cart
Total Purchases Count | int64 | user purchase of goods
