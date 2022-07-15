# StockMarket-TwitterSentimentAnalysis_TwitterAPI

This is a Twitter Sentiment Analysis Application that used the Twitter API to get a certain number of Tweets based on one word as reference.
- The <a href="https://github.com/n-rohit/StockMarket-TwitterSentimentAnalysis_TwitterAPI/blob/main/10Stocks_Twitter_Sentiment_Analysis.ipynb">10Stocks_Twitter_Sentiment_Analysis.ipynb</a> file fetches tweets related to 10 Stocks from Twitter for the purpose of Sentiment Analysis. The information about what stock to choose is taken from the <a href="https://www.bseindia.com/markets.html">BSE India</a> website.
- The concept of Getting Tweets using the Twitter API based on one word as the Search Parameter is taken from the <a href="https://github.com/n-rohit/StockMarket-TwitterSentimentAnalysis_TwitterAPI/blob/main/Twitter_Sentiment_Analysis.ipynb">Twitter_Sentiment_Analysis.ipynb</a> file.

Simply put, <i><b>10Stocks_Twitter_Sentiment_Analysis.ipynb</b></i> is a Generalized form of <i><b>Twitter_Sentiment_Analysis.ipynb</b></i>.

- The <a href="https://github.com/n-rohit/StockMarket-TwitterSentimentAnalysis_TwitterAPI/blob/main/auth.csv">auth.csv</a> is the file which contains only one column named <b>key</b> that contans the following values:
  - <i>your twitter app</i> - <b>API KEY</b>
  - <i>your twitter app</i> - <b>API KEY SECRET</b>
  - <i>your twitter app</i> - <b>ACCESS TOKEN</b>
  - <i>your twitter app</i> - <b>ACCESS TOKEN SECRET</b>

These values of the <b>key</b> column must be replaced with the actual keys that you can retrieve by Following the Steps Below:
- Goto The <a href="https://developer.twitter.com/en">Twitter Developer</a> Website.
- Signup or Login to your <a href="https://twitter.com/">Twitter</a> profile.
- Now, go to your Twitter Developer Portal <a href="https://developer.twitter.com/en/portal/dashboard">Dashboard</a>
- Create a New Project and then create a new App in that project.
- Initially, you are given the <a href="https://developer.twitter.com/en/portal/products/essential">Essential</a> Access which is not suffiecient for getting the data we need. <br>
<i>(You will get an Error if you execute the program at this stage, Mentioning that you need to apply for the Elevated Access)</i>
- So, we need to fill up an Application Form to apply for an <a href="https://developer.twitter.com/en/portal/products/elevated">Elevated</a> Access for your App.
- If you have filled all the Details correctly and answered all the Questions well, you will get the <b>Elevated</b> Access for your App in a few days.

Now, you can enter the <i>API KEY, API KEY SECRET, ACCESS TOKEN and ACCESS TOKEN SECRET</i> in the <a href="https://github.com/n-rohit/StockMarket-TwitterSentimentAnalysis_TwitterAPI/blob/main/auth.csv">auth.csv</a> file as per the Above Instructions and execute both the <b>.ipynb</b> files

If in any case, you do not get the <b>Elevated</b> Access, please check your email to see if you have recieved any mails from the <a href="developer-accounts <developer-accounts@twitter.com>">Twitter Developer's Team</a>. This will occur only if you did not answer any of the Questions properly. The Developer team will ask you to reply the answers to them again in more detail, and if you were able to do that successfully, then you will get your <b>Elevated</ab> Access.

<b><i>If Twitter's Developer Team do not find your Responses to be Appropriate, they will reject the Application immediately. So answer the Questions Properly.</i></b>
