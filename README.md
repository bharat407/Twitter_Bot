# Twitter_Bot
 A sample Twitter bot in Python - created by [@bharat407(https://github.com/bharat407)

--------------------------------------------------------

## Set up

### How to install Tweepy

First, check your Python version with ``python3 --version`` or ``python --version`` on console (terminal/shell/command prompt).


#### If you don't have Python 3 installed (if the above command fails):

Install Python 3 on your computer.

For download Python[https://www.python.org/downloads/]

#### If you have Python 3.7, run the following instead:

``pip3 install -U git+https://github.com/tweepy/tweepy.git@2efe385fc69385b57733f747ee62e6be12a1338b``

If the above command doesn't work, try replacing ``pip3`` with ``pip`` also.

#### If you have Python 3.7 and want to use pipenv, use:

``pipenv install -e git+https://github.com/tweepy/tweepy.git@2efe385fc69385b57733f747ee62e6be12a1338b#egg=tweepy``

-------------------------------------------------------------------------------------------------------------------

## Files

- **my_twitter_bot.py** - This is the main file that includes all the logic.
- **last_seen_id.txt** - This will contain the ID of the tweet that my_twitter_bot.py has seen last. If you see any errors when running the main file, try replacing the content with the ID of one of the tweets you want to examine.
- **keys.py** - Put your Twitter API keys in keys.py. That way, my_twitter_bot.py will be able to use this information.
- 
## You must have

- A Twitter Account.
- After logging into your Twitter account, follow this link: https://apps.twitter.com/app/new to create a new application.

## Configuring and granting permissions from Twitter API

- Fill out the necessary fields in the form and click on the Create Your Twitter Application button. After creating the application, look for ‘Keys and Access Tokens’ and click on ‘Generate Token Actions’. Copy the:

- Consumer Key
- Consumer Secret
- Access Token
- Access Token Secret

**Please note that the consumer key, consumer secret, access_token and access_token_secret will differ for every different application**.
