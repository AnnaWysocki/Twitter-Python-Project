# Twitter-Python-Project
This project consists of three steps. 

1) Using Twitter's API to collect tweets from accounts that regularly post tweets about vaccination. All tweets were filtered in search for key words (e.g., vaccinations, vaccine etc). The accounts were either accounts that post mis-information about vaccinations or accurate information. Additionally, we collected other variables such as number of favorites and retweets to include as features in future models. 

2) Using sentiment analysis, we analyzed the content of individual tweets to categorize tweets as either positve, negative, or neutral. Additionally, we assessed a continuous version of the tweets sentiment (0 = negative, 1 = positive) as well as the subjectivity. 

3) Using machine learning, we used SVM to classify tweets as either mis-information or true information based on the features number of retweets and number of favorites as well as the categorical version of the sentiment variable. 
 
