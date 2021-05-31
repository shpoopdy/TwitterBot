# Twitter Bot
CS 232 - Python Programming - Spring 2021  
*Python Version 3.6*

```
pip install tweepy
pip install gspread
pip install google-auth-oauthlib
```
# Bot Page
https://twitter.com/Nelja_Games

# Getting Started
If you would like to run this you'll need a Twitter developer account and the consumer key,
consumer secret, auth key, and auth secret for your bot. Once you have those run the setup script to
have it create your config.py. Tweepy will be enough to have it run with the given information,
the regular tweet function gets a little more involved with google api.




# Regular Tweet
The regular_tweet pulls its tweets from a google sheet so it requires credentials
to use and an email for the Bot if you do not wish to use your personal email. In the
link is the step by step guide by Google for accessing your app credentials.
https://developers.google.com/workspace/guides/create-credentials
