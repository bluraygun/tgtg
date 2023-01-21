# Bot for [Too good to go](https://toogoodtogo.com)

Forked from https://github.com/kacpi2442/am_bot

This application scrapes info from the Too good to go and sends a notification via a Telegram bot as soon as some items in your area are available.

## Usage:
### Install required libraries:
```pip install -r requirements.txt```
### Create config file:
```cp config.example.json config.json```
### Edit config file:
- Insert your bot token (you can get it from [@BotFather](https://t.me/BotFather). More info [here](https://medium.com/@ManHay_Hong/how-to-create-a-telegram-bot-and-send-messages-with-python-4cf314d9fa3e))
- Insert your location info (i use [latlong.net](https://www.latlong.net/))
- Insert notification range (in kilometers)
### Run the script:
```python3  watch_script.py```

 On the first run the script will ask for your tgtg email address to get the needed API keys, and it will ask you to authorize your Telegram account by sending 6 digit pin to the bot.
