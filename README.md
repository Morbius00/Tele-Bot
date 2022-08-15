![Star Badge](https://img.shields.io/static/v1?label=%F0%9F%8C%9F&message=If%20Useful&style=style=flat&color=BC4E99)
![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)

# Tele-Bot
Send message to Telegram user using Python.

Have you ever wondered how people do automation on Telegram? You may know that Telegram has a big user base and so it is one of the preferred social media to read people. What good thing about Telegram is that it provides a bunch of API’s methods, unlike Whatsapp which restricts such things. So in this post, we will be sharing how to send messages to a Telegram user using Python.

# ⚙️🛠️Getting Started:
First, create a bot using Telegram BotFather. To create a BotFather follow the below steps – 
 
* Open the telegram app and search for @BotFather.
* Click on the start button or send “/start”.
* Then send “/newbot” message to set up a name and a username.
* After setting name and username BotFather will give you an API token which is your bot token. 
 
 Then create an app on the telegram. Follow the below steps – 
 
* Log into the telegram core: https://my.telegram.org
* Go to ‘API development tools’ and fill out the form.
* You will get the api_id and api_hash parameters required for user authorization.
 
## Modules needed ⚙️
You need several Python library imports for the script functioning. 
 
* telebot: To install this module type the below command in the terminal.
```sh
pip install telebot
```

* telethon: To install this module type the below command in the terminal.
```sh
pip install telethon
```

