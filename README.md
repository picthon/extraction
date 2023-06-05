# Extract IP ID and IP HashBot

~~(yet)~~ another my.telegram.org scrapper inside Telegram.

### ⚠ legal DISclaimER 🚸
please treat your APP ID and API HASH with care, and ensure that they do not fall into wrong hands.

**Telegram said**: __It is forbidden to pass this value to third parties__.


## Frequently Asked Questions

- Should you Trust this bot?
  - **NO**. __you should never sent any of your private credentials to unknown third-party Telegram Bots__. This bot / source code was an attempt to scrap `my.telegram.org` using `Python3` libraries.


## installing

#### The Easy Way

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)


#### The Legacy Way

- clone the repository, locally.
```sh
git clone https://github.com/picthon/extraction.git
```

- change the directory.
```sh
cd Extract IP ID and IP HashBot
```

- create a virtual environment.
```sh
virtualenv -p /usr/bin/python3 venv
```

- activate the virtual environment.
```sh
. ./venv/bin/activate
```

- install the requirements.
```sh
pip install -r requirements.txt
```

- create config.py

- run the bot
```sh
python3 bot.py
```


- Only `TG_BOT_TOKEN` environment variables is mandatory.
- The Telegram RoBot should work without setting the non-mandatory variables.


## learning

check out the [helper_funcs](https://github.com/picthon/extraction/tree/main/helper_funcs) directory, to see how my.telegram.org is scrapped.

## LICENSE
[AGPLv3](https://github.com/picthon/extraction/blob/main/LICENSE)

## credits

- Libraries Used:
  - [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)
  - [requests](https://github.com/psf/requests)
  - [beautifulsoup4](https://pypi.org/project/beautifulsoup4)
- Thanks to:
  - [me](https://t.me/a_t_9)
