# Social Media Fact Checker
Our team consists of 4 members. Angela Tseng acts as the Project Manager, monitoring the activities of the team and supporting wherever is needed. Yogesh Boricha handles the role of Designer, creatively. Sadaf Davre works as the Programmer, also known as the implementor. As Programming Mentor, also known as the implementation lead, Abdul Shaik oversees the performance and execution of the code.

The external stakeholders in this scenario would be the social media users who are interested in fact checking the news that they get from their social media platforms. By simply searching for the hashtags or some keywords related to the post they want to check on our platform, they will pull up articles from reliable news outlets which would clarify if the news they just saw was correct or false. This website will be used as a means to stop the spread of misinformation on social media platforms. It will be implemented as a handy add-on feature for the social media users concerned about the reliability of their viral feeds. 

As a team, we are first going to extract top 100 hashtags which are related to social or political events. These hashtags may have a specific indication or also may be a source that creates misinformation on social media platforms. So, we will then undertake a comparison analysis of these hashtags with reliable news platform sources which can help us to do fact-checking. For example, #metoo tag went viral a couple of years back but it indicated a different meaning when it was used popularly on social media. So, fact-checking will help us with the correctness of information. To conclude, the primary goal of our task is to put out the news article on a website which has more than 60% accuracy. The requirement for the project would be a database management system to store and retrieve the data like Microsoft Access. We will also use tools to do web scraping for extracting the data from a website. 

We plan to develop a fact checking system via python and data mining. We will start off by data extraction through popular social media platforms. To be more specific, we begin by using Twitter as our primary source of hashtags. We build a simple hashtag extracter using the tweepy library. Our goal here is to provide solid news sources. We are going to use the PyGoogleNews module which acts as a wrapper library for the Google RSS feed. Once we do this, we will need a database for information storage. For this, we will be using Access and integrating with real-time data extraction and manipulation. Finally, in order to make it user-accessible we plan to build this on a Drupal web page which will have the functionality to be able to search through those hashtags.
