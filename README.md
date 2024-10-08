                Stock Movement Analysis Using Reddit API

Description

        This project analyzes stock movements based on discussions from Reddit. 
        It fetches stock-related discussions from relevant subreddits using the Reddit API and performs sentiment analysis to understand how market sentiment is correlated with stock price movements.

Prerequisites

Ensure that you have the following software installed:

        Python 3.x: Make sure you're running Python 3.x. Download Python.

        pip: The Python package manager, generally comes pre-installed with Python.

        Additionally, you'll need a Reddit API application to access Reddit's data.

Step 1: Create Reddit API Credentials

To access Reddit data, you will need to create an app on Reddit and obtain the following credentials:

        Client ID

        Client Secret

        User-Agent

Follow these steps to create an app and get the credentials:

        Go to Reddit App Preferences.

        Scroll down to "Developed Applications" and click "Create App" or "Create Another App".

        Fill in the required fields:

        name: Name of your app.

        App type: Choose "script".

        description: Short description of your app.

        about url: Leave empty or provide an appropriate URL.

        permissions: "Read" permission is enough.

        redirect uri: Use http://localhost:8888.

        developer: Your username.

        After creating the app, you'll see your Client ID, Client Secret, and User-Agent.

3. Install dependencies
        pip install praw pandas matplotlib nltk vaderSentiment

4. Set Up Reddit API Credentials
   
        REDDIT_CLIENT_ID='your_client_id'

        REDDIT_CLIENT_SECRET='your_client_secret'

        REDDIT_USER_AGENT='your_user_agent'
