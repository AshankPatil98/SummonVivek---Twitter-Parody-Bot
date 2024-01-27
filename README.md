# SummonVivek---Twitter-Parody-Bot
Overview
The VivekRamaParodyBot is a Twitter bot that humorously parodies Vivek Ramaswamy, a well-known public figure. This bot employs a custom Language Model (LLM) created using Jupyter Labs, leveraging the power of GPT-3.5 architecture from OpenAI. The project utilizes the Twitter API for interaction, Python for scripting, Airtable for data storage, and Railway.app for hosting.

Features

Parody Tweets: The bot generates witty and satirical tweets in the style of Vivek Ramaswamy, adding a humorous twist to current events and trending topics.

Custom Language Model: The bot's language model is fine-tuned to capture the distinctive voice and tone of Vivek Ramaswamy, providing a convincing and entertaining parody experience.

Twitter API Integration: The bot interacts with the Twitter platform using the Twitter API, allowing it to post tweets, like, retweet, and respond to mentions, creating an engaging online presence.

Airtable Integration: Airtable is used as a data store for managing tweet history, user interactions, and other relevant information. This provides a structured and easily accessible repository for the bot's data.

Hosted on Railway.app: The bot is hosted on Railway.app, a platform that simplifies deployment and management of web applications. Railway.app ensures the bot is running reliably and consistently.

Setup
To run the VivekRamaParodyBot, follow these steps:

Clone the Repository: Clone this repository to your local machine.


Copy code
````
```git clone https://github.com/AshankPatil98/SummonVivek---Twitter-Parody-Bot.git```
````

Install Dependencies: Install the required Python libraries and dependencies.

Copy code

'''pip install -r requirements.txt'''

Twitter API Keys: Obtain Twitter API keys from the Twitter Developer Portal. Update the config.py file with your API keys.

Airtable Setup: Create an account on Airtable and set up a base for the bot. Update the config.py file with your Airtable API key and base information.

Railway.app Deployment: Sign up on Railway.app and deploy the bot following their documentation. Update the config.py file with the provided environment variables.

Run the Bot: Start the bot by running the main script.

Copy code

'''summonvivek.py'''

Usage
Once the bot is up and running, it will automatically post parody tweets, respond to mentions, and engage with the Twitter community in a humorous manner.

Feel free to customize the language model, tweet templates, and other settings according to your preferences.

Disclaimer

This bot is created for entertainment purposes only. Be mindful of Twitter's policies and guidelines when deploying and using this bot to ensure a positive online experience for everyone.

Happy parodying!