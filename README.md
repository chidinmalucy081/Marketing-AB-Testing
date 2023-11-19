# Marketing-AB-Testing

## project overview 
Marketing companies want to run successful campaigns, but the market is complex and several options can work. So normally they tun A/B tests, that is a randomized experimentation process wherein two or more versions of a variable (web page, page element, banner, etc.) are shown to different segments of people at the same time to determine which version leaves the maximum impact and drive business metrics.

## Dataset https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing/download?datasetVersionNumber=1
## Goal 

The companies are interested in answering two questions:

Would the campaign be successful?
If the campaign was successful, how much of that success could be attributed to the ads?
With the second question in mind, we normally do an A/B test. The majority of the people will be exposed to ads (the experimental group). And a small portion of people (the control group) would instead see a Public Service Announcement (PSA) (or nothing) in the exact size and place the ad would normally be.

The idea of the dataset is to analyze the groups, find if the ads were successful, how much the company can make from the ads, and if the difference between the groups is statistically significant.

## Data dictionary:

1. Index: Row index
2. user id: User ID (unique)
3. test group: If "ad" the person saw the advertisement, if "psa" they only saw the public service announcement
4. converted: If a person bought the product then True, else is False
5. total ads: Amount of ads seen by person
6. most ads day: Day that the person saw the biggest amount of ads
7. most ads hour: Hour of day that the person saw the biggest amount of ads
