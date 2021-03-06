# Pink Python Bot
A python bot which needs to be feeded :snake:

## Requirements

- Python3
- pip
- A twitter app account
- An Api.ai account (in case of use it as NLP)

## Installation

    $ git clone https://github.com/mtnalonso/pinkpython-bot.git
    $ cd pinkpython-bot
    $ pip install -r requirements.txt

Create a credentials.py file as follows:

    CONSUMER_KEY = 'your_twitter_consumer_key'
    CONSUMER_SECRET = 'your_twitter_consumer_secret_key'
    ACCESS_TOKEN = 'your_twitter_access_token'
    ACCESS_TOKEN_SECRET = 'your_twitter_access_token_secret'

    TELEGRAM_TOKEN = 'your_telegram_bot_token'

    # only necessary if using API.ai
    APIAI_ACCESS_TOKEN_DEVELOPER = 'your_apiai_dev_token'
    APIAI_ACCESS_TOKEN_CLIENT = 'your_apiai_prod_token'

## Run

    $ cd pinkpython
    $ python3 pinkpython.py

To use only over a specific channel use the option -c or --channel

    $ python3 pinkpython.py -c telegram


## Test

    $ pip install -r test_requirements.txt
    $ pytest
