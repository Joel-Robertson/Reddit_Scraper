# Reddit_Scraper
A Reddit scraper written in Python that can act as a news aggregator for various subreddits.

In order to use this subreddit scraper, a valid Reddit account and a developer app is needed. The developer app is free and takes 1 minute to create.
Step 1)
Navigate to this URL:
    https://www.reddit.com/prefs/apps
And at the very bottom left of the page click the "Create app" button.

Step 2)
Fill in the required fields:
    Name: Reddit_Scraper
    Description: A Reddit scraper written in Python that can act as a news aggregator for various subreddits.
    Redirect URL: http://localhost:8080
The about URL can be left blank. The radio button should be on the "Script" option.

Step 3)
Record your 14 character "Personal Use Script" number and your 27 character "Secret" key somewhere safe.
Use this information to populate the following code block in the scraper:

reddit = praw.Reddit(client_id='PERSONAL_USE_SCRIPT_14_CHARS', \
                     client_secret='SECRET_KEY_27_CHARS ', \
                     user_agent='YOUR_APP_NAME', \
                     username='YOUR_REDDIT_USER_NAME', \
                     password='YOUR_REDDIT_LOGIN_PASSWORD')

Step 4) Open the "PY_scraper" file and run the script.
